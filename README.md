# Video SDK applicaiont for MindSpace Flutter Internship 

Cross platform compatible Video conferencing app created using flutter and Video SDK for as a sample project for MindSpace flutter intern position.



## Features

- [x] Works for both ios and android
- [x] Real-time video and audio conferencing
- [x] Enable/disable camera
- [x] Mute/unmute mic
- [x] Switch between front and back camera
- [x] Chat



<br/>



## Prerequisites to Setup

- If your target platform is iOS, your development environment must meet the following requirements:
  - Flutter 2.0 or later
  - Dart 2.12.0 or later
  - macOS
  - Xcode (Latest version recommended)
- If your target platform is Android, your development environment must meet the following requirements:
  - Flutter 2.0 or later
  - Dart 2.12.0 or later
  - macOS or Windows
  - Android Studio (Latest version recommended)
- If your target platform is iOS, you need a real iOS device.
- If your target platform is Android, you need an Android simulator or a real Android device.
- Valid Video SDK [Account](https://app.videosdk.live/)

<br/>

## Run the Sample App

### 1. Clone the sample project

Clone the repository to your local environment.

```js
$ git clone 
```

### 2. Copy the .env.example file to .env file.

Open your favorite code editor and copy `.env.example` to `.env` file.

```js
$ cp .env.example .env
```

### 3. Modify .env file

Generate temporary token from [Video SDK Account](https://app.videosdk.live/signup).

```js title=".env"
AUTH_TOKEN = "TEMPORARY-TOKEN";
```

### 4. go into the mindspace_app folder


```js
cd mindspace_app
```

### 5. Install the dependecies

Install all the dependecies to run the project.

```js
flutter pub get
```

### 6. Run the sample app

Bingo, it's time to push the launch button.

```js
flutter run
```

#YouTube Sample Videos

Video from Screen1: [Screen 1](https://youtu.be/4mts04bh4kg?si=hU4PZgbIXz8WIviB)
Video from Screen2: [Screen 2](https://youtu.be/davPdkG89Xs?si=Y_V58s0dVRjT5etE)
