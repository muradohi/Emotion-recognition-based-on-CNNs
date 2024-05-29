# Facial-Expression-Recognition-CNN

A Computer Vision assignment based on the Facial Expression Recognition (FER) challenge from 2013.

## Computer Vision Course

This code is optimized to run as a Jupyter Notebook and includes the following sections:

### Section 0: Library Imports
- This section imports all the necessary libraries.

### Section 1: Data Exploration and Preprocessing
- Ensure your data is either in your Google Drive or the local runtime.
- Modify the "path" variable to match your data location.
- This section will download and preprocess the data, including reshaping and normalizing it.
- Running all blocks, including the "Test Blocks", will create all necessary variables for the notebook.

### Section 2: Build Custom Model Functions
- Contains functions to create, compile, and test models.

### Section 3: Hyperparameter Tuning
- Contains code for model hyperparameter optimization.
- Run this section if you want to replicate the experiments.

### Section 4: Data Augmentation Tuning
- Contains code for data augmentation hyperparameter optimization.
- Run this section if you want to replicate the experiments.

### Section 5: Final Best Model Test
- Create and test final models.
- Test models on validation and test data.
- Includes k-fold cross-validation.

### Section 6: Filters Visualizations
- Visualize the filters learned by the final model.

### Section 7: Webcam Testing
- Code for video capture using a live webcam.
- Emotion recognition using a transformer model and a custom CNN model.
- Run section 7.1 to perform classification on the live video using transformer model.
- Run section 7.2 to perform classification on the live video using Final best model.

This structure is designed to guide you through the process of facial expression recognition, from data preprocessing to live video testing.
