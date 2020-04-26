# Webpack-Express App

The goal of this repo is be an example of a basic but functional app built on Express and Webpack.

If you want to start developing an app that wprks with API's and you need a solid configuration with Webpack and Express, this can be used as a template and starting point. 

## What's installed

The app had the following components installed (in prod mode):

- HtmlWebPackPlugin
- MiniCssExtractPlugin
- OptimizeCSSAssetsPlugin
- TerserPlugin
- WorkboxPlugin
- Sewrvice workers

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
