# Sign Language Recognition

This project is an **American Sign Language (ASL) recognition system** that uses **Convolutional Neural Networks (CNNs)** to translate ASL signs into text in real time.

## 📌 Features
- Real-time ASL recognition from video input.
- Uses a **self-made dataset** for training.
- Implements **CNN-based deep learning model**.
- Provides accurate text translation for ASL gestures.

## 📂 Project Structure
```
proj/
├── .ipynb_checkpoints/   # Jupyter notebook checkpoints
├── data/                 # Self-made ASL dataset
├── CNN_Model.ipynb       # CNN model implementation
├── app.ipynb             # ASL recognition application
├── collect_data.ipynb    # Script to collect ASL data
├── model.h5              # Trained model weights
├── model.json            # Model architecture
├── preprocessing of data.ipynb  # Data preprocessing notebook
├── testing.ipynb         # Model testing notebookpt
└── README.md             # Project documentation
```

## 📊 Dataset
The dataset consists of **self-collected ASL gesture images**. You can expand it by adding more labeled data.

## 🧠 Model
The system employs a **CNN-based architecture** for ASL classification. The model is trained using **TensorFlow/Keras or PyTorch** (whichever you are using).

## 🔥 Future Improvements
- Improve model accuracy with a larger dataset.
- Support for dynamic ASL gestures.

### 🔗 Project Link
[GitHub Repository](https://github.com/viniskykumar/Sign_Language_Recognition)
