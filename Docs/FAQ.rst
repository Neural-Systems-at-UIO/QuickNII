**FAQ**
--------------------------------

(1) I am using QuickNII to register my 2D coronal brain images with retrograde tracing. I completed all required steps through the filebuilder, but when I input my file to be registered the images does not appear, only the reference you have appears. Can you help me with this?

--> Please place the xml file in the same folder as the jpeg images, this usually solves this issue.
You can read about it here: https://quicknii.readthedocs.io/en/latest/imageprepro.html#generate-a-xml-descriptor-file

(2) I have an error with the QuickNII filebuilder that just shows a black screen and shuts down.

--> This can happen if you have spaces in the path where the QuickNII software is located. For Windows 10 users, the filebuilder can be modified and it is described here: https://www.nitrc.org/plugins/mwiki/index.php/quicknii:MainPage

(3) QuickNII filebuilder does not list my images although the size is ok.

--> The filename pattern should be consistent and the section numbers should have the same number of digits (see naming convention).

(4) How can I refine my QuickNII registration?

--> Please us VisuAlign https://visualign.readthedocs.io/en/latest/.

(5) Where can I find information about the coordinates of my images? 

--> Information can be found in this guide under "Coordinates"

(6) How can I try QuickNII with my own atlas?

--> Documentation of the cutlas file format is available here: https://www.nitrc.org/plugins/mwiki/index.php?title=quicknii:Cutlas_file_format
