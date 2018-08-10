ML Kit for Firebase Quickstart
==============================

The ML Kit for Firebase Android Quickstart app demonstrates how to use the
various features of ML Kit to add machine learning to your application.

Introduction
------------

- [Read more about ML Kit for Firebase](https://firebase.google.com/docs/ml-kit/)
- [Exploring Firebase MLKit on Android: Barcode Scanning-Part Three](https://medium.com/google-developer-experts/exploring-firebase-mlkit-on-android-barcode-scanning-part-three-cc6f5921a108)

Getting Started
---------------

- [Add Firebase to your Android Project](https://firebase.google.com/docs/android/setup).
- Then add the firebase ML Kit dependency 
  Com.google.firebase:firebase-ml-vision:16.0.0
- Add meta tab in the manifeast for the 

```Java
<application>

  <meta-data
      android:name="com.google.firebase.ml.vision.DEPENDENCIES"
      android:value="barcode" />
  <!-- To use multiple models: android:value="barcode,model2,model3" -->
</application>

```
- Run the demo application on the device




