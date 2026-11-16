# casio-BASIC-simplex-dual
Casio BASIC Simplex and Dual Linear Programming

This is a Casio BASIC implementation of the Simplex algorithm for linear programming optimization, as well as for Dual problems, intended for students' use and small size problems.
It is coded in Casio BASIC language, compatible with most of the "modern" casio programmable calculators.

It has been tested and run successfully on a Casio fx 9860 G SD (requires *.g1m files), released in the year 2005; presumably all similar and further programmable Casio calculators models should be able to run this script. It has also been tested successfully on a more recent Casio fx-CG50 (released in 2017) (works with *.g3m files).

Why CasioBASIC instead of Python?? -> Because the Python implementation on recent Casio calculators lack the libraries necessary to manipulate matrices and other mathematical objects, while they are fully supported on the older CasioBASIC language.





FILES:


SIMPL.g3m: simplex algorithm file ready to upload to your more recent Casio calculator (like a fx CG50) using usb or 3-pin connector. (FILE FORMAT g3m)

SIMPL.g1m: simplex algorithm file ready to upload to your older Casio calculator (like a fx 9860G) using usb or 3-pin connector. (FILE FORMAT g1m)

TBLCOLNM.g3m: name of the "tableau" column names for manual simplex algorithm calculation by hand.

SIMPL.txt: text of the script in the SIMPL.g3m file, for review.

DUALLP.g3m: dual linear programming file ready to upload to your Casio calculator using usb or 3-pin connector.



UPLOADING TO CALCULATOR:


To upload files to your calculator, check the user's manual. There are manuals provided here (Spanish and English) for the two Casio calculator models used for testing, most other Casio calculators will work in a similar or exact same way.
Casio fx 9860 SD: Chapters 2.8 and 8.
Casio fx CG50: Chapters 2.8 and 8.



EDITING AND COMPILING THE FILES:


Core Compiler: SourceCoder 3
**** https://www.cemetech.net/sc/ ****
Platform: A web-based development environment and compiler hosted on Cemetech (cemetech.net). View image.

Role: It acts as the bridge between standard text and Casio's proprietary binary format. It reads your text-based code (using ASCII macros for special symbols like _Disp_ for ◢, >= for ≥, and != for ≠) and compiles it into the exact machine code the calculator understands.

Export Formats: It allows you to select and download your compiled script directly as a .g3m file (specifically for the fx-CG50 series) or a .g1m file (for the older fx-9860G series).

The original platform to create and edit files for these calculators is the Casio FA-124 Software, which at the time of publishing this is unavailable online.


