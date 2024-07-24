[![lego project](https://img.shields.io/badge/powered%20by-lego-blue?logo=github)](https://github.com/melodysdreamj/lego)
[![pub package](https://img.shields.io/pub/v/firebase_crashlytics_lego.svg)](https://pub.dartlang.org/packages/firebase_crashlytics_lego)

# firebase_crashlytics_lego

##  Installation
1. open terminal in the lego project root directory, enter the following command for install cli.
   and create a new lego project if you don't have one.
```bash
flutter pub global activate lego_cli
lego create
```
2. in terminal, enter the following command for add lego to project.
```bash
lego add firebase_crashlytics_lego
```

3. (optional)upload debug symbols to firebase console. [link](https://firebase.google.com/docs/crashlytics/get-started?platform=flutter#add-sdk)
```bash
firebase crashlytics:symbols:upload --app=FIREBASE_APP_ID PATH/TO/symbols
```