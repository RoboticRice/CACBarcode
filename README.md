# CACBarcode
Convert scanned CAC barcodes (PDF417 and Code39) into readable data.

The original Python Code that this repo was forked from and based off of was created by jkusner.

Included in this repo are two barcode scanner apps that convert photos of Code39 and PDF417 barcodes into their coresponding data from OnBarcode.com. That data is what these programs use to convert into readable and useful information. That being said, the two executables are NOT created by myself or jkusner, and belong to their respective owners. Please only use them for their intended purpose, as they are NOT included in the liscence that coveres the programs in this repository.
^One note: The example barcode doesn't want to work with the PDF417 scanner .exe, but my real CAC barcode does work, I don't know why, since I can scan the example using other methods...

These program only work on the assumption you have scanned the barcode in and have the value, these codes do NOT handle the scanning process. Since most scanners act like keyboard input, you can typically use these programs with a scanner, but results may varry.

For more information on CAC barcode structure, see (old) http://www.cac.mil/docs/DoD-ID-Bar-Code_SDK-Formats_v7-5-0_Sep2012.pdf (new) http://www.cac.mil/common-access-card/developer-resources/
