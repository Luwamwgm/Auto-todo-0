# Zero

* `npm create vite@latest authenticated-todo -- --template react`
* Find a cool icon (svg, png or ico)!!
    * Add it to `public`
    * remove vite.svg from `public`
    * remove react.svg from `src/assets`
    * change the name index.html
* Add the file Anotherpage, error, Home, Login and Signup in `page/`
* Add the following in `src/index.css`
```
#root {
  max-width: 1280px;
  margin: 0 auto;
  padding: 2rem;
  text-align: center;
}
```
* delete App.css and App.jsx
* `npm install --save-dev prettier`
* `npm install react-router-dom'
* in main.jsx, import page, import react-router, set the routes, change the main component to RouterProvider
* run `npm run install`, then `npm run dev`
* verify the url: /, /x, /signup, /login, /random

///////////
run npm install firebase
run mpm run dev
Go to firebase console:
create project
add authentication
enable userid/password
copy config
create firebase.js with firebase config
add import { getAuth }, export const auth
To page/Login:
add imports of "firebase/auth" and "../firebase"
add onLongin funtion
add onClick to the button
To page/Signup:
add imports
add onSubmit function
add onClick to button
To page/Home:
add imports
add const navigate
add useEffect
add handleLogout
add logout button
navigate to /, /x

///////
https://firebase.google.com/docs/firestore/security/rules-fields
/////////////

