.. _torch_quick_start:

Get Started with PyTorch Neuron
===============================

This page provide links that will assist you to quickly start with :ref:`pytorch-neuronx-main` for both Inference and Training.

.. note::
  Below instructions are for Amazon Linux 2, if you looking for complete setup instructions for different platforms, please :ref:`Check Here. <setup-guide-index>`


.. dropdown::  Launch the Instance
    :class-title: sphinx-design-class-title-small
    :class-body: sphinx-design-class-body-small
    :animate: fade-in

    .. include:: /general/setup/install-templates/launch-instance.txt

.. dropdown::  Install Drivers and Tools
    :class-title: sphinx-design-class-title-small
    :class-body: sphinx-design-class-body-small
    :animate: fade-in

    .. include :: /src/helperscripts/installationScripts/python_instructions.txt
        :start-line: 2
        :end-line: 3

.. tab-set::

   .. tab-item:: torch-neuronx (``Trn1, Inf2``)

        .. include:: tab-inference-torch-neuronx.txt


   .. tab-item:: torch-neuron (``Inf1``)

        .. include:: tab-inference-torch-neuron.txt