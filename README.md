# Watchmyface
This is a face landmark detection web application that is based on AI technologies made by TensorFlow.js 

## How to run 

```
Download and extract the project package as a .zip from the repository. 

Change directory to the project directory on the console and run - 

`npm install`
`npm start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

The page will reload when you make changes.\
You may also see any lint errors in the console.

`npm run build`

Builds the app for production to the `build` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.\
Your app is ready to be deployed!

```

## Tech stack
  1. Reactjs
  2. Javascript
  3. Tensorflowjs
  4. facemesh-api

## Visit 

https://watchmyface.netlify.app

## Temporary warning !!
 
The site works fine on any local machine. Due to the change of the facemesh package version that I used in this project, the scaledMash object is not returning data properly, the drawMesh() function is not being able to fillStyle the ctx. Thus the face landmark detection is not showing any lines. But if you inspect the site and check the console you will see the data is being fetched by reading the webcam and 'invisible'(colorless) landmarks are being plotted on the html canvas. The issue is being looked upon. We will resolve this soon.

## Motive behind this project

Getting introduced with tensorflow.js and playing with html canvas.

