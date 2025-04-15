
**Installation and citation**
-----------------------------
**System requirements**
~~~~~~~~~~~~~~~~~~~~~~~~
Microsoft Windows: 64-bit operating system, Windows 7 or later

Apple macOS: OS X 10.9 (Mavericks) or later

3 gigabytes RAM

Display resolution minimum 1440 pixels wide and minimum 650 pixels high.

**Technical information**

QuickNII consists of two co-located executable components implemented in
two programming languages for historical reasons. The GUI component is
implemented in MXML+ActionScript (runs on Adobe Integrated Runtime,
which is bundled as "captive runtime", requiring no installation). A
slicer service running in the background is implemented in Java (and has
a bundled JRE requiring no installation). The two components communicate
via standard output and local TCP connections (using the loopback
interface).

**Download:**

Download of the software is from Nitrc.org
Link: https://www.nitrc.org/projects/quicknii/ 

Unzipp the QuickNII folder at your desired location.

**Conditions of use**
~~~~~~~~~~~~~~~~~~~~~~

**Licence:** 

Creative Commons Attribution-NonCommercial-ShareAlike 4.0
International for the main component. Source code: MIT License.


**Citation of the tool:**

-RRID on SciCrunch: (QuickNII, RRID:SCR_016854)

-Puchades MA, Csucs G, Ledergerber D, Leergaard TB, Bjaalie JG (2019)
  Spatial registration of serial microscopic brain images to
  three-dimensional reference atlases with the QuickNII tool. PLOS ONE
  14(5): e0216796. https://doi.org/10.1371/journal.pone.0216796
   
**Cite funding**
 
QuickNII is developed at the Neural Systems Laboratory, Institute of
Basic Medical Sciences,University of Oslo (Norway), with funding from the European Union’s
Horizon 2020 Framework Programme for Research and Innovation under the
Framework Partnership Agreement No. 650003 (HBP FPA) and the European Union’s Horizon Europe Programme for Research Infrastructures Grant Agreement No. 101147319 (EBRAINS 2.0).

**Citation of the atlases embedded in the tool:**

QuickNII has the following reference atlases integrated and validated:

+--------------------------------------------------+
|Allen Mouse Brain Atlas version 3 2015            |
|                                                  |
|Allen Mouse Brain Atlas version 3 2017            |
|                                                  |
|Kim-UnifiedMouse-v1                               |
|                                                  |
|Waxholm Space Atlas of the Sprague Dawley rat v2  |
|                                                  |
|Waxholm Space Atlas of the Sprague Dawley rat v3  |
|                                                  |
|Waxholm Space Atlas of the Sprague Dawley rat v4  |
|                                                  |
|Developmental Mouse Brain Atlases for P4-P56      |
+--------------------------------------------------+    

**How to cite:** 

**Allen Mouse Brain Atlas Common Coordinate Framework version 3** 

* Wang Q, Ding SL, Li Y, Royall J, Feng D, Lesnar P, Graddis N, Naeemi M, Facer B, Ho A, Dolbeare T, Blanchard B, Dee N, Wakeman W, Hirokawa KE, Szafer A, Sunkin SM, Oh SW, Bernard A, Phillips JW, Hawrylycz M, Koch C, Zeng H, Harris JA, Ng L. The Allen Mouse Brain Common Coordinate Framework: A 3D Reference Atlas. Cell. 2020 May 14;181(4):936-953.e20. doi: 10.1016/j.cell.2020.04.007. Epub 2020 May 7. 

See the `citation policy <https://alleninstitute.org/citation-policy/>`_ from the Allen Intitute for more information.

**Kim-UnifiedMouse-v1**

* Chon et al. 2019, Nature Communications 10:5067. https://doi.org/10.1038/s41467-019-13057-w

**Waxholm Atlas of the Sprague Dawley Rat**

Please refer to the atlas using RRID:SCR_017124, specify the atlas version(s) used, and cite the most recent publication:

•	Version 4: Kleven, H., Bjerke, I.E., Clascá, F. et al. Waxholm Space atlas of the rat brain: a 3D atlas supporting data analysis and integration. Nat Methods 20, 1822–1829 (2023). DOI: 10.1038/s41592-023-02034-3

If your work makes use of previous atlas versions, or brain region descriptions detailed in earlier publications, please also cite the corresponding publication:

•	Version 1: Papp EA, Leergaard TB, Calabrese E, Johnson GA, Bjaalie JG (2014) Waxholm Space atlas of the Sprague Dawley rat brain. NeuroImage 97, 374-386. DOI: 10.1016/j.neuroimage.2014.04.001
•	Version 2: Kjonigsen LJ, Lillehaug S, Bjaalie JG, Witter MP, Leergaard TB (2015) Waxholm Space atlas of the rat brain hippocampal region: Three-dimensional delineations based on magnetic resonance and diffusion tensor imaging. NeuroImage 108, 441-449. DOI: 10.1016/j.neuroimage.2014.12.080
•	Version 3: Osen KK, Imad J, Wennberg AE, Papp EA, Leergaard TB (2019) Waxholm Space atlas of the rat brain auditory system: Three-dimensional delineations based on structural and diffusion tensor magnetic resonance imaging. NeuroImage 199, 38-56. DOI: 10.1016/j.neuroimage.2019.05.016 

**Developmental Mouse Brain Atlases for ages P4-P56**

We encourage researchers who use DeMBA to cite both the dataset and publication presenting DeMBA, and to specify the age of any template(s) used and the version of any segmentation(s) used.

•	Article: Carey et al. (2024) DeMBA: a developmental atlas for navigating the mouse brain in space and time. bioRxiv. https://doi.org/10.1101/2024.06.14.598876
•	Dataset: Carey et al. (2024). Developmental mouse brain atlas (DeMBA) with continuous coverage of postnatal day 4 to 56 (v1) [Data set]. EBRAINS. https://doi.org/10.25493/PWDG-536
•	Allen CCFv3 segmentations: Wang et al. (2020). The Allen Mouse Brain Common Coordinate Framework: A 3D Reference Atlas. Cell. https://doi.org/10.1016/j.cell.2020.04.007 
•	KimLabDev segmentations: Kronman et al. (2024). Developmental mouse brain common coordinate framework. Nature Communications. https://doi.org/10.1038/s41467-024-53254-w

**In addition, versions have been compiled by other researchers**

TBA




**Release notes**
~~~~~~~~~~~~~~~~~~
* Version 2.2 (2019-05-28) This release includes several reference atlaseslisted above.
Linux support was added in July 2020. 

* Version 2.2preview (2019-04-02) Series descriptor builder recognizes multiple numbering variants in filenames (numbers at fixed character position from either end of names, and sequence indicator \_s prefixanywhere) 
Coordinate transformation to/from Allen CCFv3 added to Mouse package.

* Version 2.1 (2018-12-05) First stable version



