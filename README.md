# 🦷 Teeth Classification – Deep Learning Project  

## 📌 About the Project  
This project implements a **Convolutional Neural Network (CNN)** from scratch (no pretrained models) to classify dental images with **98–99% accuracy**.  
The model is trained on custom datasets with **training, validation, and testing splits**.  
Additional visualizations are provided for training/validation curves and **Grad-CAM** overlays for model interpretability.  

---

## 🚀 Features  
- **From-Scratch CNN Model** – Custom deep network, no pretrained weights.  
- **High Accuracy (98–99%)** – Achieved through balanced dataset, data augmentation, and careful tuning.  
- **Training & Validation Curves** – Visualize training loss and validation accuracy.  
- **Grad-CAM** – Highlight important image regions for classification decisions.  
- **Overlay Visualization** – Heatmap overlays on original images for interpretability.  

---

## 🛠️ Tech Stack  
- Python 3.10+  
- PyTorch  
- Torchvision  
- Matplotlib & Seaborn  
- OpenCV (for Grad-CAM overlays)  
- tqdm (for progress visualization)  

---

## 📂 Project Structure  
Teeth-Classification/
│── data/ # Dataset (train / val / test folders)
│── models/ # Saved model checkpoints
│── outputs/ # Grad-CAM and overlay visualizations
│── main.py # Training & evaluation script
│── requirements.txt # Dependencies
│── README.md # Project documentation



---

## ⚙️ Installation  
Clone the repository and install dependencies:  
```bash
git clone https://github.com/YourUsername/Teeth-Classification.git
cd Teeth-Classification
pip install -r requirements.txt


---

📊 Results & Visualizations

Training vs. Validation Accuracy/Loss plots

Grad-CAM heatmaps to show what the model focuses on

Overlayed visualizations for interpretability

<p align="center"> <img src="outputs/training_curve.png" width="400"/> <img src="outputs/gradcam_example.png" width="400"/> </p>



---
👨‍💻 Author

Developed by Mariam Ashraf – Passionate about AI & Healthcare
