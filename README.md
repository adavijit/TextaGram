# TextaGram

TextaGram is a social Media app built with React + Typescript on the front-end and Firebase on the backend

Check out the [deployed site](https://fir-react-image.firebaseapp.com/)

## Summary

This application was built using React (Custom Hooks, Context, React Query, Chakra UI) and Firebase. Firebase firestore handles all the data, and that data is retrieved using a React Query with custom hooks.


## Core packages

1. React Query - Fetch, cache and update data from firebase
2. React Router - Routing
3. Chakra UI - ui component libary and styling
4. React Hook Form - handling forms
5. date-fns - formating dates

## Features

1. Login/Signup
2. Edit profile (add avatar, set fullname)
3. Follow/Unfollow users to see their posts
4. Add/Delete posts
5. Like/Dislike posts
6. Add/Delete comments to posts
7. Check user profile

## Running locally

You need to create firebase app on firebase.google.com then you will get you configuration data.
At the root of your project create an .env.local file with your firebase data:

```bash

REACT_APP_API_KEY=<apiKey>
REACT_APP_AUTH_DOMAIN=<authDomain>
REACT_APP_PROJECT_ID=<projectId>
REACT_APP_STORAGE_BUCKET=<storageBucket>
REACT_APP_MESSAGING_ID=<messagingSenderId>
REACT_APP_APP_ID=<appId>
```

Then run <code>npm i</code> and <code>npm start</code> to see this app in action.
