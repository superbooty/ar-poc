# ar-poc

To run the application

For testing locally with https using python http-server You'll need to create key and cert pem files and place them on the root folder. 
You can use OpenSSL to generate those be sure to name them key.pem and cert.pem.

In the root folder type <b>python server.py</b> (you'll need pythong version 2).  This will start the python local server

you can then navigate to your local IP address something like https://10.0.0.233:4443/marker-cam.html.  You'll do this on yuor mobile device.
Make sure your mobile wifi and your computer wifi (where you run this app) are on the same network.

on your computer go to the folder <b>barcodes</b> from your root and open up the <b>00.png</b> image.  this is your marker.

from your phone point the camera at the marker.  you should see an image floating on top of the marker.  when you put the image at the center of the phone it will show an overlay with product details.




