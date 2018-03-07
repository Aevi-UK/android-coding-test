# AEVI Android Coding Test

In order to be considered for the Android position, you must complete the following steps.

### Prerequisites

Please note that this will require Java and Android knowledge.

You will need to have Java, Android Studio or IntelliJ, and the Android SDK installed.

## Instructions

1. Fork this repository.
1. Create a source folder to contain your code.
1. In the source directory, please create an Android app that accomplishes the task below.
1. Commit and push your code to your new repository.
1. Send us a pull request, we will review your code and get back to you.

## Task

Your task is to create a simple Android application that provides word suggestions (aka auto complete) 
based on an input sequence of characters.

Example of source data may be,


hello, helium, height, high, horse, flower, florence

If the input is "he", the application shall respond with "hello, helium, height".

The business requirements for the application are:
* The application shall read a list of words from a file of your choice on the sd-card.
* Other applications on the device should be able to pass in input to the application and get a result back of which suggestion the user chose.
* The application, when started manually, shall query the user for input and respond with suggestions, if any.

The technical requirements are:
* The application must keep in sync with the source of the data on a 5 second interval, regardless of any user interface being visible or not.
* The business logic that parses the source data and provides lookups must be Android agnostic for future portability to other Java environments.
* The application architecture must support future additional alternatives to how the data is stored and retrieved, say from a web server.

If and when any of the above requirements are vague or unclear, we’d like you to make assumptions and decisions that reflect your experience and skills.

When you have finished and pushed your code to github, your repo should contain:
* The application source code, including build scripts and unit tests
* A README file replacing this one that outlines,
    * Any assumptions / decisions you made
    * High level description of your solution
    * Information on how to build the project and how to run the unit tests
    * Information on any tools, libraries, etc you have chosen and why
