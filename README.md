# MSAccessRep
A LAN POS system I created in MS Access

This repository is only used to demonstrate a program I've designed, and it is not to be used commercially by others.

The program consists of two parts:

  DATARevision.mdb - This is the back-end database, where the data is stored. It is used on the host computer.
  Revision2.mdb - This is the front-end database, which contains the UI and queries. It is used on both the host computer and the client computer.
  
The data has been modified as it can't be shared publicly.

Many features will not work as expected, as it is designed for two particular computers where it's installed. Notable non-working features include:

  - The front-end database's linked table references will have an incorrect path.
  - The receipts and invoices will not print, as workplace-specific printers are used.
  - The fonts will most likely display poorly, as the fonts are installed on the workplace computers.
  - There is no password protection on the programs.
  - There are no programs to back the database up.
  - Barcodes cannot be scanned in without the scanner.
  
Because its difficult to set up on a new computer, I have included another file:

  screenshots.pdf
  
This contains screenshots of the program's UI, which I've installed onto my local machine, however the fonts do not display properly as the font isn't installed.
