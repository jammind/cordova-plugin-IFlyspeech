# cordova-plugin-IFlyspeech
科大讯飞的语音听说读写的cordova插件 
### Supported Platforms

- iOS
- android

## Installation

cordova plugin add https://github.com/jammind/cordova-plugin-iflyspeech

## Removal

cordova plugin rm cordova-plugin-xunfeiListenSpeakin

## API
startListen (onSuccess, onFail, showUI, showPunc) {
Method to start dictation. Dictation stops after a short break after speech, or about 8 seconds of silence.
onSuccess:function is a callback function when something is heard
onFail is not used
showUI:boolean indicates if the iFly UI overlay will be shown during listening. ture by default.
showPunc is uncertain
