# MNIST_D_C_-3-MAJOR---
This project report presents the development of a neural network for MNIST digit classification. Using TensorFlow/Keras, the model achieved 97.5% test accuracy, trained efficiently over five epochs, and successfully recognized a custom handwritten digit image as “3.”
MNIST Digit Classification
📌 Project Overview
This project implements a Neural Network using TensorFlow/Keras to classify handwritten digits from the MNIST dataset. The model was trained, evaluated, and tested on a custom image, achieving high accuracy and reliable predictions.
🚀 Features
- Loads and preprocesses the MNIST dataset (60,000 training, 10,000 test images).
- Normalizes pixel values for faster convergence.
- Neural Network architecture:
- Flatten input layer (784 neurons).
- Two hidden Dense layers (128 and 64 neurons, ReLU activation).
- Output Dense layer (10 neurons, Softmax activation).
- Compiled with Adam optimizer and Sparse Categorical Crossentropy loss.
- Achieved 97.5% test accuracy.
- Successfully predicted a custom handwritten digit image (3-digit.PNG) as digit 3.
📊 Results
|  |  |  |  | 
|  |  |  |  | 
|  |  |  |  | 


🛠 Workflow
- Data Loading – MNIST dataset via keras.datasets.mnist.
- Preprocessing – Normalization of pixel values (0–1 range).
- Model Building – Sequential NN with Flatten, Dense, and Softmax layers.
- Training – 5 epochs, accuracy improved to 98.8%.
- Evaluation – Confusion matrix visualization, test accuracy 97.5%.
- Custom Prediction – Image preprocessing with OpenCV, correct classification.
📂 Files
- MNIST Digit Classification_Report.docx – Detailed project report.
- 3-digit.PNG – Custom handwritten digit image used for testing.
✅ Conclusion
The project exceeded expectations by achieving high accuracy and correctly classifying custom input, demonstrating the effectiveness of the chosen architecture and preprocessing steps.
