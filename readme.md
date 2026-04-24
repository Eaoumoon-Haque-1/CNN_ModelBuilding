# A Robust Deep Learning Framework with Explainable AI for Fruit Recognition under Real-World Variations

## 📌 Project Overview

This project presents a custom Convolutional Neural Network (CNN) based fruit recognition system designed to classify fruits under real-world environmental variations such as changes in lighting, shadows, pose variation, partial occlusion, and background disturbance.

Unlike many existing fruit datasets collected in highly controlled conditions, this project uses a more realistic dataset containing images captured under practical scenarios similar to supermarkets and fruit shops.

In addition to high classification performance, Explainable AI (XAI) techniques are integrated to visualize model decision-making and improve trustworthiness.

---

## 🎯 Objectives

- Build a deep learning model from scratch for multi-class fruit classification.
- Improve robustness against real-world image variations.
- Evaluate model performance using standard metrics.
- Integrate Explainable AI for prediction transparency.
- Demonstrate practical use cases such as automated checkout and smart weighing systems.

---

## 📂 Dataset Information

- **Dataset Name:** Fruit Recognition Dataset
- **Total Images:** 44,406 labeled images
- **Main Categories:** 15 fruit classes
- **Image Resolution:** 320 × 258 pixels
- **Color Space:** RGB

### Dataset Characteristics

Images were collected over 6 months under different practical scenarios:

- Natural light / Artificial light
- Shadow effects
- Pose variations
- Partial hand occlusion
- Different fruit quantities
- Similar color different fruits
- Different color same fruit categories
- Camera movement
- Realistic supermarket-like environment

---

## 🧠 Model Architecture

A custom CNN architecture was developed using PyTorch.

### Core Layers:

- Convolution Layers
- ReLU Activation
- Max Pooling
- Batch Normalization
- Dropout
- Fully Connected Layers
- Softmax Output

### Why Custom CNN?

Instead of using transfer learning, the model was built from scratch to demonstrate fundamental deep learning capability and full architectural control.

---

## ⚙️ Technologies Used

- Python
- PyTorch
- NumPy
- Pandas
- Matplotlib
- Scikit-learn
- OpenCV

---

## 📊 Training Strategy

- Data Augmentation
- Train / Validation Split
- Adam Optimizer
- Learning Rate Scheduler
- Cross Entropy Loss
- Best Model Weight Saving (`.pth`)

---

## 📈 Performance

| Metric | Result |
|--------|--------|
| Best Validation Accuracy | 99.07% |
| Best Validation Loss | 0.0307 |
| Epochs Trained | 10 |

---

## 🔍 Explainable AI (XAI)

Grad-CAM was used to generate heatmaps showing which image regions influenced the model prediction.

### Benefits:

- Increases model transparency
- Builds trust in predictions
- Helps detect model bias/errors
- Useful for real-world deployment

---

## 💼 Real-World Applications

- Smart supermarket fruit recognition
- Automated billing systems
- Intelligent weighing machines
- Retail inventory systems
- Self-checkout kiosks
- Agriculture sorting systems

---

## 📁 Project Files

```bash
CNN_StudentID.ipynb      # Full notebook implementation
best_model.pth          # Saved trained model weights
README.md               # Project documentation