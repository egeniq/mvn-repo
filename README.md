Egeniq's Maven Repository
========

How to use
--------
Simply add the repository to your __top level__ build.gradle file:

    allprojects {
        repositories {
            mavenCentral()
            maven {
                // Egeniq Maven Repository
                url 'https://raw.github.com/okaymak/mvn-repo/'
            }
        }
    }

Now you can use the artifacts like this:

    dependencies {
        compile 'com.egeniq:android-library:1.0'
    }
