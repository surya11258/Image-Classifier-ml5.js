# Image-Classifier-ml5.js
- ML5.js is a pretrained library in JS for image classifictaion https://ml5js.org/

- MobileNet is an efective convolutional Neural Network for Mobile Apps , https://arxiv.org/abs/1704.04861

- The ML5.js library gets all the dataset from : http://image-net.org/
ImageNet is a repository of around 15 million images gathered from google searches, Wikipedia, and other open sources.
    
# Working of ML5.js
ML5.js is a pretrained image classifier that runs in browser
It is an opensourced classfier developer by ML Developers,  It works on the basis of **Supervised Learning** 
- The Data set needs an input as an image
- The data set contains **Input**, image in (png, jpg) and its **label** in a .csv file

# The files 
index.html file , the main initialization file 
## Examples and Setup : https://ml5js.org/docs/getting-started.html

sketch.js , the main code for placing the image as input for classifier and steps of prediction

# Runnig in Browser
To run the image classifier in browser , open the index.html file in local-host
To enable prediction, replace the image in **puffin = createImg('path', imageReady);**   
*here puffin is a variable*
