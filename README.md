# Final Project - CS677 - Xiaohan Jiang 

# Import Libraries
1. Import necessary libraries:
   - NumPy, Pandas for data handling
   - TensorFlow, Keras for model building and training
   - OpenCV, PIL for image processing
   - Matplotlib for data visualization
   - Scikit-learn for train-test splitting

# Data Preparation
2. Load dataset:
   - Extract image files from a zip or directory.
   - Process images using OpenCV or PIL.
   - Resize images to a uniform shape.
   - Convert labels to categorical format.

3. Split data:
   - Divide data into training, validation, and test sets using train_test_split.

# Model Building
4. Initialize a Sequential model:
   - Add convolutional layers (Conv2D) with ReLU activation.
   - Add pooling layers (MaxPool2D).
   - Add dropout layers for regularization.
   - Flatten the output.
   - Add dense layers for classification.

# Model Training
5. Compile the model:
   - Use a loss function suitable for classification (e.g., categorical crossentropy).
   - Choose an optimizer (e.g., Adam).
   - Monitor accuracy during training.

6. Train the model:
   - Use the `fit()` function on the training set.
   - Validate performance on the validation set.

# Model Evaluation
7. Evaluate the model:
   - Use the test set to calculate accuracy and loss.

8. Visualize results:
   - Plot training and validation loss and accuracy over epochs.

# Save and Load Model
9. Save the trained model to a file.
10. Optionally, load the model for reuse or further evaluation.

# Predictions
11. Use the trained model to make predictions on new data.
12. Visualize predictions and compare them with true labels.
