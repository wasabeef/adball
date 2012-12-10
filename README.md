adball
======

Adb All devices command

## Requirements

* Download the [Android SDK](http://developer.android.com/sdk/index.html)

Android SDK Environment Path Setting

    export PATH=$PATH:${android_sdk}/platform-tools/
    // ${android_sdk} refers to your android sdk root folder

## Usage

Install

    ./adball install Sample.apk
    // adball install [apkfile]


Uninstall

    ./adball uninstall Sample.apk
    // adball uninstall [apkfile]
    
push

    ./adball push /yourpath/sample.txt /sdcard/
    // adball push [local] [remote]
    
pull
    
    ./adball pull /sdcard/myDog.png ./
    // adball push [remote] [local]