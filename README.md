# Manager
![Quality Assurance](https://github.com/Cheon-App/planner/workflows/Quality%20Assurance/badge.svg) ![Flutter Build](https://github.com/Cheon-App/planner/workflows/Flutter%20Build/badge.svg)

## Getting Started
Create a Firebase project and add an Android or IOS app to it. You'll be given the option to download a google-services.json(Android) or GoogleService-Info.plist(IOS) file which should be placed in android/app/google-services.json or ios/Runner/GoogleService-Info.plist respectively.

If you're on Android you'll also need to [create a keystore](https://flutter.dev/docs/deployment/android#create-a-keystore) and [reference the keystore](https://flutter.dev/docs/deployment/android#create-a-keystore) via the file `android/key.properties`

## Running the app
### Android

#### Production build

`flutter run --release --flavor prod -t lib/main_prod.dart`

#### Development build

`flutter run --release --flavor dev`

### IOS

#### Production build

`flutter run --release -t lib/main_prod.dart`

#### Development build

`flutter run --release`

## Static analysis

`flutter analyze`

## Automated tests

`flutter test`
