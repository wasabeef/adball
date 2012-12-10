adball
======

Adb All devices command

## Requirements

* Download the [Android SDK](http://developer.android.com/sdk/index.html)

Android SDK Enviroment Path Setting

    export PATH=$PATH:${android_sdk}/platform-tools/
    // ${android_sdk} refers to your android sdk root folder

## Usage

Install

    ./adball install Sample.apk


Uninstall

    ./adball uninstall Sample.apk
    
push

    ./adball push /yourpath/sample.txt /sdcard/
    
pull
    
    ./adball pull /sdcard/myDog.png ./