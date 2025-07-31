# AI-Powered Deepfake Detection System

This project uses a Convolutional Neural Network (CNN) to detect deepfake images and classify them as real or fake.

## 🎯 Objective
Detect tampered or deepfake images using computer vision and deep learning techniques.
## 🛠️ Tools & Technologies
- Python  
- TensorFlow / Keras  
- OpenCV  
- CNN (Convolutional Neural Network)  
- Jupyter Notebook

## 📂 Project Structure
```
deepfake-detection-system/
├── deepfake_detection.ipynb     # Main notebook
├── sample.jpg                   # Test image (optional)
└── README.md                    # Project documentation
```

## 🚀 How to Run
1. Clone this repo or download it as ZIP
2. Open `deepfake_detection.ipynb` in Jupyter Notebook or Google Colab
3. Ensure your dataset is organized as:
   ```
   dataset/
   ├── train/
   │   ├── real/
   │   └── fake/
   └── test/
       ├── real/
       └── fake/
   ```
4. Run the notebook cell by cell to train and test

## 📊 Model Details
- Architecture: 2 Conv Layers → Flatten → Dense
- Loss Function: Binary Crossentropy
- Optimizer: Adam
- Evaluation: Accuracy over epochs

