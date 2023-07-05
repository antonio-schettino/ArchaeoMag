# ArchaeoMag
Computer program for the modelling of magnetic anomalies in archaeological research
Welcome to ArchaeoMag 3.3.2 for Windows 7-8-10

This README file contains important information about ArchaeoMag
For technical information, please contact the software authors by sending an
e-mail to:

antonio.schettino@unicam.it
annalisa.ghezzi@unicam.it

If you use ArchaeoMag for research, please cite the following paper:

Schettino, A. & Ghezzi, A., 2020. Forward modelling of magnetic anomalies in archaeological geophysics: A new software tool, Bollettino di Geofisica Teorica ed Applicata, 61(1), 89-102, DOI 10.4430/bgta0296.


1. Installation
   ------------

ArchaeoMag does not require an installation procedure. Simply run an instance of the program from its main folder.
However, for a correct operational environment you must meet the following minimum requirements:

- 16 GB RAM (32 GB recommended)
- An Intel Core i7 processor
- Windows 7, Windows 8, or Windows 10
- About 21 MB of free hard disk space
- A large color display. It is recommended to set the resolution to 1280×960 or higher;
- A color printer
- A mouse


2. File List
   ------------

- ArchaeoMagan.exe:		ArchaeoMag binary
- License.txt:			License File
- Readme.txt:			This file
- ArchaeoMag.pdf			ArchaeoMag Help
- ArchaeoMag.res			Resources file
- borlndmm.dll			Dynamic library
- cc32270mt.dll			Dynamic library
- cc32270.dll			Dynamic library
- cc32c270.dll			Dynamic library
- cc32c270mt.dll			Dynamic library
- vcl270.bpl			Dependency Package
- rtl270.bpl			Dependency Package
- vclimg250.bpl			Dependency Package
- vcl270.de			Dependency Package Language Resource
- vcl270.jp			Dependency Package Language Resource
- vcl270.fr			Dependency Package Language Resource
- rtl270.de			Dependency Package Language Resource
- rtl270.jp				Dependency Package Language Resource
- rtl270.fr				Dependency Package Language Resource
- vclimg270.de			Dependency Package Language Resource
- vclimg270.jp			Dependency Package Language Resource
- vclimg270.fr			Dependency Package Language Resource
- Tests				Folder containing some examples


3. Examples
   ------------

Three examples and two tutorials are included in this distribution. They work only if the main folder is D:\Archaeomag\Tests\. Otherwise,
you should open the project files: .\Tests\Test_1.aprj, .\Tests\Test_2.aprj, and .\Tests\Test_3.aprj, through a text editor (e.g., Notepad) and substitute all the occurrences of
strings "D:\Archaeomag\Tests\" by the correct path. In addition, two tutorials from Bruce Bevan (kr2012s.pdf and pp3.pdf) and associated material can be found in the Tests folder.
Finally, this distribution includes four examples of colour palettes that can be used to visualize magnetic anomaly grids. They are placed in the Resources folder.



4. What is new in version 2.0 March 2018)
   -----------------------------------------

This version allows to load an uncertainty grid, which can be used to stop the forward modelling procedure when the current error falls below the uncertainty. In this instance, magnetic profiles will include
a grey area indicating the level of uncertainty along the profile. You can consider that the fit is acceptable when the error curve is entirely within the grey area.

Another important feature of this version is the new fast algorithm of magnetic anomaly computation. Now the program will update the anomaly field using a smart algorithm that makes changes only in the areas
surrounding modified objects.


5. What is new in version 2.1 May 2018)
   -----------------------------------------

This version allows to lock a single feature and the unlocking of all the loaded features. This is useful when
you have overlapping objects at different depths, because it allows to disable the selection of an object


6. What is new in version 2.2 (January 2019)
   -----------------------------------------

This version allows to set the rotation angle that the programs applies when you want to rotate an object about its centroid. It also allows to define cylindrical features. A small bug in the creation of profiles has been fixed.

7. What is new in version 2.3 (February 2019)
   -----------------------------------------

This new version allows to set the background (average) anomaly of the calculated anomalous field to a specific value (default is zero)


8. What is new in version 2.4 (April 2019)
   -----------------------------------------

This new version fixes a bug in the resent of the calculated anomaly field in particular conditions (creation and immediate deletion of an object). It also allows to create grids of calculated anomalies

9. What is new in version 2.5 (May 2019)
   -----------------------------------------

This new version fixes some bugs in the management of the background anomaly

10. What is new in version 2.6 (February 2020)
   -----------------------------------------

This new version allows to import features identified on GPR amplitude maps and fixes some bugs in the management of projects.

11. What is new in version 2.6 (March 2020)
   -----------------------------------------

This new version allows to assign a display style to features (pen color, style, and size)

12. What is new in version 3.0 (August 2020)
   -----------------------------------------

The program now allows to model also vertical gradient and fluxgate data. Some minor bugs have been fixed.

13. What is new in version 3.1 (September 2020)
   -----------------------------------------

This version fixes a major bug in the calculation of gradient data. Total field anomalies and pseudo-gradients are calculated as in the previous version.


14. What is new in version 3.11 (September 2020)
   -----------------------------------------

This version fixes a major bug in the update of dipole anomalies.

15. What is new in version 3.3 (October 2020)

Several bugs have been fixed. New projects have default pen styles. It is now possible to import xyz magnetic data files, perform automatic gridding, and export in flt format. Block navigation capability and new user interface 
features have been introduced.

16. What is new in version 3.3.1 (November 2020)

A bug in the repeated opening of projects has been fixed.

17. What is new in version 3.3.2 (December 2020)

A bug has been fixed, which prevented creation of projects in absence of anomaly grids
