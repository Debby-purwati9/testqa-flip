# testqa-flip
Automation for test QA Flip



# Table of Contents
1. [Requirements](#1-Requirements)
2. [Getting Started](#2-getting-started)
3. [Running Automation Test](#3-running-automation-test)

## 1. Requirements

### Check if Node.js, Java, Appium is already installed
  Open Terminal :

    node -v   
    node --version
    npm -v
    npm --version
    java -version
    appium -v

* Install [NVM](https://github.com/coreybutler/nvm-windows) ( [Download](https://github.com/coreybutler/nvm-windows/releases/download/1.1.7/nvm-setup.zip) )

  Open Terminal :
    ```
    nvm install v8.12.0
    ```

* Install Node.Js version *8.12.0* and Npm version *6.4.1*
  *  Install [Node.js](https://nodejs.org/download/release/v8.12.0/)
  *  Check version  

    Open Terminal :

    ```
    node -v
    version v8.12.0
    ```
  *  Check version  

    Open Terminal :

    ```
    npm -v 
    version 6.4.1
    ```
  *  Check folder node 

    Open Terminal :

    ```
    where node
    ```
  *  Setup Path Node.js and Npm 

* Install Java 
    * Install Java Development Kit Version 8 ( [Download](https://www.oracle.com/technetwork/java/javase/downloads/jdk8-downloads-2133151.html) ) | ( [Tutorial](https://www.youtube.com/watch?v=LlLRjFptXAY) )
    * Setup Path java Jdk and jre

* Setup Android Sdk

    * [Download Android SDK](https://dl.google.com/android/repository/sdk-tools-windows-4333796.zip)

    * [Setup ANDROID_HOME and Path](http://www.automationtestinghub.com/setup-android-environment-variables/)    

* Install [CHOCOLATEY](https://chocolatey.org/install)

* Intall [YARN](https://yarnpkg.com/en/docs/install#windows-stable)

* Install Mocha 
    ```
    npm install -g mocha@5.2.0
    ```    

## 2. Getting Started

* Clone This Project
  ```
  git clone https://github.com/Debby-purwati9/testqa-flip.git/
  ```
* Open project directory in terminal
  ```
  cd testqa-flip
  ```
* From root project directory copy .env.example into .env  
* Copy APK  to apps folder
* Install Project Dependencies
  ```
  yarn install
  ```
* Create avd Nexus 5 API 25 

## 3. Running Automation Test

### Running On Emulator 
* Run Test 
    * Run Appium

        Open Terminal 1 : 
        ```
        yarn run appium
        ````
    * Run Test

        Open Terminal 2 :
        ```
        yarn test
        ```
* Run 1 Test Cases
    * command line =>  mocha test/folder test/name test cases.test.js

        Example :
        ```
        mocha test/login.test.js
        ```
