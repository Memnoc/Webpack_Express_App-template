# Webpack-Express App

The goal of this repo is be an example of a basic but functional app built on Express and Webpack.

## How's the app configured

The app has both a dev mode and a prod mode. 
The dev mode has hot-reloading configured for ease of testing.
A custom entry point has been set up in `index.js`

## What's installed

The app had the following components installed (in prod mode):

- Webpack CLI
- Babel
- Webpack dev server

- HtmlWebPackPlugin
- MiniCssExtractPlugin
- OptimizeCSSAssetsPlugin
- TerserPlugin
- WorkboxPlugin
- Service workers

The app had the following components installed (in dev mode):

- HtmlWebPackPlugin
- CleanWebpackPlugin

## Get Up and Running

Fork this repo, then clone it to your computer or simply download it.


`cd` into your new folder and run:
- ```npm install```
- ```npm run build-dev``` to start the app in dev mode
- ```npm start``` on another terminal

- ```npm run build-prod``` to start the app in prod mode
- ```npm start``` on another terminal
- this app runs on localhost:8081, but you can of course edit that in server.js

## List of useful npm commands

 - ```npm i webpack webpack-cli```
 - ```npm i -D @babel/core @babel/preset-env babel-loader```
 - ```npm i -D html-webpack-plugin```
 - ```npm i -D clean-webpack-plugin```
 - ```npm i -D style-loader node-sass css-loader sass-loader```
 - ```npm i -D mini-css-extract-plugin```
 - ```npm i -D optimize-css-assets-webpack-plugin terser-webpack-plugin```
 - ```npm install workbox-webpack-plugin --save-dev```