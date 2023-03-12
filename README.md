# flutter_auth

A new Flutter project.

## Getting Started

## Commands
dart pub global activate flutterfire_cli

Add this path to your environment
# 👇️ replace YOUR_USER with your actual username
#    C:\Users\YOUR_USER\AppData\Local\Pub\Cache\bin

npm install -g firebase-tools
firebase login
flutterfire config \ 
--project=auth-test-d55bc \ 
--out=lib/firebase_options.dart \ 
--ios-bundle-id=com.example.flutter_auth \ 
--macos-bundle-id=com.example.flutter_auth \ 
--android-app-id=com.example.flutter_auth

set the minSDK to 21 in gradle file.

cd ios
pod install
open Podfile and uncomment platform :ios, '11.0'
pod install

add multiDexEnabled true to gradle file defaultConfig

https://stackoverflow.com/questions/74226250/error-member-not-found-firebaseappplatform-verifyextends

add this to pubspec.yaml file if you face error
dependency_overrides:
  firebase_core_platform_interface: 4.5.1