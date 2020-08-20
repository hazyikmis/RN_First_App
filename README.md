## React Native Intro

Just to remind that REACT is a JS library for building UIs, typically used for WebDev, React is platform agnostic.

- RN is collection of SPECIAL react components
- Components you created always compiled to Native Widgets
- JS code runs as is
- Native Platform APIs (accessing camera, mic, contact list, sms etc) exposed to JS
- Connects JS and NAtive Platform code
- < div > : android.view : UIView : < View >
- < input > : EditText : UITextField : < TextInput >
- NO "Write JS code and run it everywhere"
- NO or VERY LITTLE cross-platform styling of components

* In order to create RN Apps, you have 2 options:
  - Expo CLI (Managed App Development, like a wrapper around your app, complexity removed, lots of utility features. Downside is you are limited to Expo ecosystem. You can always switch to React Native CLI-means eject)
  - React Native CLI (Bare-bone development, Full flexibility, fine grain configuration on your app)

# Expo CLI

Expo Client App (Native Device Simulator) can be downloaded from AppStore of PlayStore and installable to your mobile device. By doing that, you do not need to install your own app, whoever installed Expo Client on their mobile device can access/run/test your app. You can also publish your own apps using Expo Client.

# Steps to Create RN App and Testing it on Expo CLI

(https://expo.io/learn)

- Install NodeJS
- npm install expo-cli --global (or npm install -g expo-cli)
- expo init myNewProject
  - /_ choose "blank - minimal dependencies to run and an empty root comp..." _/
- cd myNewProject
- expo start
  - /_ or run "npm start", check the package.json _/

# Android Studio Emulator Installation

(https://docs.expo.io/workflow/android-studio-emulator/)

- Right bottom menu: Configure -> SDK Manager
- Select related Android versions ("SDK Platforms")
- Select related Tools ("SDK Tools" from top)
  - Android SDK Build-Tools XX
  - Android Emulator
  - Android SDK Platform-Tools
  - Android SDK Tools
  - Intel x86 Emulator Accelerator
  - Click Apply
- Right bottom menu: Configure -> AVD Manager

  - Allows you to create virtual devices (phone, tablet, tv etc ...). Buttom left corner: Create Virtual Device

# Core Components of RN

(https://reactnative.dev/docs/components-and-apis)

- Built-in RN
  - Basic Components
    - View
    - Text
    - Image
    - TextInput
    - ScrollView
    - StyleSheet
  - User Interface
    - Button
    - Switch
  - List Views
    - FlatList
    - SectionList
  - iOS Components & APIs
    - ActionSheetIOS
  - Android Components & APIs
    - BackHandler
    - DrawerLayoutAndroid
    - PermissionsAndroid
    - ToastAndroid
  - Others
    - ActivityIndicator
    - Alert
    - Animated
    - Dimensions
    - Linking
    - Modal
    - ...
- Your UIs / Custom Components (composed of built-in components of other your UIs)

# Styling in RN

- No HTML
- No CSS
- Inline styles or StyleSheet Objects (Written in JS based on CSS syntax)
