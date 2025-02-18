

.. _sphx_glr_gallery_developer-guides:




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


.. toctree::
   :hidden:

   /gallery/developer-guides/add-operator-resolve-rule
   /gallery/developer-guides/add-new-operator-rule-based
   /gallery/developer-guides/add-torch-operator-mapping
   /gallery/developer-guides/add-subgraph-rewrite-rule
   /gallery/developer-guides/add-new-operator-compute-definition
   /gallery/developer-guides/hidet-script-dynamic-kernel
   /gallery/developer-guides/add-new-operator-template-based

