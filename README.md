## React Native Intro

Just to remind that REACT is a JS library for building UIs, typically used for WebDev, React is platform agnostic.

- RN is collection of SPECIAL react components
- Components you created always compiled to Native Widgets
- JS code runs as is
- Native Platform APIs (accessing camera, mic, contact list, sms etc) exposed to JS
- Connects JS and NAtive Platform code
- <div> : android.view : UIView : <View>
- <input> : EditText : UITextField : <TextInput>
- In order to create RN Apps, you have 2 options:
  - Expo CLI (Managed App Development, like a wrapper around your app, complexity removed, lots of utility features. Downside is you are limited to Expo ecosystem. You can always switch to React Native CLI-means eject)
  - React Native CLI (Bare-bone development, Full flexibility, fine grain configuration on your app)

# Expo CLI

Expo Client App (Native Device Simulator) can be downloaded from AppStore of PlayStore and installable to your mobile device. By doing that, you do not need to install your own app, whoever installed Expo Client on their mobile device can access/run/test your app. You can also publish your own apps using Expo Client.

# Steps to Create RN App and Testing it on Expo CLI

(https://expo.io/learn)

- Install NodeJS
- npm install expo-cli --global
- expo init myNewProject
  - /_ choose "blank - minimal dependencies to run and an empty root comp..." _/
- cd myNewProject
- expo start
  - /_ or run "npm start", check the package.json _/
