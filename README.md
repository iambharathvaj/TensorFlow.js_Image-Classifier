# TensorFlow.js_Image-Classifier
                          Image Classification using MobileNet model - ML Project #1
                          
In this project, I have built a simple, custom image classifier that can be trained on your web browser itself (really?). Yeah, you read it right! It is as simple as that. It is built using TensorFlow.js, a machine learning library for JavaScript and it is running on top of the pre-trained model called MobileNet by using the technique called "Transfer Learning".

# Usage
1. To test this code, open the "index.html" file in your web browser and allow the webcam access to your browser.

2. Once the webcam is up and running, it will capture the first 30 frames (practical assumption) and will add the activations to the "No Action" (neutral state) class in a k-Nearest Neighbour classifier.

3. Then, show any object/gesture to the webcam. Simultaneously, click on the appropriate "Add" button which specifies the class that the input image belongs to (Here, I have considered A, B and C for simplicity). Each time you click one of the "Add" buttons, one image will be added to that class as a training example. Do the same for different objects with different classes.

4. While you perform this series of activities, eventually, the models learns how to classify and it makes predictions on the webcam images coming in and shows the results (classification as well as the highest probability) in real-time.




