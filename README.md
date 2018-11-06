
~~# THIS REPO HAS BEEN DEPRECATED~~
~~Due to the increased fine grained configuration of Appodeal last SDK releases that requires manual edition of AndroidManifest this repo is no longer maitained.~~


BIG Thanks to the original Author : https://github.com/pamartineza/appodeal-sdk-wrapper

## appodeal-sdk-wrapper
Get Appodeal SDK adding just a Gradle dependency line :)



x.y.z.version  -> x.y.z match official Appodeal release, "version" should be 0 or n if I have to make any release to add fixes

The aim of this repository is to simplify updating Appodeal SDK or switching among available versions, it includes all jar dependencies, manifest entries and proguard configuration.

####Please read carefully:

// TODO

##How to add to your project:

This project has been built using Jitpack.io
[![](https://jitpack.io/v/thelittlefireman/appodeal-sdk-wrapper.svg)](https://jitpack.io/#thelittlefireman/appodeal-sdk-wrapper)

Releases available using this repo:
* 2.4.8-beta (Nov 06, 2018)
-> com.github.thelittlefireman:appodeal-sdk-wrapper:2.4.8-beta.0
* 2.0.2-beta (May 31, 2017)
-> com.github.pamartineza:appodeal-sdk-wrapper:2.0.2-beta.0 (aars: facebook-audience-network-4.22.0, adcolony-sdk-3.1.2')
* 2.0.0-beta (April 12, 2017)
-> com.github.pamartineza:appodeal-sdk-wrapper:2.0.0-beta.0 (aars: cheetah-mobile-3.5.aar, facebook-audience-network-4.19.0, adcolony-sdk-3.1.1')
* 1.15.9 (February 16, 2017)
-> com.github.pamartineza:appodeal-sdk-wrapper:1.15.9.0 (aars: cheetah-mobile-3.4.7.aar)
* 1.15.8 (December 15, 2016)
-> com.github.pamartineza:appodeal-sdk-wrapper:1.15.8.0 (aars: cheetah-mobile-3.4.7.aar)
* 1.15.7 (October 10, 2016)
-> com.github.pamartineza:appodeal-sdk-wrapper:1.15.7.0 (aars: cheetah-mobile-3.4.7.aar)
* 1.15.5 (September 26, 2016)
-> com.github.pamartineza:appodeal-sdk-wrapper:1.15.5.0 (aars: cheetah-mobile-3.4.7.aar)
* 1.15.3 (September 6, 2016)
-> com.github.pamartineza:appodeal-sdk-wrapper:1.15.3.0 (aars: unity-ads-1.5.8.aar and cheetah-mobile-3.4.7.aar)
* 1.15.2 (August 12, 2016)
-> com.github.pamartineza:appodeal-sdk-wrapper:1.15.2.0 (aars: unity-ads-1.5.8.aar and cheetah-mobile-3.4.7.aar)
* 1.15.1 (August 8, 2016)
-> com.github.pamartineza:appodeal-sdk-wrapper:1.15.1.0 (aars: unity-ads-1.5.8.aar and cheetah-mobile-3.4.7.aar)
* 1.14.15 (June 17, 2016)
-> com.github.pamartineza:appodeal-sdk-wrapper:1.14.15.0 (aar: unity-ads-1.5.6.aar)

_(Note: aars are available in this repo in the folder aars)_



Add to your root build.gradle

```groovy
allprojects {
	repositories {
		...
		maven { url "https://jitpack.io" }
	}
}
```	
	
	
Add to your app build.gradle, check Jitpack badge to get current release numbers [![](https://jitpack.io/v/thelittlefireman/appodeal-sdk-wrapper.svg)](https://jitpack.io/#thelittlefireman/appodeal-sdk-wrapper)
```groovy
dependencies {
        compile 'com.github.thelittlefireman:appodeal-sdk-wrapper:x.y.z.version'
}
```	

####Please star :star: this project if you find it useful :)
