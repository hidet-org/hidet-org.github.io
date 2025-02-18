:orphan:

Index
=====



.. raw:: html

    <div class="sphx-glr-thumbnails">

.. thumbnail-parent-div-open

.. thumbnail-parent-div-close

.. raw:: html

    </div>




.. raw:: html

    <div class="sphx-glr-thumbnails">

.. thumbnail-parent-div-open

.. raw:: html

    <div class="sphx-glr-thumbcontainer" tooltip="This is a tutorial introduces the operator resolving mechanism and how to add a new operator resolve rule. An operator resolve rule is used to resolve an operator to other operators. Usually, we would resolve a more generic operator to more specific and efficient operators. The operator resolving rules allow us to reuse existing highly-optimized operators to implement a new operator, while organizing the operators in a more modular way.">

.. only:: html

  .. image:: /gallery/developer-guides/images/thumb/sphx_glr_add-operator-resolve-rule_thumb.png
    :alt:

  :ref:`sphx_glr_gallery_developer-guides_add-operator-resolve-rule.py`

.. raw:: html

      <div class="sphx-glr-thumbnail-title">Add Operator Resolve Rule</div>
    </div>


.. raw:: html

    <div class="sphx-glr-thumbcontainer" tooltip="In the previous tutorial, we have learned how to define the computation using compute primitives and wrap it into a :py~hidet.ir.task.Task. In this tutorial, we will learn how to add an operator (i.e., :py~hidet.graph.Operator) with given computation definition, and use hidet&#x27;s provided rule-based scheduler to automatically schedule the computation into a tensor program.">

.. only:: html

  .. image:: /gallery/developer-guides/images/thumb/sphx_glr_add-new-operator-rule-based_thumb.png
    :alt:

  :ref:`sphx_glr_gallery_developer-guides_add-new-operator-rule-based.py`

.. raw:: html

      <div class="sphx-glr-thumbnail-title">Using Rule-based Scheduling</div>
    </div>


.. raw:: html

    <div class="sphx-glr-thumbcontainer" tooltip="This guide describes how to add an operator mapping for PyTorch.">

.. only:: html

  .. image:: /gallery/developer-guides/images/thumb/sphx_glr_add-torch-operator-mapping_thumb.png
    :alt:

  :ref:`sphx_glr_gallery_developer-guides_add-torch-operator-mapping.py`

.. raw:: html

      <div class="sphx-glr-thumbnail-title">Add PyTorch Operator Mapping</div>
    </div>


.. raw:: html

    <div class="sphx-glr-thumbcontainer" tooltip="This tutorial shows how to add a sub-graph rewrite rule in the graph optimization pipeline. Sub-graph rewriting is an important technique in graph optimization. It is used to replace a sub-graph with another sub-graph, which is usually more efficient than the original one. For example, we can replace a sub-graph with two matrix multiplications sharing the same input and one addition with a concatenation and a single matrix multiplication:">

.. only:: html

  .. image:: /gallery/developer-guides/images/thumb/sphx_glr_add-subgraph-rewrite-rule_thumb.png
    :alt:

  :ref:`sphx_glr_gallery_developer-guides_add-subgraph-rewrite-rule.py`

.. raw:: html

      <div class="sphx-glr-thumbnail-title">Add Sub-Graph Rewrite Rule</div>
    </div>


.. raw:: html

    <div class="sphx-glr-thumbcontainer" tooltip="Each operator takes a list of input tensors and produces a list of output tensors:">

.. only:: html

  .. image:: /gallery/developer-guides/images/thumb/sphx_glr_add-new-operator-compute-definition_thumb.png
    :alt:

  :ref:`sphx_glr_gallery_developer-guides_add-new-operator-compute-definition.py`

.. raw:: html

      <div class="sphx-glr-thumbnail-title">Define Operator Computation</div>
    </div>


