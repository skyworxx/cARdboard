# cARdboard AR
# Created by Mark Schramm
# www.Mark-Schramm.com

cARdboard AR - Open Source AR headset

[title image](http://i.imgur.com/oqWcStS.jpg)


cARdboard AR is an open source AR headset in the style of Google's Cardboard.

It requires two fresnel lenses with 3 or 4 times magnification, ideally in the size of 75x75mm as well as one mirror (150x75mm) and one tinted acrylic sheet (150x75mm).

The idea behind this cheap AR headset is that the phone camera still faces forward and can be used for tracking. It should be compatible with ARKit and Vuforia and any other phone camera based tracking, but because of the offset it won't be directly compatible with the standard examples. Also very few standard examples render stereoscopic.

For Vuforia, you can read more about rendering stereoscopic here:
https://library.vuforia.com/articles/Training/Vuforia-for-Digital-Eyewear
Follow the informationr regarding Video See-Through and just disable video background rendering.

ARKit is in beta and I found this working example:
https://github.com/andrewnakas/ARKit-Cardboard-VR

Please note that in almost every case, you have to modify the virtual camera FOV to align with your headset.

