![App](/images/just_java_logo.png)
# Just Java  
[![Build Status](https://app.bitrise.io/app/c373b1aa540acc1c/status.svg?token=u-KpJIBnS_0TQUtBtYNEJQ&branch=master)](https://app.bitrise.io/app/c373b1aa540acc1c)
[![Playstore](https://img.shields.io/badge/Download-Playstore-brightgreen.svg)](https://play.google.com/store/apps/details?id=com.marknkamau.justjava)
[![latest build](https://img.shields.io/badge/Download-Latest%20build-brightgreen.svg)](https://skyll.herokuapp.com/justjava/latest?redirect=true)

A mock Android application for a coffee shop. 

[Website](https://marknjunge.com/projects/justjava)

* 100% Kotlin.
* MVP architecture.
* Room (with RxJava) for local data storage.
* Firebase Authentication for Authentication.
* Firebase Cloud Firestore for cloud storage.
* Firebase Cloud Messaging for notifications. 
* Crashlytics by Fabric for crash reporting.
* Mpesa payment

## Cloning

- Create a Firebase project and add two applications; `com.marknkamau.justjavastaff` 
and `com.marknkamau.justjava`. Add the `google-service.json` files to their respective folders.
- Enable Email/Password authentication on Firebase.
- Create a `keys.properties` file based on`keys.properties.sample`. You can get the credentials from
[Safaricom developer portal](https://developer.safaricom.co.ke/). If you don't want to use M-Pesa, 
you can put random values.

## Screenshots

![App](/images/branding.png)

## Download 
<a href='https://play.google.com/store/apps/details?id=com.marknkamau.justjava'>
​    <img alt='Get it on Google Play' 
​         src='https://play.google.com/intl/en_us/badges/images/generic/en_badge_web_generic.png'
​         height="116" width="300"/>
</a>  

[Download latest build](https://skyll.herokuapp.com/justjava/latest?redirect=true)