.. raw:: html

    <div class="sphx-glr-thumbcontainer" tooltip="  More details about hidet script and how to write dynamic kernel are coming soon.">

.. only:: html

  .. image:: /gallery/developer-guides/images/thumb/sphx_glr_hidet-script-dynamic-kernel_thumb.png
    :alt:

  :ref:`sphx_glr_gallery_developer-guides_hidet-script-dynamic-kernel.py`

.. raw:: html

      <div class="sphx-glr-thumbnail-title">Writing Dynamic kernel</div>
    </div>


.. raw:: html

    <div class="sphx-glr-thumbcontainer" tooltip="In the previous tutorial, we have learned how to define a new operator with rule-based scheduling. Rule-based scheduling is a convenient way to define a new operator, but it is not efficient enough for operators with large amount of reduction. In this tutorial, we will learn how to define a new operator with template-based scheduling. Template-based scheduling allows us to define a tensor program template, and the template will be instantiated for different input shapes and tunable hyper-parameters.">

.. only:: html

  .. image:: /gallery/developer-guides/images/thumb/sphx_glr_add-new-operator-template-based_thumb.png
    :alt:

  :ref:`sphx_glr_gallery_developer-guides_add-new-operator-template-based.py`

.. raw:: html

      <div class="sphx-glr-thumbnail-title">Using Template-based Scheduling</div>
    </div>


.. thumbnail-parent-div-close

.. raw:: html

    </div>

Index
=====


.. raw:: html

    <div class="sphx-glr-thumbnails">

.. thumbnail-parent-div-open

.. raw:: html

    <div class="sphx-glr-thumbcontainer" tooltip="This guide walks through the key functionality of Hidet for tensor computation.">

.. only:: html

  .. image:: /gallery/getting-started/images/thumb/sphx_glr_quick-start_thumb.png
    :alt:

  :ref:`sphx_glr_gallery_getting-started_quick-start.py`

.. raw:: html

      <div class="sphx-glr-thumbnail-title">Quick Start</div>
    </div>


.. thumbnail-parent-div-close

.. raw:: html

    </div>

Index
=====


.. raw:: html

    <div class="sphx-glr-thumbnails">

.. thumbnail-parent-div-open

.. raw:: html

    <div class="sphx-glr-thumbcontainer" tooltip="Vector Addition">

.. only:: html

  .. image:: /gallery/hidet-script/images/thumb/sphx_glr_2-vector-addition_thumb.png
    :alt:

  :ref:`sphx_glr_gallery_hidet-script_2-vector-addition.py`

.. raw:: html

      <div class="sphx-glr-thumbnail-title">Vector Addition</div>
    </div>


.. raw:: html

    <div class="sphx-glr-thumbcontainer" tooltip="Scalar Addition">

.. only:: html

  .. image:: /gallery/hidet-script/images/thumb/sphx_glr_1-scalar-addition_thumb.png
    :alt:

  :ref:`sphx_glr_gallery_hidet-script_1-scalar-addition.py`

.. raw:: html

      <div class="sphx-glr-thumbnail-title">Scalar Addition</div>
    </div>


.. raw:: html

    <div class="sphx-glr-thumbcontainer" tooltip="In this example, we will show you how to use hidet to write a simple &quot;Hello World&quot; program.">

.. only:: html

  .. image:: /gallery/hidet-script/images/thumb/sphx_glr_0-hello-world_thumb.png
    :alt:

  :ref:`sphx_glr_gallery_hidet-script_0-hello-world.py`

.. raw:: html

      <div class="sphx-glr-thumbnail-title">Hello World!</div>
    </div>


.. raw:: html

    <div class="sphx-glr-thumbcontainer" tooltip="Naive Matrix Multiplication">

.. only:: html

  .. image:: /gallery/hidet-script/images/thumb/sphx_glr_4-naive-matmul_thumb.png
    :alt:

  :ref:`sphx_glr_gallery_hidet-script_4-naive-matmul.py`

