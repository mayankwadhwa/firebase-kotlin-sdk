<h1 align="left">Firebase Kotlin Multiplatform SDK <img alt="GitHub last commit" src="https://img.shields.io/github/last-commit/teamhubapp/firebase-kotlin-multiplatform-sdk?style=flat-square"></h1>
<img align="left" width="75px" src="https://avatars2.githubusercontent.com/u/42865805?s=200&v=4"> 
  <b>Built and maintained with 🧡 by <a href="https://teamhub.dev">TeamHub</a></b><br/>
  <i>Real-time code collaboration inside any IDE</i><br/>
  🔓 <a href="https://teamhub.typeform.com/to/uSS8cv">Request Early Access</a>
<h4></h4>

The Firebase Kotlin Multiplatform SDK implements the client-side libraries used by applications using Firebase services. 

It a light-weight Kotlin layer that mirrors the Firebase Android SDK but connects to the correct native Firebase SDKs for each target platform, enabling you to use Firebase directly from your common source in your Kotlin Multiplatform projects targeting iOS, Android or JS.

## Available libraries

The following libraries are available for the various Firebase products.


| Service or Product	                                                                 | Gradle Dependency                                                                                                                   | SDK Coverage                                                                                                                                                                                                               |
| ------------------------------------------------------------------------------------ | :-----------------------------------------------------------------------------------------------------------------------------------|:-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [Authentication](https://firebase.google.com/docs/auth#kotlin-android)               | [`dev.teamhub.firebase:firebase-auth:0.1.0`](https://mvnrepository.com/artifact/dev.teamhub.firebase/firebase-auth/0.1.0)           | [![<50%](https://img.shields.io/badge/-50%25-lightgrey?style=flat-square)](/firebase-auth/src/commonMain/kotlin/dev/teamhub/firebase/auth/auth.kt) [![Android: 50%](https://img.shields.io/badge/Android-50%25-green?logo=android&style=flat-square)](/firebase-auth/src/androidMain/kotlin/dev/teamhub/firebase/auth/auth.kt) [![JS: 50%](https://img.shields.io/badge/Web-50%25-yellow?logo=javascript&style=flat-square)](/firebase-auth/src/jsMain/kotlin/dev/teamhub/firebase/auth/auth.kt) [![iOS: 0%](https://img.shields.io/badge/iOS-0%25-blue?logo=apple&style=flat-square)](/firebase-auth/src/iosMain/kotlin/dev/teamhub/firebase/auth/auth.kt) |            
| [Realtime Database](https://firebase.google.com/docs/database#kotlin-android)        | [`dev.teamhub.firebase:firebase-database:0.1.0`](https://mvnrepository.com/artifact/dev.teamhub.firebase/firebase-database/0.1.0)   |              
| [Cloud Firestore](https://firebase.google.com/docs/firestore#kotlin-android)         | [`dev.teamhub.firebase:firebase-firestore:0.1.0`](https://mvnrepository.com/artifact/dev.teamhub.firebase/firebase-firestore/0.1.0) |              
| [Cloud Functions](https://firebase.google.com/docs/functions/callable#kotlin-android)| [`dev.teamhub.firebase:firebase-functions:0.1.0`](https://mvnrepository.com/artifact/dev.teamhub.firebase/firebase-functions/0.1.0) |              