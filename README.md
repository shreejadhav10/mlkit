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
- Add meta tab in the manifeast to download the dependency at the time fo installation

```Java
<application>

  <meta-data
      android:name="com.google.firebase.ml.vision.DEPENDENCIES"
      android:value="barcode" />
  <!-- To use multiple models: android:value="barcode,model2,model3" -->
</application>

```
- Run the demo application on the device.
- Supported barcode list
  * Code 128 (FORMAT_CODE_128)

  * Code 39 (FORMAT_CODE_39)

  * Code 93 (FORMAT_CODE_93)

  * Codabar (FORMAT_CODABAR)

  * EAN-13 (FORMAT_EAN_13)

  * EAN-8 (FORMAT_EAN_8)

  * ITF (FORMAT_ITF)
 
  * UPC-A (FORMAT_UPC_A)

  * UPC-E (FORMAT_UPC_E)

  * QR Code (FORMAT_QR_CODE)

  * PDF417 (FORMAT_PDF417)

  * Aztec (FORMAT_AZTEC)

  * Data Matrix (FORMAT_DATA_MATRIX)




