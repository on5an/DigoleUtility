DigoleUtility
=============

Utility for Digole displays to upload fonts and start screen

To use:

1. Select communication method in DigoleUtility.ino
2. Modify array data in mydata.h with the desired font/start screen data. The digole can
   have up to 4 x 4KB fonts and 1 128x64 start screen.  A font can exceed 4KB but each font
   starts on a 4KB boundary (eg. a 6KB font uses 2 font "pages").
3. Comment out sections of code to upload as many or as few fonts as required
4. After each font download, test text is sent to the display.  The text can be modified as required
5. Once all data is uploaded, the program will stop.  Resetting the Spark will upload the data again!
