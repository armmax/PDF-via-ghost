PDF-via-ghost
=============

Applescript by Jürgen Schell to compress PDF using GhostScript. 

Description : Use the GhosScripts Library and the ActionScripts Folder to compress the PDF in a very efficient manner: the quality almost stays the same and the weight is dramaticaly decreased.


**FOR MAC OS X User**

The installation process takes time but you will save you much more time later, trust me.

1. Install homebrew from https://brew.sh/ or just open your Terminal and type 
```
/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
```
Follow the indication in the terminal.
2. Once Homebrew is installed, type the following command in your Terminal
```
brew install ghostscript
```
2. Download the "PDFconvert" script from this repo and put it on your desktop
3. In the spotlight search tool type "Terminal" and open a new window
4. In the terminal, type the following command :
```
sudo mv ~/Desktop/PDFconvert.scpt /Library/Scripts/Folder\ Action\ Scripts/
```
5. Enter your password
6. Create a new folder on your desktop and name it "Compress_PDF"
7. Right Click on the "Compress_PDF" folder and then choose "Services -> Folder Actions Setup"
8. In the pop-up, select the "PDFconvert.scpt" script 
9. Select "Enable Folder Actions" and then quit (Command-Q)

Final step : 
1. To compress a PDF, simply drag and drop it inside the "Compress_PDF" folder
2. Wait a few seconds until your file disappear from the folder
3. Discover your compressed PDF in the "Compress_PDF/PDFs" subfolder

*Note : I originally got it online but I can't manage to find it again and Jürgen Schell's website http://www.j-schell.de is down. 
So I decided to put it back online for everyone else to use.*
