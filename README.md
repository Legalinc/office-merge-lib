# office-merge-lib
This library contains the CDE packages of libreOffice and Imagick.

This is used to convert doc, docx, png and jpeg files to PDF.

### Steps for convertion.

* Move the File which is to be converted to `cde-root/home/user/convert/` folder.
* Change the directory to `cde-root/home/user/`.
* For converting the image files, run the shell command `./convert.cde convert/imageFileName output/finalPDFName`.
* For converting the doc/docx files, run the shell command `./libreoffice.cde  --headless --invisible --convert-to pdf convert/docFileName --outdir output/`.
* The converted PDF files can be extracted from the `cde-root/home/user/output/` folder.
* Remove the files to prevent memmory growth.
