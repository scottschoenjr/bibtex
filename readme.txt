BibTeX Formatting with BibTool

BibTool (http://www.gerd-neugebauer.de/software/TeX/BibTool/en/) was compiled with gcc on cygwin (https://www.cygwin.com/).
The exectuable bibtool.exe can be run on cygwin bash or a Windows terminal as far as I can tell.

The batch file formatBibtex.bat is a shortcut to remove fields from the input BibTeX file an save a "clean" version.
Edit this script to change the name of the input and output files to handle.

Set fields to be removed in the removeFields.rsc file. See the BibTool documentation for more details.