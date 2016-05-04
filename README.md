# obsSlide
A simple slide show for OBS Studio

To add images open the obsslide.html file in notepad, Notpead++ or any othe text editor.
Replace each line with the filename of an image you want in your slideshow.
For web images the format is http://mysite.com/folder/image.jpg
For local images the format is http://absolute/c:/folder/image.jpg

Save the file an make sure if you are using notepad to make sure the fle 
is saved as obsslide.html and not obsslide.html.txt by changing "Save as type" to All Files (*.*).

To change the duration each image is on screen edit the scripts/obsslide.js and update the druation variable.

var duration = 20; // duration in seconds

Change to 

var duration = 10; //duration in seconds 

for a ten second fade.

This code is unapologetically modified from the following pen:

http://codepen.io/Archonius/pen/efEAD