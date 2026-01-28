# Fashion-MNS-Image-Classification
## Google Collab Link: https://colab.research.google.com/drive/1_RWG8seubrDcpNYC5O35c-o02yNzknBW#scrollTo=SzJ9sUv-1HyN

### 1. What is the Fashion MNIST dataset?
Fashion MNIST is a collection of 70,000 grayscale images of clothing items like shirts, shoes, and bags.

-60,000 images are for training, 10,000 for testing.
-Each image is 28×28 pixels.
-It’s often used to teach and test image classification models.

### 2. Why do we normalize image pixel values before training?
Normalization means scaling pixel values from 0–255 to 0–1.
 -It helps the model learn faster and more efficiently.
 -Prevents large numbers from making training unstable.

 ### 3. List the layers used in the neural network and their functions.
 -Flatten layer → turns 2D images (28×28) into a 1D array so the model can process them.
 -Dense (fully connected) layer → learns patterns in the data.
 -Activation function (ReLU) → adds non-linearity so the model can learn complex relationships.
 -Output layer (Dense with softmax) → gives probabilities for each clothing class.
 -Optional: Dropout/BatchNormalization → improves accuracy and prevents overfitting.

 ### 4. What does an epoch mean in model training?
 An epoch is one full pass through the entire training dataset.
 -If you train for 10 epochs, the model sees each training image 10 times.

 ### 5. Compare the predicted label and actual label for the first test image.
 -Actual label: the real class of the image (e.g., “T-shirt/top”).
 -Predicted label: what the model thinks it is.
 -Example: If the model predicts “T-shirt/top” and the actual is also “T-shirt/top”, the prediction is correct.

 ### 6. What could be done to improve the model’s accuracy?
 -Use a Convolutional Neural Network (CNN) instead of a simple Dense network.
 -Add more layers or neurons.
 -Use data augmentation to increase variety in training images.
 -Use dropout or regularization to prevent overfitting.
 -Train for more epochs or adjust the learning rate.

