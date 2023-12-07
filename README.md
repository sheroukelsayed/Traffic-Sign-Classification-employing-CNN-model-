# Traffic Sign Classification employing CNN model 
 the aim  is to have a working model that identifies traffic signs. The project and product team have decided to start with stop signs - is it a stop sign or not?
Certainly, here are concise notes without the code:

1. Mounting Google Drive:
   - Google Drive is mounted to access and store files.

2. Folder Paths:
   - Paths for 'stop' and 'non-stop' traffic sign images are defined.

3. Libraries:
   - Libraries such as os, csv, Pillow, and pandas are imported for file manipulation, CSV operations, image processing, and data analysis.

4. CSV Files:
   - Paths for CSV files to store image information are defined.

5. Image Reading and DataFrame Creation:
   - A function is used to read and preprocess images, creating DataFrames for 'stop' and 'non-stop' images.

6. Train-Test Split:
   - The data is split into training and testing sets using the `train_test_split` function.

7.Concatenate DataFrames:
   - DataFrames for training and testing sets for both 'stop' and 'non-stop' images are concatenated.

8. Shuffling DataFrames:
   - Training and test DataFrames are shuffled for randomness.

9. Load and Preprocess Images:
   - Training and validation images are loaded and preprocessed for the CNN model.

10. Define and Compile CNN Model:
    - A simple CNN model is defined using Keras and compiled.

11. Train CNN Model:
    - The CNN model is trained on the training data.

12. Save Trained Model:
    - The trained model is saved for later use.

13.Load Pre-trained VGG16 Model:
    - VGG16 model pre-trained on ImageNet data is loaded.

14.Freeze Pre-trained Layers and Add Custom Classifier:
    - Pre-trained layers are frozen, and a custom classifier is added on top of the VGG16 model

15 Compile and Train VGG16 Model:
    - The VGG16 model is compiled and trained.

16.Save Trained VGG16 Model:
    - The trained VGG16 model is saved.

17.Load Pre-trained ResNet50 Model:
    - ResNet50 model pre-trained on ImageNet data is loaded.

18Freeze Pre-trained Layers and Add Custom Classifier:
    - Pre-trained layers are frozen, and a custom classifier is added on top of the ResNet50 model.

19.Compile and Train ResNet50 Model:
    - The ResNet50 model is compiled and trained.

20. Save Trained ResNet50 Model:
    - The trained ResNet50 model is saved.

21. Image Prediction:
    - Test images are loaded and predictions are made using the trained models, displaying predictions and probabilities.
