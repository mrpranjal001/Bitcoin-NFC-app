# Bitcoin-NFC-app
Bitcoin crypto app
This is a NFC card reader app that displays contents from the scanned card. 
cryptocurrency bitcoin transection
BlockCypher Api  (https://www.blockcypher.com/) 

Package:

{
  "name": "tavonnipay",
  "version": "0.0.1",
  "author": "Ionic Framework",
  "homepage": "https://ionicframework.com/",
  "scripts": {
    "ng": "ng",
    "start": "ng serve",
    "build": "ng build",
    "test": "ng test",
    "lint": "ng lint",
    "e2e": "ng e2e",
    "postinstall": "npx jetify"
  },
  "private": true,
  "dependencies": {
    "@angular/common": "~10.0.0",
    "@angular/core": "~10.0.0",
    "@angular/forms": "~10.0.0",
    "@angular/platform-browser": "~10.0.0",
    "@angular/platform-browser-dynamic": "~10.0.0",
    "@angular/router": "~10.0.0",
    "@ionic-native/barcode-scanner": "^5.31.1",
    "@ionic-native/clipboard": "^5.33.1",
    "@ionic-native/core": "^5.0.0",
    "@ionic-native/http": "^5.30.0",
    "@ionic-native/in-app-browser": "^5.30.0",
    "@ionic-native/native-storage": "^5.32.1",
    "@ionic-native/qr-scanner": "^5.31.1",
    "@ionic-native/splash-screen": "^5.0.0",
    "@ionic-native/status-bar": "^5.0.0",
    "@ionic/angular": "^5.0.0",
    "@rxweb/reactive-form-validators": "^2.1.2",
    "angularx-qrcode": "^10.0.12",
    "bech32": "^1.1.4",
    "bigi": "^1.4.2",
    "bitcoinjs-lib": "^4.0.5",
    "browserfy": "^1.0.0",
    "browserify": "^17.0.0",
    "buffer": "^6.0.3",
    "crypto": "^1.0.1",
    "opennode": "^1.2.1",
    "readable-stream": "^3.6.0",
    "rxjs": "^6.5.5",
    "stream": "0.0.2",
    "tslib": "^2.0.0",
    "uglify-es": "^3.3.9",
    "unorm": "^1.6.0",
    "xcode": "^3.0.1",
    "zone.js": "~0.10.3"
  },
  "devDependencies": {
    "@angular-devkit/build-angular": "~0.1000.0",
    "@angular/cli": "~10.0.5",
    "@angular/compiler": "~10.0.0",
    "@angular/compiler-cli": "~10.0.0",
    "@angular/language-service": "~10.0.0",
    "@ionic/angular-toolkit": "^2.3.0",
    "@ionic/lab": "3.2.10",
    "@types/jasmine": "~3.5.0",
    "@types/jasminewd2": "~2.0.3",
    "@types/node": "^12.20.15",
    "codelyzer": "^6.0.0",
    "cordova-android": "^9.0.0",
    "cordova-clipboard": "^1.3.0",
    "cordova-ios": "^6.2.0",
    "cordova-plugin-add-swift-support": "^2.0.2",
    "cordova-plugin-advanced-http": "^3.1.0",
    "cordova-plugin-androidx": "^3.0.0",
    "cordova-plugin-androidx-adapter": "^1.1.3",
    "cordova-plugin-device": "^2.0.2",
    "cordova-plugin-file": "^6.0.2",
    "cordova-plugin-inappbrowser": "^4.1.0",
    "cordova-plugin-ionic": "^5.4.7",
    "cordova-plugin-ionic-keyboard": "^2.2.0",
    "cordova-plugin-ionic-webview": "^4.2.1",
    "cordova-plugin-nativestorage": "^2.3.2",
    "cordova-plugin-splashscreen": "^5.0.2",
    "cordova-plugin-statusbar": "^2.4.2",
    "cordova-plugin-whitelist": "^1.3.3",
    "jasmine-core": "~3.5.0",
    "jasmine-spec-reporter": "~5.0.0",
    "jetifier": "^1.6.6",
    "karma": "~5.0.0",
    "karma-chrome-launcher": "~3.1.0",
    "karma-coverage-istanbul-reporter": "~3.0.2",
    "karma-jasmine": "~3.3.0",
    "karma-jasmine-html-reporter": "^1.5.0",
    "phonegap-plugin-barcodescanner": "^8.1.0",
    "protractor": "~7.0.0",
    "tangem-sdk": "^0.4.0",
    "ts-node": "~8.3.0",
    "tslint": "~6.1.0",
    "typescript": "~3.9.5"
  },
  "browser": {
    "crypto": false
  },
  "description": "An Ionic project",
  "cordova": {
    "plugins": {
      "cordova-plugin-whitelist": {},
      "cordova-plugin-statusbar": {},
      "cordova-plugin-device": {},
      "cordova-plugin-splashscreen": {},
      "cordova-plugin-ionic-webview": {
        "ANDROID_SUPPORT_ANNOTATIONS_VERSION": "27.+"
      },
      "cordova-plugin-ionic-keyboard": {},
      "cordova-plugin-androidx-adapter": {},
      "cordova-plugin-advanced-http": {},
      "cordova-clipboard": {},
      "cordova-plugin-inappbrowser": {},
      "cordova-plugin-ionic": {
        "APP_ID": "7c7d6cd1",
        "CHANNEL_NAME": "Production",
        "UPDATE_METHOD": "auto",
        "MAX_STORE": "2",
        "MIN_BACKGROUND_DURATION": "30",
        "UPDATE_API": "https://api.ionicjs.com"
      },
      "phonegap-plugin-barcodescanner": {
        "ANDROID_SUPPORT_V4_VERSION": "27.+"
      },
      "cordova-plugin-nativestorage": {},
      "tangem-sdk": {}
    },
    "platforms": [
      "android"
    ]
  }
}
