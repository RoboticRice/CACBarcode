# CACBarcode for Spreadsheets
Convert scanned CAC barcodes (PDF417 and Code39) into readable data.

The code in this directory is optimized for spreadsheet style programs, such as Excel, OpenOffice Spreadsheets, and Google Drive's Spreadsheets.

To use the spreadsheets, be shure to include the page titled "Base32 Alphabet" as that is used to decode the values for EDIPI, PDI, and all the dates. If you do not need any of those fields, then the Base32 Alphabet is optional.

To use the spreadsheets code for a unit rollcall/roster (which is why I made this in the first place, my unit was reading off names and it was taking forever!), download the Rollcall file of the programtype you use (.xls Excel, .oxs Open Office). Then, when I create the document, finish the document, and then add a tutorial, you can follow the steps that don't yet exist.

The original Python Code that this repo was forked from and based off of was created by jkusner.

These program only work on the assumption you have scanned the barcode in and have the value, these codes do NOT handle the scanning process. Since most scanners act like keyboard input, you can typically use these programs with a scanner, but results may varry.

For more information on CAC barcode structure, see http://www.cac.mil/docs/DoD-ID-Bar-Code_SDK-Formats_v7-5-0_Sep2012.pdf
