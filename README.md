Website of hidet
================

This is the website of hidet hosted at https://hidet.org.

## Website repo strcuture
The repo https://github.com/hidet-org/hidet-org.github.io has the following structure:
- **3rdparty/netron** - we have a modified version of netron to visualize our FlowGraph
- **html/**  - the whole folder will be published
  - **index.html**  - this index.html is used to direct `hidet.org` to `https://hidet.org/docs/stable/index.html`
  - **docs** - documentation for different versions of hidet
    - **v0.1** - hidet v0.1 docs
    - ...
    - **stable** - a softlink to the lastest documentation, currently, it points to `v0.3.0`. 
       We need to use `$ ln -s` to generate it.

## Steps to publish documentation for new hidet version

### 0. Update the meta information (when needed)
Under the hidet repo, check the meta information in `docs/source/conf.py`. Focus on the copyright (the year), and the release version. (serach the keyword and we will find the assignment, like `copyright='2023, Hidet Authors'`). 

### 1. Build documentation
Still under the hidet repo, 
```bash
$ cd docs
$ pip install -r requirements.txt
$ make clean; make html
```
There will be a folder `build/html` that contains the built documentation.

### 2. Upload the built documentation to website repo
We first copy the built website `build/html` to the website repo (`html/docs/{hidet-version}`).  
```bash
$ cp -r <hidet-repo>/docs/build/html <website-repo>/html/docs/v0.x.x  # change v0.x.x to the correct version
```
After that, we change the stable link file
```bash
$ rm stable # remove the old softlink 
$ ln -s -T v0.x.x stable # create the new softlink, replace the v0.x.x to the version of docs
```
And finally commit and push
```bash
$ git commit -m "Update docs v0.x.x"
$ git push
```

### 3. Check the published website
After we commit to the main branch of our website repo, the website will be automatically deployed to https://hidet.org. Check that everything looks good.
