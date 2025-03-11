# Image-Classification
-------------------------------------------
# 🐶🐱 Dog vs Cat Image Classification using CNN (TensorFlow)
This project is a deep learning-based image classification model that categorizes images into two classes: Dog and Cat using Convolutional Neural Networks (CNNs) with TensorFlow.
This is a Basic for image Classification for bginner,for complex use case there are many steps to follow to preprocess and train Model.
 
### 📌 Features
* Built using TensorFlow and Keras.
* Uses CNN for feature extraction and classification.
* Trained on a dataset of labeled images of dogs and cats.
* Data augmentation for better generalization.
* Achieves high accuracy in classifying images.

### Steps 
1. Installation of require library <br />
    ```pip install tensorflow os numpy matplotlib ```

2. Load Dataset
3. Scale your Data
4. Split for training and testing
5. Build a Deep Learning Model <br />
    *Model Architecture <br />
       -Convolutional Layers for feature extraction <br />
       -Max Pooling for dimensionality reduction <br />
       -Fully Connected (Dense) Layers for classification <br />
6. Train Model <br/>
       ### Summary of Model <br/>

| Layer (type) |Output Shape  |  Param #  |
| :---         |     :---:      |          ---: |
| conv2d_9 (Conv2D)   | (None, 254, 254, 32)     |  896     |
| max_pooling2d_6 (MaxPooling2D)     | (None, 127, 127, 32)      | 0      |
| conv2d_10 (Conv2D)   | (None, 125, 125, 16)     |  4624     |
| max_pooling2d_7 (MaxPooling2D)     |(None, 62, 62, 16)      | 0      |
| conv2d_11 (Conv2D)    | (None, 60, 60, 8)      |  1160     |
| max_pooling2d_8 (MaxPooling2D)     | (None, 30, 30, 8)      | 0      |
| dense_8 (Dense)    | (None, 256)      |  1,843,456   |
| dense_9 (Dense)       | (None, 1)     | 257      |

 Total params: 1,850,393 (7.06 MB)
 Trainable params: 1,850,393 (7.06 MB)
 Non-trainable params: 0 (0.00 B)

   
8. Test your Model
9. Saveing Model<br/>
    `from tensorflow.keras.models import load_model`
------------------------------------------------------------
