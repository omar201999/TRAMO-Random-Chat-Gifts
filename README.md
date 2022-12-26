# TRAMO : Random Chat & Gifts

TRAMO is a mobile application developed using Flutter. It supports both Android and IOS.

TRAMO is a Live Streaming Chat with Different people over all the world

## Table of contents
- ### [main packages used](https://github.com/omar201999/TRAMO-Random-Chat-Gifts/blob/main/README.md#main-packages-used-1)
- ### [Folder structure](https://github.com/omar201999/TRAMO-Random-Chat-Gifts/blob/main/README.md#folder-structure-1)
- ### [Video](https://github.com/omar201999/TRAMO-Random-Chat-Giftsy/blob/main/README.md#Video-1)
- ### [Google Play Store](https://github.com/omar201999/TRAMO-Random-Chat-Gifts/blob/main/README.md#google-play-store-1)

## Main packages used
- [flutter_bloc](https://pub.dev/packages/flutter_bloc) as state management.
- [shared_preferences](https://pub.dev/packages/shared_preferences) to handle caching data.
- [flutter_offline](https://pub.dev/packages/flutter_offline) A tidy utility to handle offline/online connectivity.
- [flutter_screenutil](https://pub.dev/packages/flutter_screenutil) for adapting screen and font size.
- [cloud_firestore](https://pub.dev/packages/cloud_firestore) A Flutter plugin to use the Cloud Firestore API.
- [firebase_core ](https://pub.dev/packages/firebase_core) A Flutter plugin to use the Firebase Core API, which enables connecting to multiple Firebase apps.
- [firebase_auth ](https://pub.dev/packages/firebase_auth) Flutter plugin for Firebase Auth, enabling Android and iOS authentication using passwords, phone numbers and identity providers like Google, Facebook and Twitter.
- [firebase_storage ](https://pub.dev/packages/firebase_storage) Flutter plugin for Firebase Cloud Storage, a powerful, simple, and cost-effective object storage service for Android and iOS.
- [trust_location](https://pub.dev/packages/trust_location) A Flutter plugin for detecting mock location on Android device.
- [admob_flutter](https://pub.dev/packages/admob_flutter) Admob plugin that shows banner ads using native platform views.
- [pay](https://pub.dev/packages/pay) A plug-in to add support for payments on Flutter applications.
- [flutter_downloader](https://pub.dev/packages/flutter_downloader) Powerful plugin making it easy to download files.
- [path_provider](https://pub.dev/packages/path_provider) Flutter plugin for getting commonly used locations on host platform file systems, such as the temp and app data directories.
- [image_picker](https://pub.dev/packages/image_picker) Flutter plugin for selecting images from the Android and iOS image library, and taking new pictures with the camera.

## Folder structure
I have applied clean archeticture concept and here is the basic folder structure:

core folder structure that flutter provides:

```
tramo
├── android
├── assets
├── build
├── ios
├── lib
└── test
```


Here is the folder structure I have been using in this project:
```
lib
├── business_logic
├── constants
├── data
├── presentation
└── main.dart
```

### business_logic
This folder containes the business logic of the application specificly state management.

```
business_logic
├── global_cubit
└── home-layout_cubit
└── login_cubit
└── registration_cubit


```

### constants
This folder contains all constants strings and all constants files related to the application
```
constants
├── constant
├── ads_manager
├── localization
├── assets_image_manager


```

### data
This folder manages application data eg. retrieve data from the network, manage data cache
```
data
├── local
├── models

```

### presentation
This folder presents data to a screen and handle user interactions
```
presentation
├── router
├── screens
├── styles
└── views
└── widgets

```
## Video
https://www.youtube.com/watch?v=ogE4x1ReLTU

## Google Play Store

Soon
