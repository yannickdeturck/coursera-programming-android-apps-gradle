# coursera-programming-android-apps
This repository contains the Gradle version of the assignments of the 'Programming Mobile Applications for Android Handheld Systems'-Coursera course.

IntelliJ13 was used as IDE on Mac OS X 10.9, Genymotion for AVDs, Galaxy Nexus 4.3 API 18 as VD.

## Installation
Clone or download the assignment.

```ANDROID_HOME``` must be configured as environment variable, this needs to point at the 'sdk'-folder of your ADT bundle.

It is not necessary to have Gradle installed and set up, it is possible to make use of the Graddle Wrapper in the project using the gradlew- (Unix) or gradlew.bat-script (Windows).
Several examples of commands:

To clean, use:

    $ ./gradlew clean
    
To build, use:

    $ ./gradlew build
    
To execute instrumentation tests, make sure you have a virtual device running and use:

    $ ./gradlew connectedInstrumentTest

Import the project in IntelliJ13, you can select 'Gradle' when being prompted about importing from an external model. Tests can be run by right-clicking an individual Test or the Test root (```instrumentTest/java```).
If no Run/Debug Configuration exists for running the application on the Virtual Device, create a new 'Android Application'-configuration and select the correct module.

A similar workflow should exist for importing and running the Gradle project in Eclipse.
