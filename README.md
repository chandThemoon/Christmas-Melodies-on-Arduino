# Christmas-Melodies-on-Arduino
It plays melodies of three different kinds. Jingle Bells, We wish you a Merry Christmas, and Santa Claus is Coming.
If you would like to make similar melody player of christmas songs, given below are the instructions to follow.
1) Install the arduino IDE if you haven't already . Here is link to the page for downloading https://www.arduino.cc/en/Main/Software 
  -> You don't need zip, you can just install .exe by clicking on the Windows Installer, for Windows XP and up.
2) Install the NewCrystal Library
   -> Go to https://bitbucket.org/fmalpartida/new-liquidcrystal/downloads/, download Newliquidcrystal_1.3.5.zip.
   -> open your arduino, click sketch -> Include Library -> Add Zip, and then locate your file zip file.
3) Now you might have to make a minor change in your code, depending on the address of you I2C, mine is 0x27. You can determine 
   yours by clicking ->Tools -> serial monitor 
 4) Once you are done following the above steps, copy past  the code in your arduino.
 5) Make the connection by following the schematic
 6) Hit upload, press any switch on the board and then enjoy your melodies.
 
