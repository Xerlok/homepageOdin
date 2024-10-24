# template
A basic template with webpack

Package JSON:
  npm init -y

Webpack installation:
  npm install webpack webpack-cli --save-dev
  npm install --save-dev style-loader css-loader

EsLint installation:
  npm init @eslint/config

Jest installation:
  npm install --save-dev jest

Babel with Jest installation:
  npm install --save-dev babel-jest @babel/core @babel/preset-env
  npm install --save-dev babel-loader

Package JSON Scripts:
  "build": "webpack",
  "watch": "webpack --watch",
  "preview": "git subtree push --prefix dist origin gh-pages",
  "test": "jest"
