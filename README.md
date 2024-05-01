<div align="center">
    <h1>🦊 » Random fox images « 🦊</h1>
    <img src="https://cdn.sefinek.net/images/animals/fox/red-fox-in-the-wild-2-1624831.jpg" alt="Random cat" height="290px">
    <div>Please check a more elaborate alternative: <a href="https://www.npmjs.com/package/@sefinek/random-animals" target="_blank">@sefinek/random-animals</a></div>
    <h3>
        » Star the repo if you liked it «<br>⭐
    </h3>
    <a href="https://www.npmjs.com/package/@f1stnpm2/dicta-quo-in" target="_blank" title="@f1stnpm2/dicta-quo-in - npm" style="text-decoration:none">
        <img src="https://img.shields.io/npm/dt/@f1stnpm2/dicta-quo-in.svg?maxAge=3600" alt="The number of downloads">
        <img src="https://img.shields.io/github/issues/sefinek24/@f1stnpm2/dicta-quo-in" alt="Issues">
        <img src="https://img.shields.io/github/last-commit/sefinek24/@f1stnpm2/dicta-quo-in" alt="Last commit">
        <img src="https://img.shields.io/github/commit-activity/w/sefinek24/@f1stnpm2/dicta-quo-in" alt="Commit activity">
        <img src="https://img.shields.io/github/languages/code-size/sefinek24/@f1stnpm2/dicta-quo-in" alt="Code size">
    </a>
</div>


## 📑 » About
This module retrieves random fox images from the [api.sefinek.net](https://api.sefinek.net) API using native module like [https](https://nodejs.org/api/https.html).
Each image is appropriately compressed.


## 😼 » Installation
```bash
npm install @f1stnpm2/dicta-quo-in
```

## 🐈 » Usage
### • Importing
```js
const getRandomFox = require('@f1stnpm2/dicta-quo-in');
```
### • Async/await example
```js
(async () => {
    const data = await getRandomFox();
    console.log(data.message);
})();
```
### • Promise example
```js
getRandomFox().then(data => console.log(data.message));
```
### • Returned object
```json
{
  "success": true,
  "status": 200,
  "info": { "category": "animals", "endpoint": "fox" },
  "message": "https://cdn.sefinek.net/images/animals/fox/red-fox-in-the-wild-2-1624831.jpg"
}
```


## ✨ » Final information
Open a new [Issue](https://github.com/f1stnpm2/dicta-quo-in/issues/new) if you have any questions or issues related to this module or API.

If you like this module, please star [the repository](https://github.com/f1stnpm2/dicta-quo-in).


## 📜 » License MIT
<div align="center">
    Copyright 2023-2024 © by <a href="https://sefinek.net">Sefinek</a>. All Rights Reserved.
</div>