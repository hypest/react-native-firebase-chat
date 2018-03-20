# react-native-firebase-chat
This repository contains the source code for a simple chat application built with React Native (frontend) and Firebase (backend).

Copy the config from your Firebase account and paste it to firebase.js file that can be found by the path: app/configs/firebase.js 

```javascript
export const firebaseConfig = {
  apiKey: “<API_KEY>“,
  authDomain: “<PROJECT_ID>.firebaseapp.com”,
  databaseURL: “https://<DATABASE_NAME>.firebaseio.com”,
  projectId: “<PROJECT_ID>“,
  storageBucket: “<BUCKET>.appspot.com”,
  messagingSenderId: “<SENDER_ID>“,
}
```

To run the server, use the following command:

```
yarn start
```

And load the app via the Expo app on the device.

<iframe width="880" height="425" frameborder="0" src="//cdn.rawgit.com/dabbott/react-native-web-player/gh-v1.10.0/index.html"></iframe>
