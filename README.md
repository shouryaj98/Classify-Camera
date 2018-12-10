# Classify-Camera
This is a simple Android app to classify the content of an image. The image is clicked from the device and sent to the server, the server returns a json file containing a list of 3 most probable classes of object in the image and their corresponding probabilities. To test this app, [L1aoXingyu/deploy-pytorch-model](https://github.com/L1aoXingyu/deploy-pytorch-model) can be used to deploy the server on the localhost and a url for the localhost can be created using [ngrok](https://ngrok.com/)

This app makes use of [okhttp](http://square.github.io/okhttp/) library to connect to the server.
