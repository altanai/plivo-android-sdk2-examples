## Android Sample App for Voice Calling

### Get Started

1. Clone this repo

2. Launch Android Studio

3. Choose ‘Open an existing Android Studio Project’, Open and Run the app


##### Pre-requisites

1. [Plivo Account](https://manage.plivo.com/accounts/register/)

2. [Create an endpoint with a username and a password.](https://manage.plivo.com/endpoint/create/)


##### Get started
	
1. Launch the application from Android Studio.
2. Enter the username and password of your endpoint when prompted for.
	
##### VoiceCallingApp shows you

1. How to register your your SDK to Plivo. This is the first step to make and receive calls from the Android SDK.
2. How to make outbound calls from your app using the Android SDK.
3. How to receive inbound calls on your app using the Android SDK.

Reference link: [Android SDK Documentation](https://www.plivo.com/docs/sdk/android/)

##### Change Log:

1. The SDK now uses OpenSSL v1.0.2k. This version satisfies recent warnings seen by publishers to the Google Play store.
2. The SDK now supports all available architectures

##### Bug Fixes:

1. Fixed a number of crashes that could occur when initial SIP request is sent to the server.
2. Fixed a number of crashes that could occur when we make calls.


