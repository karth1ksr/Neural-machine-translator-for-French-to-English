# GEN-AI : Neural-Machine-Translation-for-French-to-English

This project implements a neural machine translation (NMT) model using TensorFlow/Keras to translate French text into English. The model architecture includes embedding layers, bidirectional LSTM layers, repeat vector layer, and time-distributed dense layer with softmax activation.

#Project Overview
The aim of this project is to develop a deep learning model capable of accurately translating French text into English. The project includes the following key steps:

Data Acquisition: The dataset containing pairs of French and English sentences is sourced from "https://go.aws/38ECHUB".

Data Preprocessing: Clean and preprocess the text data, including tokenization and handling special characters.

Model Architecture: Implement a sequence-to-sequence model architecture for machine translation using TensorFlow/Keras.

Training: Train the translation model on the acquired dataset.

Evaluation: Evaluate the trained model's performance using metrics such as loss, accuracy, and BLEU score.

#Usage
To use the project:

Install the required dependencies by running pip install -r requirements.txt.

Run the provided code to preprocess the data, train the model, and evaluate its performance.

Adjust hyperparameters and experiment with model configurations to optimize performance.

#Results
Accuracy: The model achieved an accuracy of approximately 90% on the test dataset.

Translation Example: Input "Arrête de crier" (Stop shouting) translated accurately to "Stop shouting" in English.

Challenges: Limited hardware constrained training to 5000 words out of 160000.

Improvement: Training on full dataset and optimizing parameters could enhance accuracy.

Future Directions: Data augmentation and model refinement can improve performance.

#Conclusion
Despite limitations, the results demonstrate the potential of deep learning for machine translation tasks. Further refinement and optimization can enhance the model's accuracy and applicability in various domains.


#License
This project is licensed under the MIT License.
