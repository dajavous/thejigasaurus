# thejigasaurus.com

Briefly documents the changes made to Gallery v3.1.5 to suit migration from a Gallery2 website to provide a similar look and feel to users and the admins. Further work has been completed to test the migration of thejigasaurus.com to run on PHP 8.1, currently hosted on its test site at: https://dajavous.com/gallery315

Winmerge files describe the changes made to customise Gallery the Revival. Download and expand to view the WinMerge details of changes made to Gallery the Revival version of Gallery3 v3.1.5 to customise the website: https://www.thejigasaurus.com

A new version of the Winmerge files describes the further changes made to run thejigasaurus on its test site with PHP 8.1 using the Wide Wind theme.

The modules activated for the PHP 7.4 installation are shown in the pdfs, as well as the order the modules are loaded. 

The modules used can be found at http://codex.galleryproject.org/Gallery3:Modules and https://github.com/gallery/gallery3. 

The theme used for PHP 7.4 is Grey Dragon 4.0.2 which can be downloaded from https://blog.dragonsoft.us/gallery-3/, which also requires the greydragon module.

For completeness, all required files for the PHP 7.4 version are included here: Gallery v315 initial files for installation on a web server with PHP and mySQL, the guide to installing Gallery3, plus the modules and theme used. The modules and theme include all the customisations made to these files - further customisations were made to other installation files as documented in the Winmerge report. 

Two additional fields were added to the SQL items table:

Column	    Type	Null	Default

g2_summary	text	Yes	  NULL

tag_album	  text	Yes	  NULL

with more fields needed for the Gallery2 to Gallery3 migration as shown in the Gallery315 database structure file.
