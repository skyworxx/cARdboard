# cARdboard AR
# Created by Mark Schramm
# www.Mark-Schramm.com

cARdboard AR - Open Source AR headset

![title image](http://i.imgur.com/oqWcStS.jpg)


# cARdboard AR is an open source AR headset in the style of Google's Cardboard.

![gif](cARdboardAR3.gif?raw=true "Title")

It requires two fresnel lenses with 3 or 4 times magnification, ideally in the size of 75x75mm as well as one mirror (150x75mm) and one tinted acrylic sheet (150x75mm).

The idea behind this cheap AR headset is that the phone camera still faces forward and can be used for tracking. It should be compatible with ARKit and Vuforia and any other phone camera based tracking, but because of the offset it won't be directly compatible with the standard examples. Also very few standard examples render stereoscopic. See "Software" for mroe information.



# Material Required
- 1 large sheet of Cardboard. Other than scrap cardboard, the art supply or crafts store is a good place to find large sheets of sturdy cardboard.
- 150x75mm tinted acrylic sheet. You can get them at your local hardware store. The darker the tint, the better, but it has to be see through
- 150x75mm mirror. You can find 75x75mm mirrors at your art supply or craft store easily.
- 2 75x75mm fresnel lenses with 3 or 4 times magnification. These are hard to find. I used credit card size magnifiers from the office supply store. They are not tall enough, but it'll work.
- Glue (for the tabs). You can also cut off the tabs and just use sticky tape to hold it together.


# How To Build cARdboard

![template](http://i.imgur.com/NdNckSA.png)

1. Print out the template (in one or several parts), transfer it onto a piece thin piece of cardboard and cut out the shape.  Alternately, you could lasercut the template directly out of cardboard.

2. Carve the lines (makes folding easier)

3. Attach the lenses, mirrors and the acrylic sheet.

4. Fold the tabs and the body. Here is a short video demonstratign the folding (older prototype shown): https://photos.app.goo.gl/QYjz6L6NNGe5HdWH2

6. Glue all tabs to the body



# Software
For Vuforia, you can read more about rendering stereoscopic here:
https://library.vuforia.com/articles/Training/Vuforia-for-Digital-Eyewear
Follow the informationr regarding Video See-Through and just disable video background rendering.

ARKit is in beta and I found this working example:
https://github.com/andrewnakas/ARKit-Cardboard-VR

Please note that in almost every case, you have to modify the virtual camera FOV to align with your headset.
