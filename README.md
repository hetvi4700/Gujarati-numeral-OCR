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

🖼️ 
<img width="621" height="535" alt="image" src="https://github.com/user-attachments/assets/32b191e1-29bb-4aef-bd6e-55032390d175" />


---

## 🖼️  Results

<img width="906" height="340" alt="image" src="https://github.com/user-attachments/assets/dd007d53-fcb0-40ed-a473-6490b1a87781" />

🖼️ *Optional:* Include training accuracy/loss curve or confusion matrix
<img width="428" height="342" alt="image" src="https://github.com/user-attachments/assets/7499877d-ee79-4362-99fd-c22a655e0b35" />
<img width="435" height="319" alt="image" src="https://github.com/user-attachments/assets/4a8746a5-8258-4ffe-a6e1-b5042c6631d7" />
<img width="419" height="367" alt="image" src="https://github.com/user-attachments/assets/1b50fd96-3af4-445e-8cfd-9df62f153c40" />




---

## ⚙️ Installation & Usage

### Clone the repository

```bash
git clone https://github.com/yourusername/gujarati-numeral-ocr.git
cd gujarati-numeral-ocr
```

### Install dependencies

```bash
pip install -r requirements.txt
```

### Train the model

```bash
python train_model.py
```

### Test the model

```bash
python test_model.py
```

---

## 🧰 Tech Stack

* Python
* TensorFlow / Keras
* Scikit-learn
* XGBoost
* NumPy, Pandas, Matplotlib


---

## 📚 Research Paper

📄 **Paper Title:** *Gujarati Handwritten Digit Recognition using Ensemble Learning with Deep Learning-based Feature Fusion*
📍 *Accepted at the 8th International Conference on Electronics, Communication and Aerospace Technology (ICECA 2024)*

🔗 **Link:** [To be updated upon publication]

---

## 🙌 Acknowledgements

Special thanks to **Parth Goel Sir**, **Hitwanshi Dalsania**, and **Arjav Ankoliya** for their valuable guidance and collaboration.

---

## 🏆 Citation

If you use this work, please cite:

```bibtex
@inproceedings{bhadani2024gujarati,
  title={Gujarati Handwritten Digit Recognition using Ensemble Learning with Deep Learning-based Feature Fusion},
  author={Hetvi Bhadani and Hitwanshi Dalsania and Arjav Ankoliya and Parth Goel},
  booktitle={8th International Conference on Electronics, Communication and Aerospace Technology (ICECA 2024)},
  year={2024}
}
```

---

## 📬 Contact

**Hetvi Bhadani**
📧 [hetvi.bhadani47000@gmail.com](mailto:hetvi.bhadani47000@gmail.com)
🔗 [LinkedIn](https://linkedin.com/in/yourprofile) | [GitHub](https://github.com/yourusername)

---
