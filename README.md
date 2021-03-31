# OneAtlas Android SDK

## Quick start

Add the OneAtlas SDK dependency to your ```build.gradle```file:

```gradle
dependencies {
    // ...
    productionImplementation 'com.airbus.oneatlas:oneatlas:1.2.1'
    // ...
}
```

You should also add the url to this Maven repository:

```gradle
allprojects {
    repositories {
        // ...
        maven {
            url "https://raw.github.com/airbusgeo/oneatlas-sdk-android/main"
        }
        // ...
    }
}
```

## Documentation

Please visit [OneAtlas Developer Portal](https://api.oneatlas.airbus.com/mobile).

## Sample code

This [GitHub repository](https://github.com/airbusgeo/oneatlas-sdk-android-sample-code) hosts some Android sample code that will help get you started.

## Author

Airbus DS Geo SA
<br/>
intelligence-airbus-ds-mobile@airbus.com

## License

Copyright ©2019 Airbus DS Geo SA.
<br/>
OneAtlas SDK is available under a proprietary license.
<br/>
See the LICENSE.md file for more info.