.. raw:: html

      <div class="sphx-glr-thumbnail-title">Naive Matrix Multiplication</div>
    </div>


.. raw:: html

    <div class="sphx-glr-thumbcontainer" tooltip="Kernel Functions">

.. only:: html

  .. image:: /gallery/hidet-script/images/thumb/sphx_glr_3-kernel-functions_thumb.png
    :alt:

  :ref:`sphx_glr_gallery_hidet-script_3-kernel-functions.py`

.. raw:: html

      <div class="sphx-glr-thumbnail-title">Kernel Functions</div>
    </div>


.. raw:: html

    <div class="sphx-glr-thumbcontainer" tooltip="In this example, we show you how to write a more efficient matrix multiplication kernel on NVIDIA GPU that uses shared memory. For simplicity, we omitted some optimizations like software pipelining (see our `paper`_ for more details).">

.. only:: html

  .. image:: /gallery/hidet-script/images/thumb/sphx_glr_5-efficient-matmul_thumb.png
    :alt:

  :ref:`sphx_glr_gallery_hidet-script_5-efficient-matmul.py`

.. raw:: html

      <div class="sphx-glr-thumbnail-title">More Efficient Matrix Multiplication</div>
    </div>


.. thumbnail-parent-div-close

.. raw:: html

    </div>

Index
=====


.. raw:: html

    <div class="sphx-glr-thumbnails">

.. thumbnail-parent-div-open

.. raw:: html

    <div class="sphx-glr-thumbcontainer" tooltip="Visualization is a key component of a machine learning tool to allow us have a better understanding of the model.">

.. only:: html

  .. image:: /gallery/how-to-guides/images/thumb/sphx_glr_visualize-flow-graph_thumb.png
    :alt:

  :ref:`sphx_glr_gallery_how-to-guides_visualize-flow-graph.py`

.. raw:: html

      <div class="sphx-glr-thumbnail-title">Visualize Flow Graph</div>
    </div>


.. thumbnail-parent-div-close

.. raw:: html

    </div>

Tutorials
=========


.. raw:: html

    <div class="sphx-glr-thumbnails">

.. thumbnail-parent-div-open

.. raw:: html

    <div class="sphx-glr-thumbcontainer" tooltip="Hidet provides a backend to pytorch dynamo to optimize PyTorch models. To use this backend, you need to specify &#x27;hidet&#x27; as the backend when calling torch.compile such as">

.. only:: html

  .. image:: /gallery/tutorials/images/thumb/sphx_glr_optimize-pytorch-model_thumb.png
    :alt:

  :ref:`sphx_glr_gallery_tutorials_optimize-pytorch-model.py`

.. raw:: html

      <div class="sphx-glr-thumbnail-title">Optimize PyTorch Model</div>
    </div>


.. raw:: html

    <div class="sphx-glr-thumbcontainer" tooltip="This tutorial walks through the steps to run a model in ONNX format with Hidet. The ResNet50 onnx model exported from PyTorch model zoo would be used as an example.">

.. only:: html

  .. image:: /gallery/tutorials/images/thumb/sphx_glr_optimize-onnx-model_thumb.png
    :alt:

  :ref:`sphx_glr_gallery_tutorials_optimize-onnx-model.py`

.. raw:: html

      <div class="sphx-glr-thumbnail-title">Optimize ONNX Model</div>
    </div>


.. thumbnail-parent-div-close

.. raw:: html

    </div>


.. toctree::
   :hidden:
   :includehidden:


   /gallery/developer-guides/index.rst
   /gallery/getting-started/index.rst
   /gallery/hidet-script/index.rst
   /gallery/how-to-guides/index.rst
   /gallery/tutorials/index.rst



.. only:: html

 .. rst-class:: sphx-glr-signature

    `Gallery generated by Sphinx-Gallery <https://sphinx-gallery.github.io>`_
