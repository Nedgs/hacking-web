# Hacking Web

By Nader Gouasmi & Yvon Lewis Ghilbert BINGANGOYE 


## Features

- Angular 12.x + Firebase
- OAuth and Email/Password Signup with Firebase

## Usage

1.  Run

- `git clone https://github.com/Nedgs/hacking-web.git`
- `npm install`

2.  Create a project at https://firebase.google.com/ and grab your web config:


3.  Add the config to your Angular environment

#### src/environments/

Update the `environment.prod.ts` and `environment.ts` files. 

```typescript
export const environment = {
  production: false,
  firebase: {
    apiKey: 'APIKEY',
    authDomain: 'DEV-APP.firebaseapp.com',
    databaseURL: 'https://DEV-APP.firebaseio.com',
    projectId: 'DEV-APP',
    storageBucket: 'DEV-APP.appspot.com',
    messagingSenderId: '...',
    appId: '...',
  }
};
```


5.  Run `ng serve`
