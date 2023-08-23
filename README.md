# E-school

### Note: This app is not fully developed, it still has a lot of bugs and I'm still working on it (For now all the login data for parent, teacher and student are added manually in firestore)

### [Web Portal](https://github.com/ketanchoyal/Our-E-School-Web-Portal) is under development.

#### There are backend firebase functions too written in Typescript for some automation and some functions to make them work with web based project(future proof)

Our E School is the app build for iOS and Android using Flutter.

It uses Firebase FireStore as Database and Firebase Storage.

## FeatureS

|  UI  | Logic | Feature |
| ------ | ------ | ------|
| ✔ | ✔ | Teacher Login
| ✔ | ✔ | Student Login
| ✔ | ✔ | Parent Login
| ✔ | ✔ | Multiple Child Profile View
| ✔ | ✔ | Chat between teacher and parent
| ✔ | ✔ | Intro Screens.
| ✔ | ✔ | Post photo or notice on Standard post section(Only Teacher)
| ✔ | ✔ | Post photo or notice on global post section(Only Teacher)
| ✔ | ✔ | Dark Mode
| ✔ | ✔ | Profile Setup
| ✔ | ✔ | Forget Password
| ✔ |  | TimeTable
### and many more......

## Screenshots

![Screenshot_1](https://github.com/youssef0405/E-school/assets/78429621/c5def387-4460-46e6-9f66-63b1defd613c)

Database structure snapshot are [here](https://github.com/ketanchoyal/Academic-Connect/raw/master/DB%20Structure).

A full database documentation will be created soon..

## Server.dart 

You need to create this and put in /core/ folder. \
This File is necessary in order to make Cloud Functions work.

```dart
class Server {
  static String baseUrl =
      YOUR-CLOUD-FUNCTION-URL;
  static String webApi = 'webApi/';
  static String profileUpdate = 'profileupdate';
  static String getProfileData = 'userdata';
  static String postAnnouncement = 'postAnnouncement';
  static String addAssignment = 'addAssignment';
}
```

## Getting Started

This project is a starting point for a Flutter application.

A few resources to get you started if this is your first Flutter project:

- [Lab: Write your first Flutter app](https://flutter.dev/docs/get-started/codelab)
- [Cookbook: Useful Flutter samples](https://flutter.dev/docs/cookbook)

For help getting started with Flutter, view our 
[online documentation](https://flutter.dev/docs), which offers tutorials, 
samples, guidance on mobile development, and a full API reference.
