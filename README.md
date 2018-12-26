This is a simple setup for **React** without **create-react-app**

for getting start you have to download this file or clone it.

Now you have to create two folder like this

```bash
├── dist
│   ├── index.html # React Icon, You may change if you wish.
└── src
    ├── index.js # This is the root of your app. Contains static HTML right now.

```
in `index.html` file create a div and Add a `script ` tag ,
```js
    <div id="app"></div>
    <script src="./bundle.js"></script>
```


Now you need to `Run` 

```js
npm install
```

It'll automatically Install all dependencies.

now for start `sever` run this command 
```js 
npm start
```



## Here is all Dependencies
* [webpack webpack-dev-server webpack-cli](https://webpack.js.org/)
* [react](https://www.npmjs.com/package/react)
* [react-dom](https://www.npmjs.com/package/react-dom)
* [babel-loader @babel/core @babel/preset-env @babel/preset-react](https://babeljs.io/)