# 🩺 Pneumonia Detection & X-ray Analysis Dashboard

This project is a **Flask-based AI web app** for analyzing chest X-rays using a pre-trained Convolutional Neural Network (CNN) model. It provides doctors with a comprehensive dashboard to:

- Predict if a patient has **Pneumonia**.
- Generate **Grad-CAM heatmaps** to visualize lung regions contributing to the diagnosis.
- Render **lung damage localization maps**.
- Upload and manage multiple patient X-rays and reports.

---

## 🔬 Features

- 🔍 **AI Prediction**: Binary classification (Pneumonia / Normal) with confidence score.
- 🌡 **Grad-CAM** Heatmap: Highlights regions of concern.
- 🫁 **Lung Damage Map**: Zone-wise intensity map for visual understanding.
- 📊 Patient-specific dashboards with vital info, reports, and analysis.
- 📁 Upload patient details, X-ray images, and supporting reports.
- 🖼️ Clean, responsive UI using Bootstrap and custom design.

---

## 🧠 Model

- Format: `.h5` (Keras model)
- Input size: `224x224`
- Output: Binary classification (`Normal` / `Pneumonia`)

---

## 🛠 Installation

### 1. Clone this repo

```bash
git clone https://github.com/yourusername/pneumonia-xray-dashboard.git
cd pneumonia-xray-dashboard


├── model/
│   └── xray_model.h5
├── static/
│   ├── uploads/
│   ├── heatmaps/
│   ├── lung_maps/
│   └── default-avatar.png
├── templates/
│   ├── index.html
│   ├── dashboard.html
│   ├── result.html
│   ├── report.html
│   └── Analysis.html
├── app.py
└── README.md


![Screenshot (199)](https://github.com/user-attachments/assets/0b03d6bf-5742-4adb-9de1-88f934a1121c)






