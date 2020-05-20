*Set up steps* <br>
npm init <br>
npm install react <br>
npm install webpack webpack-cli --save-dev <br>
npm install svg-inline-loader --save-dev <br>
npm install css-loader --save-dev <br>
npm install style-loader --save-dev <br>
npm install babel-loader --save-dev <br>
npm install html-webpack-plugin --save-dev <br>
npm install webpack-dev-server --save-dev <br>
*Package dot JSON comments* <br>
**Windows** <br>
"scripts":{<br>
    "build": "SET NODE_ENV= 'production' && webpack", <br>
    } <br>
**All Others**
"scripts":{<br>
    "build": "SET NODE_ENV= 'production' webpack", <br>
    } <br>