# React Native Typescript sample run on Android / iOS / Web
 
Introduction
------------

The goal of this React Native Typescript application run on Android, iOS and Web platform. 
* Refer medium article [How to add React Native Web to an existing React Native project](https://arry.medium.com/how-to-add-react-native-web-to-an-existing-react-native-project-eb98c952c12f)
* Youtube Steps [https://www.youtube.com/watch?v=itMhGwiLrrs]

Getting Started
---------------
This project uses the npm, pod, Gradle build system. To build this project, use the `yarn install` command in [Visual Studio Code](https://code.visualstudio.com/download) or Getting Started with React native typescript project
```sh
npx react-native init rnw_blogpost --template react-native-template-typescript
```

Project command
---------
To run this project, use `npm run android` or `npm run ios`.
if need clean this project, use `npm run android-clean` or `npm run ios-clean`.

| npm run ... | Description |
| --- | --- |
| android | Run android development-mode on emulator or phone |
| ios | Run iOS project with Simulator |
| ios-pod-install | install depedenceny for iOS project |
| web | Run web project on [Browser](hhttp://localhost:8080/) |
| test  | jest testing  |
| lint | lint testing |

Libraries Used
--------------
* [React Getting started](https://reactnative.dev/docs/getting-started)
* [Getting Started with TypeScript](https://reactnative.dev/docs/typescript)
* [react-native-web](https://github.com/necolas/react-native-web/)

Add yarn dependencies
--------------
```sh
yarn add react-native-web
```

IDE setup
------------------------
For development, the latest version of [Android Studio](https://developer.android.com/studio/) is required. The latest version can be
downloaded from [Xcode](https://developer.apple.com/xcode/).
