# Machine Learning
This is the machine learning part of our capstone project. There are 2 Machine Learning features in our app:

### 1. Filtering Sexual/Inappropriate Image
We built a sexual image detection model to filter inappropriate contents from the app. The dataset was obtained from Kaggle [https://www.kaggle.com/datasets/drakedtrex/my-nsfw-dataset](url). Transfer learning MobileNetV2 with the input shape 224 x 224 x 3 was used and a few layers such as flatten, dropout, and dense layers with ‘sigmoid’ activation as the output activation were added. The dataset consists of 1676 images divided into 1400 train images and 200 test images. The train images were further divided into NSFW and SFW. The idea behind this model is to classify whether the images uploaded were sexual or not. 
### 2. Landmark Recognition (Especially Indonesian Landmark)
We built the landmark detection model (especially Indonesian landmark) using MobileNetV2 with the input shape 300 x 300 x 3, and added a few layers such as GlobalAveragePooling2D and dense layers with ‘softmax’ activation as the output activation.
