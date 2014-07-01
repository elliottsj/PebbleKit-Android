PebbleKit-Android
=================

Gradle-compatible copy of the PebbleKit library for android that comes with the Pebble SDK.

A software development kit that provides methods for interacting with Pebble Smartwatch applications.


Usage
-----

First install the .aar to your local Maven repository:

```bash
./gradlew install
```

Then in another Android project, add the your local maven repository:

```groovy
allprojects {
    repositories {
        jcenter()
        mavenLocal()
    }
}
```

Then you can add it to your dependencies:

```groovy
dependencies {
    compile 'com.getpebble.android.kit:library:2.0.0@aar'
}
```
