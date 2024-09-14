# affirmations-android-app


Below is a list of density qualifiers on Android:  

mdpi - resources for medium-density screens (~160 dpi)  
hdpi - resources for high-density screens (~240 dpi)  
xhdpi - resources for extra-high-density screens (~320 dpi)  
xxhdpi - resources for extra-extra-high-density screens (~480 dpi)  
xxxhdpi - resources for extra-extra-extra-high-density screens (~640 dpi)  
nodpi - resources that are not meant to be scaled, regardless of the screen's pixel density  
anydpi - resources that scale to any density  


##
Summary  
Place app icon files in the mipmap resource directories.  
Provide different versions of an app icon bitmap image in each density bucket (mdpi, hdpi, xhdpi, xxhdpi, xxxhdpi) for backwards compatibility with older versions of Android.  
Add resource qualifiers onto resource directories to specify resources that should be used on devices with a certain configuration (v24 or v26).  
Vector drawables are Android's implementation of vector graphics. They are defined in XML as a set of points, lines, and curves, along with associated color information. Vector drawables can be scaled for any density without loss of quality.  
Adaptive icons were introduced to the Android platform in API 26. They are made up of a foreground and background layer that follow specific requirements, so that your app icon looks high-quality on a range of devices with different OEM masks.  
Use Image Asset Studio in Android Studio to create legacy and adaptive icons for your app.  
