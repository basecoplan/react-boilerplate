### How to recreate:

```
npm init
npm install webpack -D
npm install webpack-cli -D
# add 'start': 'webpack' into package.json scripts section
# add webpack.config.js
# fill basic config
# add index.js
# add index.html
npm i babel-core babel-loader babel-preset-es2015 babel-preset-react -D
# add .babelrc
# add webpack babel configuration to webpack.config.js
npm install react react-dom -S
# add basic index.js
```