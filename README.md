# Digit-Classifier
A web-based browser model using tensorflow.js. 
We create a naive Digit Recognizer using the [MNIST DATASET](http://yann.lecun.com/exdb/mnist/) .We train the model in web server using webGL

# System Requirements
- [web Server for Chrome](https://chrome.google.com/webstore/detail/web-server-for-chrome/ofhbbkphhbklhfoeikjpcbhemlocgigb?hl=en)
- [Brackets](http://brackets.io/)
- [tensorflow.js](https://www.tensorflow.org/js)
# Installation 
    $ git clone https://github.com/adeepH/Digit-Classifier
    $ cd Digit-Classifier/

## Abstract 
`script.js` is the JavaScript file that contains the architecture of the model.
- The model uses the following architecture as specified in  `architecture.png`.
We create a folder containing the `data.js` , `script.js`, `mnist.html`.
- Launch the [web extension for chrome](https://chrome.google.com/webstore/detail/web-server-for-chrome/ofhbbkphhbklhfoeikjpcbhemlocgigb?hl=en) and choose the folder containing all of the required files.
- Launch the web URL (http://127.0.0.1:8887) and wait for the model to train.
- After completing the training you get an alert/pop-up message , test the model.
- [canvas](https://www.w3schools.com/html/html5_canvas.asp) is used.
