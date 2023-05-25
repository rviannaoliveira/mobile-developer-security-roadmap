<p align="center">
  <img src="android.png" align="center" width=300>
  <img src="ios.jpeg" align="center" width=300>
</p>


<h3 align="center"> 
  
![visitor badge](https://visitor-badge.glitch.me/badge?page_id=rviannaoliveira.mobile-developer-security-roadmap)
<a href="https://www.linkedin.com/in/rviannaoliveira"><img src="https://user-images.githubusercontent.com/5540492/212076261-85e22389-eaae-4ac0-9c9d-06196f54ac70.png" height="20px"/></a>
<a href="https://medium.com/@rodrigo.vianna.oliveira"><img src="https://img.shields.io/badge/Medium-12100E?style=for-the-badge&logo=medium&logoColor=white" height="20px"/></a>
<a href="https://www.youtube.com/c/CodandoTV"><img src="https://img.shields.io/badge/YouTube-FF0000?style=for-the-badge&logo=youtube&logoColor=white" height="20px"/></a>
</h3> 

<h1 align="center">Mobile developer security roadmap 🔒</h1>


Welcome to Mobile Developer Security Roadmap 2023

The main purpose of this roadmap is to help anyone who to get knowledge about security.
This contains all topics to help you find what you are looking for quickly. I hope I can help you=


### :book: Authors
This was derived from a series created on youtube about security, check it out and subscribe to the channel. The video was made together with:\
[Me](https://www.linkedin.com/in/rviannaoliveira)\
[Gabriel Amorim](https://www.linkedin.com/in/gabriel-silveira-amorim-2a8b5827/)\
[João Calvo](https://www.linkedin.com/in/jfc-nunes/)\
[Gabriel Monteiro](https://www.linkedin.com/in/gabrielmcsilva/)


take a look and subscribe to the channel from the [CodandoTV](https://www.youtube.com/@CodandoTV) to help this initiative :clapper:\
<a href="https://www.youtube.com/watch?v=edPQ_CEVrgo&list=PL-7tME9TKyA4W3WLme-8gp2mw5nhtSG-E"><img src="https://img.shields.io/badge/YouTube-FF0000?style=for-the-badge&logo=youtube&logoColor=white" height="20px"/></a>

### ✨ Contribution 
This repo is open to contributions
If you have any questions, suggestions let's have it over [Issues](https://github.com/rviannaoliveira/mobile-developer-security-roadmap/issues)\
***Remembering that this is our point of view and it is up to you to evaluate the best for your scenario***

## 🗺️ Roadmap - You can access the link to the original image of the link by [Miro](https://miro.com/app/board/uXjVPkAoz6k=/)

<image src="general.png"/>

## Contents

- 📦 Safe Storage
  * [Cryptography of sharedpreferences](https://developer.android.com/reference/androidx/security/crypto/EncryptedSharedPreferences)
  * [DataStore + Cipher (to secure the data)
  (modern data storage solution)](https://developer.android.com/topic/libraries/architecture/datastore)
  * [Encryption of Data to store 🤖](https://developer.android.com/reference/androidx/security/crypto/MasterKey.Builder)
  * Cryptography of userdefault
  * [General Data Encryption for :apple:](https://github.com/apple/swift-crypto)
* ⛅ Code Obfuscation
  * [proguard](https://developer.android.com/studio/build/shrink-code) 🟥
  * [dexguard](https://www.guardsquare.com/)
  * [swiftshield](https://github.com/rockbruno/swiftshield) 🟥
  * [iXGuard](https://www.guardsquare.com/)
* 🦠 Malware
  * [Detection of accessibility services](https://medium.com/wultra-blog/blocking-untrusted-accessibility-readers-on-android-82a20ed60aa5)
  * [Screen overlay](https://medium.com/devknoxio/what-is-tapjacking-in-android-and-how-to-prevent-it-50140e57bf44)
  * [Root user block](https://github.com/scottyab/rootbeer)
  * Lock keyboard 🍎
  * [Remote access blocking](https://proandroiddev.com/protect-your-android-app-content-and-embrace-its-security-1adeb5437c6)
  * Layout configuration setFilter 🍎
  * [Enable activity parameter to leave white screen 🤖](https://proandroiddev.com/protect-your-android-app-content-and-embrace-its-security-1adeb5437c6)
  * Listen to events and control the screen tree and place the screen on top :apple:
* 🔑 User Authentication
  * Two factor authentication
  * One time password 
  * [Proof of life](https://www.liveness.com/)
* 🔒 Secure Communication of Data in Transit
  * SSL 🟥
  * Request Signature
  * Request Encryption
  * [TLS Pining](https://owasp.org/www-community/controls/Certificate_and_Public_Key_Pinning)
  * [Two way pining](https://owasp.org/www-community/controls/Certificate_and_Public_Key_Pinning)
* 🔎 Code Analysis
  * [SwiftLint](https://github.com/realm/SwiftLint)
  * [Detekt](https://github.com/detekt/detekt)
  * [Sonar](https://www.sonarsource.com/products/sonarqube/)
  * [Fortify](https://fortifyapp.com/)
  * [MobSF](https://github.com/MobSF/Mobile-Security-Framework-MobSF)
  * Code Review 🟥
  * [GuardSquare](https://www.guardsquare.com)
* 💻 Realtime Application Self Protect (Rasp) 
  * Debug 🟥
  * [Debugger](https://dexprotector.com/docs)
  * [jail break](https://medium.com/@i0sa/jailbreak-development-for-ios-developers-ba3cc54ee8f8) 🍎
  * [Root](https://github.com/scottyab/rootbeer)🤖
  * [App Tamper](https://dexprotector.com/docs)
  * [File Tamper](https://dexprotector.com/docs)
  * [App Cloner](https://proandroiddev.com/preventing-android-app-cloning-e3194269bcfa)
  * [Memory Hook](https://dexprotector.com/docs)
  * [Validate the Installation Source](https://dexprotector.com/docs)

*  🟥 Cards that have a red tag we believe to be mandatory for any case

Contributors:

<img src="https://opencollective.com/roadmapsecurity/contributors.svg?width=890&button=false" />

License
-------

    Copyright 2023 Rodrigo Vianna

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

    http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.


