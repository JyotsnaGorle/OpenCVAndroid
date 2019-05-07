# OpenCVAndroid
detect the frontal face of a person in the camera
=============================================================================
The steps to include OpenCV as a native android library: inspired from the readme in this project and the sample project linked in.
https://github.com/floe/opencv-android/tree/master/manager

1. download the Android OpenCV library from github - the latest version
2. create an android project - empty activity preferably
3. Import module from source - and use the java folder inside sdk/java. This folder conatains all the java precompiled versions of the C++ openCV library files.
4. Update the gradle file with the build versions since the OpenCV downloaded version is not updated for the new android versions.
5. Add the openCV imported module as a dependency to your project.
6. Adding the Native libraries - The Jnilibs folder - The java native libraries : 
I got confused with the exisiting jnilibs folder in the samples folder. But that is not the one we need. The sdk/native/libs folder has to be copied into app/src/main and renamed to jniLibs folder.

tip from : https://android.jlelse.eu/a-beginners-guide-to-setting-up-opencv-android-library-on-android-studio-19794e220f3c
