# Building React from scratch

Configuration for React without create-react-app

## commands

git init
npm init -y
mkdir src/index.js
mkdir src/components
mkdir public/index.html
create .babelrc
create webpack.config.js
create .gitignore
create .eslintrc

{
  "presets": [
    "@babel/preset-env",
    "@babel/preset-react"
  ]
}

## React 
npm install react react-dom

## Babel
npm install @babel/core babel-loader @babel/preset-env @babel/preset-react -D

## Webpack
npm install webpack webpack-cli html-webpack-plugin html-loader -D

## webpack dev server
npm i webpack-dev-server -D

## css and sass
npm i mini-css-extract-plugin css-loader node-sass sass-loader -D

## eslint with airbnb config
npm i eslint babel-eslint eslint-config-airbnb eslint-plugin-import eslint-plugin-react eslint-plugin-jsx-a11y -D
