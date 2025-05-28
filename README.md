# img-classifier-using-cifar10-data-set

🔍 Overview
The goal of this project is to:

Preprocess image data

Train an ANN to classify images

Evaluate performance using metrics like accuracy, precision, recall

Visualize correct and incorrect predictions

Save and reuse the trained model

🧠 Technologies Used
Python

TensorFlow / Keras

NumPy

Matplotlib

Seaborn

scikit-learn

 Model Workflow
Load dataset (e.g., Fashion MNIST)

Normalize and preprocess data

Build a sequential ANN model

Train using model.fit()

Predict using model.predict()

Evaluate with classification report and confusion matrix

Visualize misclassified images

Save the trained model for future use

📊 Evaluation Metrics
Accuracy: Overall correctness of the model

Precision & Recall: Per-class prediction quality

F1-score: Harmonic mean of precision and recall

Confusion Matrix: Shows class-wise prediction performance

📈 Sample Output
Accuracy: ~92%

Clear classification report

Misclassified image samples displayed with predictions

🛠 Future Improvements
 Try using CNN instead of ANN for better accuracy

 Use data augmentation to improve generalization

 Deploy using Streamlit or Flask

 Add custom image upload and prediction interface

