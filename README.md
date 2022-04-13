# webpack-ts-react

## Create a directory
```zsh
  mkdir app-name && cd $_
```
## install react dependencies
```zsh
  yarn add react react-dom typescript 
  yarn add -D @types/react @types/react-dom
```
## instal dev dependencies webpack, babel, CSS and image loaders
```zsh
  yarn add -D webpack webpack-cli webpack-dev-server
  yarn add -D babel-loader @babel/preset-typescript @babel/preset-react @babel/preset-env @babel/core  
  
  yarn add -D css-loader style-loader url-loader react-svg-loader
  yarn add -D html-webpack-plugin
```
## Create a file named `webpack.config.js`
### paste the content inside the attached file
  
## Create a file named `.babelrc`
### paste the content inside the attached file

## Add to the `package.json` a script call
```json
  "scripts": {
      "start": "webpack-dev-server",
      "build": "webpack"
    },
```
## create the folder `/public`
```zsh
  mkdir public && cd $_ && touch index.html && ../
```
  add the  html content as is done on react 

## create the folder `/src`
```zsh
  mkdir src && cd $_ && touch index.tsx && ../
```
## after the configuration you can run
```zsh
  yarn start
```
