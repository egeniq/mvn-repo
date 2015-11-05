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
        compile 'com.egeniq:android-library:1.0.5'
    }

Available artifacts:
--------

[Egeniq Android Library](https://github.com/egeniq/egeniq-android)

    com.egeniq:android-library:1.0
    com.egeniq:android-library:1.0.1
    com.egeniq:android-library:1.0.2
    com.egeniq:android-library:1.0.3
    com.egeniq:android-library:1.0.4	Advanced markup with SpannableTextView
    com.egeniq:android-library:1.0.5	Contains a bug in Button and TextView, don’t use
    com.egeniq:android-library:1.0.6	Added DigestFrequency to msgs/v2/entity/Endpoint