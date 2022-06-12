# Machine Learning
This is the machine learning part of our capstone project. There are 2 Machine Learning features in our app:

### 1. Filtering Sexual/Inappropriate Image
We built a sexual image detection model to filter inappropriate contents from the app using MobileNetV2 with the input shape 224 x 224 x 3. We added a few layers such as flatten, dropout, and dense layers with ‘sigmoid’ activation as the output activation
### 2. Landmark Recognition (Especially Indonesian Landmark)
We built the landmark detection model (especially Indonesian landmark) using MobileNetV2 with the input shape 300 x 300 x 3, and added a few layers such as GlobalAveragePooling2D and dense layers with ‘softmax’ activation as the output activation.