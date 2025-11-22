# KMNIST Character Classification Project

## 📌 Project Overview
This project focuses on handwritten Japanese character recognition using the Kuzushiji-MNIST (KMNIST) dataset. We compare multiple models:
- Logistic Regression (Baseline)
- Simple CNN
- ResNet-like CNN
- Improved CNN with BatchNorm and Dropout
- Tuned Improved CNN

The goal is to understand the performance gap between linear classifiers and deep convolutional networks, and explore few-shot learning using Siamese networks.

## 🔗 Live Website
[View Blog on GitHub Pages](https://<your-username>.github.io/ECEN_Data_Mining_Project_Group10/)

## 📂 Repository Contents
- `index.html` : Main blog page
- `style.css` : Styling for the blog
- `script.js` : Theme toggle functionality
- `assets/` : Images and visualizations

## 📊 Key Results
- Logistic Regression: ~60% accuracy
- Tuned CNN: ~97% accuracy
- Siamese Network (One-shot): ~77.67% accuracy

## 🖼 Visuals Included
- Class distribution in training set
- PCA visualization of KMNIST
- Confusion matrices (Train & Test)
- Misclassified examples

## 📜 Report & Code Links
- [GitHub Repository](https://github.com/adimantamu/ECEN_Data_Mining_Project_Group10)
- [Overleaf Report](https://www.overleaf.com/project/69016ec3e24401e7e034fea3)

## 🚀 How to Run Locally
1. Clone the repository:
   ```bash
   git clone https://github.com/adimantamu/ECEN_Data_Mining_Project_Group10.git
   ```
2. Navigate to the project folder:
   ```bash
   cd ECEN_Data_Mining_Project_Group10
   ```
3. Open `index.html` in your browser.

## 👥 Authors
- Noureddin Lutfi (noorlutfe@tamu.edu)
- Aditya Rajiv (adiman@tamu.edu)
- Nuo Chen (nuochen@tamu.edu)
- Diviya Bhavaani M B (diviyabhavaani@tamu.edu)

## ✅ Future Work
- Data augmentation (shifts, rotations)
- Deeper residual networks
- Regularization strategies (label smoothing, mixup)

