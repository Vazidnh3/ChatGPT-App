# ChatGPT-App

ChatGPT is a user-friendly application. This application has been developed using `Java` for the backend and leverages the `OKHTTP` library to create HTTP requests and interact with the `OpenAI API`.

# Installation

1. Clone the project
2. Open project in Android Studio
3. Change the YOUR_API_KEY to Yours key
4. Then run the application

# Downloads

You can download the application from 

# Implementation

1. Add the okhhtp dependency
   
     ``` bash
      implementation("com.squareup.okhttp3:okhttp:4.10.0")
     ```
3. Allow the internet permissioin in AndroidManifest.xml file
     ``` bash
      <uses-permission android:name="android.permission.INTERNET" />
     ```
4. OpenAPI url
     ``` bash
     https://api.openai.com/v1/completions
     ```
