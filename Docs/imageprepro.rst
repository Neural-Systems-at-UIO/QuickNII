**Image preprocessing requirements**
-------------------------------------
**Input data**
~~~~~~~~~~~~~~~~~~
| QuickNII supports standard web-compatible image formats, **24-bit PNG
  and JPEG**. Images can be loaded up to the resolution of 16 megapixels
  (e.g. 4000x4000 or 5000x3000 pixels), however QuickNII does not
  benefit from image resolutions exceeding the resolution of the monitor
  in use. For a standard FullHD or WUXGA display (1920x1080 or 1920x1200
  pixels) the useful image area is approximately 1500x1000 pixels, using
  a similar resolution ensures optimal image-loading
| performance.

.. Note:: 
  **When using *Filebuilder* to generate the image series descriptor file, a warning will appear if your files are too big (details below).**

Preprocessing of images with other software tools (e.g. Nutil Transform,
ImageMagick, Matlab scripts) or python scripts found in many open source
libraries (e.g. PIL)) is usually needed to fulfill these requirements
(converting to PNG or JPEG and downscaling to screen-like size), but
QuickNII allows storage of original image dimensions as part of its
series descriptor.

**File naming convention**
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
Serial section images should be assigned consecutive serial numbers,
preferably indicated by three-digit numbers at the end of the file
name\ **, e.g. Sample_ID_s001.png**

The section number should reflect the serial order and spacing of the
sections (e.g. s002, s006, s010 for every 4th section starting with
section 2).

.. Note:: 
  **If you plan to analyse your images with the **QUINT workflow**, both the image segmentation file from ilastik and the atlas map that correspond to a particular section must contain a unique ID that meets the file naming requirement described above. These unique IDs must also be present in the XML/JSON file containing the anchoring information: this happens automatically as long as the images that are anchored with QuickNII contain the unique IDs.**

Nutil Quantifier supports IDs in the format: sXXX.., with XXX..
representing the section number, as well as formats defined by regular
expressions.

Example: tg2345_MMSH_s001_segmentation.png (It is fine to include a
string of letters and numbers followed by the unique ID).

As Nutil Quantifier scans and detects the \_s part of the name, the file
name should not contain additional \_s. 
Example that would not work:
tg2345_MMSH_ss_s001.png

**Generate a XML descriptor file**
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

Collect the section images in a folder. The section sampling is defined by the serial numbers.

Remember to have a filenaming pattern that is consistent and with equal number of digits.

Use the small program “FileBuilder.bat” provided with QuickNII to
generate the XML descriptor file. A new window will open, and ask for the folder where your
images are located. Point to the correct folder, mark all image files (ctrl+A), and click ok.

.. image:: 6bef45ee36424df69f030c687f030605/media/image3.png
   :width: 2.88889in
   :height: 2.01888in

.. image:: 6bef45ee36424df69f030c687f030605/media/image4.png
   :width: 6.29306in
   :height: 0.57028in

Files will be reviewed, and an xml file will be generated when all
files passed (green OK). If the files are too big they will not pass and get a red warning. The
orange warning allows files to pass.

Click “Save xml”and give a name to your descriptor file. You can now
open the xml in QuickNII. If the section number is not recognized, you have the option to just
number the images in filebuilder.

**NOTE! The xml descriptor file must be located in the same folder as
the small png or jpeg images for QuickNII.**



