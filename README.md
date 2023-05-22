# captcha-recognizer
_Recognition of numbers inside CAPTCHA using CNN neural network model. (using tensorflow library)_<br>
We have 101 different captchas and there are 10 different types of each captcha. each image has 5 digits, which is divided into 5 equal parts, and finally the model is trained on 5050 digit images.<br><br>
So, we have trained the model on the numbers, not on the entire captcha image.<br><br>
In the last layer of the model, softmax is used due to the existence of several classes for each data, and this gives us the probability of occurrence of each class.<br><br>
To evaluate the model, sparse categorical crossentropy is used and a validation set is given to the model during training to calculate its loss and accuracy.
Finally, the accuracy of the model was 99% on the training data and 96% on the test data.
