**What is QuickNII?**
======================= 
QuickNII is one of several tools developed by the NeSys laboratory at University of Oslo with the aim of facilitating brain atlas-based analysis and
integration of experimental data and knowledge about the human and rodent brain. 
  
QuickNII is a stand-alone application for user-guided affine
spatial registration (anchoring) of section images, typically high
resolution histological images, to 3D reference atlas space. A key
feature of the tool is its ability to generate user-defined cut planes
through the atlas templates that match the orientation of the cutting
plane of the 2D experimental images (atlas maps). The reference atlas is
transformed to match anatomical landmarks in the corresponding
experimental images. In this way, the spatial relationship between the
experimental image and the atlas is defined, without introducing
transformations in the original experimental images. Following anchoring
of a limited number of sections containing key landmarks,
transformations are propagated across the entire series of images. These
propagations must be validated and saved by the user for each section,
with application of fine positional adjustments as required. We
recommend the use of `VisuAlign <https://visualign.readthedocs.io/en/latest/>`_ to perform nonlinear adjustments after
the QuickNII registration for an optimal fit.

.. image:: 6bef45ee36424df69f030c687f030605/media/image1.png
   :width: 6.3in
   :height: 4.04916in 


.. image:: 6bef45ee36424df69f030c687f030605/media/image2.png
   :width: 6.30139in
   :height: 2.48678in
   

.. tip:: 
   **QuickNII and VisuAlign are part of the QUINT workflow**
   
   Visit `EBRAINS <https://ebrains.eu/service/quint/>`_ for more information about the QUINT workflow. Find full user documentation `here <https://quint-workflow.readthedocs.io>`_. 

**Which atlases are supported?**
-----------------------------

1. Allen Mouse Brain Atlas Common Coordinate Framework version 3 (2017) (CCFv3)
2. Waxholm Atlas of the Sprague Dawley rat, version 3 and 4 (WHS rat brain atlas)
3. Developmental Mouse Brain Atlas, version 2 (DeMBA)

**What is the output of QuickNII?**
---------------------------------
- A registration file (XML or JSON format) containing the coordinates of your regisered section images in atlas space. 
   Use the JSON format for continuing registration in VisuALign.
- Export of atlas maps (png format)
