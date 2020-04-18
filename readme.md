Basic Webpack configuration to provide a React Starter Kit 

To start 
1. npm install - install all relevant node modules
2. npm run start - to start development server
3. npm run build - to create a build 
Update provides support for ES6 function and components. 
To enable that support install 
https://babeljs.io/docs/en/babel-plugin-proposal-class-properties

Also to support ES7 features like async await 
use 
https://babeljs.io/docs/en/babel-polyfill 

Add polyfill to entry point using 
entry: ['@babel/polyfill', './src/index.js'],