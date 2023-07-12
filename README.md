# ChatGPT-App

ChatGPT is a user-friendly application. This application has been developed using `Java` for the backend and leverages the `OKHTTP` library to create HTTP requests and interact with the `OpenAI API`.

# Installation

1. Clone the project
2. Change the YOUR_API_KEY to Your key
3. Then run the application

# Downloads

You can download the application from https://github.com/Vazidnh3/ChatGPT-App/releases/tag/v1.0.0

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
# Screenshots

<div style="display:flex">
<img src="https://github.com/Vazidnh3/ChatGPT-App/assets/111126298/e0e78a3b-9d5a-4192-a04a-1cff71b42f7a" width="500" height="900">
<img src="https://github.com/Vazidnh3/ChatGPT-App/assets/111126298/f5aab054-a683-4442-8b9d-4e8c669958df" width="500" height="900">
<img src="https://github.com/Vazidnh3/ChatGPT-App/assets/111126298/0dc7d184-ad73-409d-8163-0d993de6cc2e" width="500" height="900">
<img src="https://github.com/Vazidnh3/ChatGPT-App/assets/111126298/6c91231d-138d-474e-a623-7c4d9de6628d" width="500" height="900">
</div>

## References
- <a href="https://platform.openai.com/docs/introduction">OpenAPI Documentation</a>
- <a href="https://square.github.io/okhttp/">OKHTTP Library Documentation</a>
