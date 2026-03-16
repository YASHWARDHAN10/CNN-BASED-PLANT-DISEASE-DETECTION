# CNN-BASED-PLANT-DISEASE-DETECTION

Project Overview
This project addresses the critical challenge of agricultural productivity by leveraging Deep Learning to automate the detection of plant diseases. Specifically focused on potato crops using the PlantVillage dataset, the system identifies healthy leaves versus those affected by Early or Late Blight with high precision.

Unlike many implementations that rely on pre-trained models, this project features a custom-engineered Convolutional Neural Network (CNN) architecture built from scratch, optimized for accuracy and computational efficiency.

🚀 Key Features
1.Custom CNN Architecture: A refined 4-block Conv2D pipeline featuring Max-Pooling, Dropout layers (0.5) for overfitting prevention, and Dense layers.
2.High Accuracy: Engineered to achieve a performance benchmark of 85-95% accuracy on unseen validation data.
3.End-to-End Pipeline: Covers the entire lifecycle from data augmentation in Google Colab to model serialization (.h5).
4.Scalable Deployment: Backend powered by TensorFlow Serving, enabling seamless API integration for mobile and desktop applications.

🛠️ Tech Stack
1.Language: Python
2.Deep Learning Framework: TensorFlow / Keras
3.Data Processing: NumPy, Pandas, Matplotlib
4.Deployment: TensorFlow Serving, Postman (API Testing)

Environment: Google Colab (GPU accelerated)

Convolutional Blocks: 4 layers of Conv2D with ReLU activation and MaxPooling.

Regularization: Dropout layer to ensure robust generalization.

Classification: Dense layers culminating in a Softmax output for multi-class identification
