# CNN-on-Rice-Dataset
🌾 Rice Leaf Disease Classification using CNN
This project builds a Convolutional Neural Network (CNN) to classify rice leaf diseases from images. It utilizes image preprocessing, data augmentation, and deep learning to identify diseases affecting rice crops.

🧠 Project Overview
Objective: Classify rice leaf images into healthy or disease categories

Model: Custom-built CNN using TensorFlow/Keras

Dataset: Labeled images of rice leaves (from external dataset or local directory)

Frameworks Used:

TensorFlow / Keras

OpenCV (optional)

Matplotlib, Seaborn

🛠️ Workflow
Image Preprocessing:

Resizing images

Normalizing pixel values

Augmentation using Keras ImageDataGenerator

CNN Model Architecture:

Convolutional + MaxPooling layers

Dropout for regularization

Flatten + Dense layers for classification

Training & Validation:

Visualized with loss and accuracy plots

Evaluated with classification report and confusion matrix

🧪 Model Evaluation
Metric	Value (Example)
Training Accuracy	98.5%
Validation Accuracy	95.3%
Loss	Low/Stable
Confusion Matrix	✅ (Plotted)

Replace with actual values from your run.

🗂️ Folder Structure
objectivec
Copy
Edit
📦 CNN_RICE_TASK
 ┣ 📜 CNN_RICE_TASK.ipynb
 ┣ 📄 README.md
 ┗ 📂 rice_leaf_dataset/
     ┣ 📂 train/
     ┃ ┣ healthy/
     ┃ ┗ diseased/
     ┗ 📂 test/
        ┣ healthy/
        ┗ diseased/
📦 Installation
bash
Copy
Edit
pip install tensorflow keras numpy matplotlib seaborn
🚀 How to Run
Place dataset in appropriate folders (train/test).

Launch the notebook:

bash
Copy
Edit
jupyter notebook CNN_RICE_TASK.ipynb
Run all cells sequentially to train and evaluate the model.

📈 Outputs
Accuracy and loss graphs

Confusion matrix

Prediction results on test data

📚 Future Scope
Integrate with a mobile/web app for field use

Add more disease classes

Try transfer learning with VGG, ResNet, etc.

Use Grad-CAM for model explainability
