BadgevilleOnAndroid is a "starter kit" for integrating with Badgeville from the 
Android platform. BadgevilleOnAndroid is an Eclipse project based on the Android
Eclipse plugin; however, you can simply copy the com.badgeville.helper classes 
into your project/code base to integrate with Badgeville.

A brief summary of the key files:

src\com\badgeville\helper\HTTPHelper.java: 
    A helper class for Apache�s HTTPClient library

src\com\badgeville\helper\BVHelper.java: 
    Ahelper class for Badgeville�s berlin APIs, built on HTTPHelper

src\com\badgeville\BadgevilleClient.java.java: 
    A sample client that demonstrates use of BVHelper to create an activity


