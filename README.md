Egeniq's Maven Repository
========

How to use
--------
Simply add the repository to your  build.gradle file:

    repositories {
        mavenCentral()
        maven {
            // Egeniq Maven Repository
            url 'https://raw.github.com/egeniq/mvn-repo/master'
        }
    }

Now you can use the artifacts like this:

    dependencies {
        compile 'com.egeniq:android-library:1.0'
    }