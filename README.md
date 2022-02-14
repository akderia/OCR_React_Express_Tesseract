# OCR App Using React, Express & Tesseract

A simple OCR (optical character recognition) application using React, Express & Tesseract. Supported packages: Semantic UI React & React Webcam. It can be used to recognize characters from uploaded image or captured photo. 



#

- __Try this project__:

    1. __Clone this repo__

        ```bash
        $ git clone https://github.com/LintangWisesa/OCR_React_Express_Tesseract
        ```

    2. __Setup Node.js server__

        Install packages & run the server
        ```bash
        $ cd OCR_React_Express_Tesseract
        $ cd nodejs_ocr
        $ npm i
        $ node app
        ```
        It will run at `localhost:5000`. If you have nodemon or pm2, you can also use them to run this server.
        ```bash
        $ nodemon app
        ```
        or
        ```bash
        $ pm2 start app.js
        ```


    3. __Setup React app__

        Install packages & run the app:
        ```bash
        $ cd OCR_React_Express_Tesseract
        $ cd react_ocr_webcam
        $ npm i
        $ npm start
        ```
        It will run at `localhost:3000`. Try to upload an image or capture a photo by webcam to see the result.
#

- __Preview__

  Home Page

  ![./img/Home.png](./img/home.png)

  OCR for uploaded image
  
  ![./img/imageupload.png](./img/imageupload.png)

  OCR for captured photo
  
  ![./img/photocapture.png](./img/photocapture.png)

<hr>



<br>
