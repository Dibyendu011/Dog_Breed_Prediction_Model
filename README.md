Model Overview --

This repository hosts a deep learning model for dog breed classification, trained via transfer learning on a curated subset of the Stanford Dogs Dataset (120 breeds). The model leverages EfficientNetV2B0 (tf.keras.applications) with hyperparameter tuning for optimized performance.

Dataset & Setup --

Dataset Source: [Stanford Dogs Dataset](http://vision.stanford.edu/aditya86/ImageNetDogs/)

Storage Recommendation: Upload datasets to a dedicated Google Drive folder to minimize local storage usage and enable seamless access via Google Colab.

Training Scope --

Due to computational constraints, the model was trained on 10% of the training data (stratified across classes) and evaluated on 58% of the test data. Despite limited training, it demonstrates robust performance. For full-scale training/prediction, please follow the commented lines in the source code.
