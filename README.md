# 🩺 Pneumonia Detection & X-ray Analysis Dashboard

A **Flask-based AI web app** that empowers medical professionals to analyze chest X-rays using a CNN model. It provides diagnostic predictions, heatmaps, and lung damage visualization with a sleek, responsive interface.

---

## 🔍 Features

- 🤖 **AI Prediction**  
  Classifies chest X-rays as **Normal** or **Pneumonia** with a confidence score.

- 🌈 **Grad-CAM Heatmaps**  
  Highlights critical lung regions influencing the diagnosis.

- 🫁 **Lung Damage Localization**  
  Visual damage maps for a clear understanding of affected lung zones.

- 🧑‍⚕️ **Doctor Dashboard**  
  Manage patient records, view reports, and access analysis quickly.

- 📂 **Patient Management**  
  Upload X-rays, input patient details, and generate individual reports.

- 💻 **Responsive UI**  
  Built with Bootstrap and custom styling for a clean clinical look.

---

## 🧠 Model Details

- Format: `.h5` (Keras)
- Input Size: `224x224`
- Output: Binary Classification (`Normal` / `Pneumonia`)

---

## 🖼️ Screenshots

### 🧾 Report Page
![Report Page](assets/report_view.png)

### 🩺 Doctor’s Dashboard
![Dashboard View](assets/dashboard_view.png)

> _Make sure you save your screenshots as `report_view.png` and `dashboard_view.png` under an `/assets/` folder in your repository._

---

## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/yourusername/pneumonia-xray-dashboard.git
cd pneumonia-xray-dashboard
