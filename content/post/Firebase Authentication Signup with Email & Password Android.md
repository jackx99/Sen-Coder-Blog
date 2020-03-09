---
title: Firebase Authentication Signup with Email & Password Android
date: 2019-10-22T06:00:00+08:00
thumbnail: img/Firebase Authentication Signup with Email & Password Android.webp
comments: true
tags:
- firebase
- restapi
- kotlin
- android
- androidstudio
categories:
- android

---
An app should securely save user data for the right data access on the database. In this tutorial, We will sign up using the email and password through OkHttp.

You can watch the [YouTube video](https://youtu.be/xDiocobaxj4) or Learn more.

OkHttpClient must have a Request and callback on accepting the responsibility of issued HTTP. A Request should have a URL with the parameter of the web API key and body if it asks for it. If the email provided is unique, then the response should return a token for authorization.
{{< gist sen-coder 90d2bf56697b3dc473263700e6d50337 >}}