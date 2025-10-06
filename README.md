# Gujarati Numeral OCR

*Handwritten Gujarati Digit Recognition using Ensemble Learning with Deep Learning-based Feature Fusion*

---

## 🧠 Overview

This project presents an Optical Character Recognition (OCR) system for handwritten **Gujarati numerals (0–9)**.
It employs deep learning architectures—**ResNet50, VGG16, VGG19, and InceptionV3**—for feature extraction, followed by **feature fusion** and classification using **XGBoost**.

The approach enhances recognition accuracy and robustness for Gujarati digits, contributing to multilingual OCR research and regional language digit recognition.

---

## ✨ Features

* Recognizes handwritten Gujarati numerals (0–9)
* Uses feature fusion from multiple CNN architectures
* High-accuracy classification via XGBoost
* Includes preprocessing (thresholding, inversion, normalization)
* Extensible to other Indian language numeral datasets

---

## 🧩 Methodology

**Workflow:**

```
Input Image → Preprocessing → Feature Extraction (VGG16, VGG19, ResNet50, InceptionV3)
→ Feature Fusion → XGBoost Classifier → Output (Predicted Digit)
```

<img width="621" height="535" alt="image" src="https://github.com/user-attachments/assets/32b191e1-29bb-4aef-bd6e-55032390d175" />


---

## 🖼️  Results
**Accuracy**
<img width="400" height="300" alt="image" src="https://github.com/user-attachments/assets/dd007d53-fcb0-40ed-a473-6490b1a87781" />
**Accuracy Vs Epoch**
<img width="300" height="300" alt="image" src="https://github.com/user-attachments/assets/7499877d-ee79-4362-99fd-c22a655e0b35" />
**Loss Vs Epoch**
<img width="300" height="300" alt="image" src="https://github.com/user-attachments/assets/4a8746a5-8258-4ffe-a6e1-b5042c6631d7" />
**Confusion Matrix** 
<img width="300" height="300" alt="image" src="https://github.com/user-attachments/assets/1b50fd96-3af4-445e-8cfd-9df62f153c40" />




---

## ⚙️ Installation & Usage

### Clone the repository

```bash
git clone https://github.com/yourusername/gujarati-numeral-ocr.git
cd gujarati-numeral-ocr
```

### Feature extraction

Run the vgg19, vgg16, inceptionv3 and resnet ipynb files.

### Feature fusion, Classification and Testing

Run classification.ipynb.

---

## 🧰 Tech Stack

* Python
* TensorFlow / Keras
* Scikit-learn
* XGBoost
* NumPy, Pandas, Matplotlib


---

## 📚 Research Paper

📄 **Paper Title:** *Handwritten Digit Recognition using Ensemble Learning with Deep Learning-based Feature Fusion*
📍*2024 8th International Conference on I-SMAC (IoT in Social, Mobile, Analytics and Cloud) (I-SMAC), Kirtipur, Nepal, 2024*

🔗 **Link:** https://ieeexplore.ieee.org/document/10714854/

---

## 🙌 Acknowledgements

Special thanks to **Parth Goel Sir**, **Hitwanshi Dalsania**, and **Arjav Ankoliya** for their valuable guidance and collaboration.

---

## 🏆 Citation

If you use this work, please cite:

```bibtex
@INPROCEEDINGS{10714854,
  author={Ankoliya, Arjav and Bhadani, Hetvi and Dalsania, Hitwanshi and Goel, Parth},
  booktitle={2024 8th International Conference on I-SMAC (IoT in Social, Mobile, Analytics and Cloud) (I-SMAC)}, 
  title={Handwritten Digit Recognition using Ensemble Learning with Deep Learning-based Feature Fusion}, 
  year={2024},
  volume={},
  number={},
  pages={1961-1966},
  keywords={Deep learning;Handwriting recognition;Analytical models;Accuracy;Writing;Linguistics;Feature extraction;Ensemble learning;Residual neural networks;Testing;Gujrati handwritten digits;classification;pre-trained CNN networks;ensemble learning;deep learning},
  doi={10.1109/I-SMAC61858.2024.10714854}}

```

---

## 📬 Contact

**Hetvi Bhadani**
📧 [hetvi.bhadani47000@gmail.com](mailto:hetvi.bhadani47000@gmail.com)
🔗 [LinkedIn](https://linkedin.com/in/yourprofile) | [GitHub](https://github.com/yourusername)

---
