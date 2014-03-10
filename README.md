PDF-via-ghost
=============

Applescript by Jürgen Schell to compress PDF using GhostScript

Use the GhosScripts Library and the ActionScripts Folder to compress the PDF in a very efficient manner: the quality almost stays the same and the weight is dramaticaly decreased.

=============
FOR MAC OS X User 
=============
The installation process takes time but you will save you much more time later, trust me.

1. Download the GhostScript Package for MAC OS X under [that link](http://www.linuxfoundation.org/collaborate/workgroups/openprinting/macosx/foomatic) and install it. Forget the Foomatic RIP. 
2. Download the "PDFConvert" script from this repo and put it on your desktop
3. In the spotlight search tool type "Terminal" and open a new window
4. In the terminal, type the following command :
```
mv ~/Desktop/PDFConvert.scpt /Library/Scripts/Folder\ Action\ Scripts/
```
5. Create a new folder on your desktop and name it "Compress_PDF"
6. Right Click on the "Compress_PDF" folder and then choose "Services -> Folder Actions Setup"
7. In the pop-up, select the "PDFconvert.scpt" script 
8. Select "Enable Folder Actions" and then quit (Command-Q)

Final step : 
1. To compress a PDF, simply drag and drop it inside the "Compress_PDF" folder
2. Wait a few seconds until your file disappear from the folder
3. Discover your compressed PDF in the "Compress_PDF/PDFs" subfolder
