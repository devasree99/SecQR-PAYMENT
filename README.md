# SecQR-PAYMENT
Step 1: SecQR CODE validator
The QR code validator is set up to perform secure payments by avoiding trojans in the website and other malwares. This can be implemented through html and css languages.
The qr code is much more safe and secure with the most significant use of security.The qr code can be implemented by scanning the frame.png file.
Step 2:Face Detection Application
The face detection application is the platform where the website can be safer without any trojans.The face detection is used with html,css and javascript.

Face detection is one of the most common applications of Artificial Intelligence. The use of Facial detection has increased in the last couple of years.

Face-api.js has brought a JavaScript API for face detection and face recognition in the browser implemented on top of the tensorflow.js core API

In this tutorial, we will build the face recognition app that will work in the Browser. From the face, we will predict the Emotion, Gender, and age.

1.Create a folder called face-recognition
2.download the face-api.min.js
    Download the face-api.min.js code from the following URL and paste it inside the js/face-api.min.js file.
    https://raw.githubusercontent.com/karkranikhil/face-recognition-using-js/master/js/face-api.min.js

3.download the modal files
    Download the files from the following URL and placed them inside the models folder.
    https://github.com/karkranikhil/face-recognition-using-js/tree/master/models
4.Let's built the index.html file.
    In index.html file we importing the style.css for styles, face-api.min.js for processing the model data and extracting the features and main.js where we will write our logic.
Inside the body tag we are creating a video tag to get the face, result-container for showing the emotion, gender, and age.
Place the below code inside the index.html file
Upload the html code to index.html

5.Let's built the main.js file.
    Inside the main.js file we are using promise.all to load the models to the face API. once the promise is resolved then we are calling the startVideo method that starts the streaming. Below are the methods used for this demo

faceapi.detectSingleFace method - detectSingleFace utilize the SSD Mobilenet V1 Face Detector. You can specify the face detector by passing the corresponding options object. To detect the multiple faces replace the detectSingleFace with detectAllFaces

withFaceLandmarks method - It is used for Detecting 68 Face Landmark Points

withFaceExpressions method - This method Detect all faces in an image + recognize facial expressions of each face and return the array

withAgeAndGendermethod - This method Detect all faces in an image + estimate age and recognize gender of each face and return the array
Upload the main code to main.js
6.Let's Add the style to the app.
    Upload style code to the css file.
    
7.Let's run the app by the live server or http-server

Step 3 : PAYMENT WEBSITE
    1.Create a folder payment in which the images, css and html files are included.
    2.Upload the following files in the payment folder
        index.html
        style.css
        logo.png
    3.Poppins files are imported into the file using url.
    4.Run the code in the website using php connect.
    
 so happy coding guys!!..
 
