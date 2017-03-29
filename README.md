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

    startListen (onSuccess, onFail, showUI, showPunctuation) {
    Method to start dictation. Dictation stops after a short break after speech, or about 8 seconds of silence.
    onSuccess:function Callback function when something is heard or timeout.
    onFail::function Callback function when somethong is wrong. Seems not used.
    showUI:boolean Indicates if the iFly UI overlay will be shown during listening. ture by default.
    showPunctuation:boolean Indicates if punctuation will be recognized. true by default.
    
    stopListen ()
    Method to stop listening.

## Note
Always create your own App ID at http://www.xfyun.cn/ and replace the original App ID @ Line 20 in speech.m

    Always create your own App ID at http://www.xfyun.cn/ and replace the original App ID
    #define SPEECH_APP_ID @"xxxxxxxx" // BeanLab App ID
