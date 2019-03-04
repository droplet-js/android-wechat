# android-wechat

[![Build Status](https://cloud.drone.io/api/badges/v7lin/android-wechat/status.svg)](https://cloud.drone.io/v7lin/android-wechat)
[![GitHub tag](https://img.shields.io/github/tag/v7lin/android-wechat.svg)](https://github.com/v7lin/android-wechat/releases)
[![API](https://img.shields.io/badge/API-14%2B-brightgreen.svg?style=flat)](https://android-arsenal.com/api?level=14)

### snapshot

````
ext {
    latestVersion = '5.1.4-SNAPSHOT'
}

allprojects {
    repositories {
        ...
        maven {
            url 'https://oss.jfrog.org/artifactory/oss-snapshot-local'
        }
        ...
    }
}
````

### release

````
ext {
    latestVersion = '5.1.4'
}

allprojects {
    repositories {
        ...
        jcenter()
        ...
    }
}
````

### usage

android
````
...
dependencies {
    ...
    implementation "io.github.v7lin:wechat-android:${latestVersion}"
    ...
}
...
````
