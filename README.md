# 🩺 Pneumonia Detection & X-ray Analysis Dashboard

This project is a **Flask-based AI web app** for analyzing chest X-rays using a pre-trained Convolutional Neural Network (CNN) model. It provides doctors with a comprehensive dashboard to:

- Predict if a patient has **Pneumonia**.
- Generate **Grad-CAM heatmaps** to visualize lung regions contributing to the diagnosis.
- Render **lung damage localization maps**.
- Upload and manage multiple patient X-rays and reports.

---

## 🔬 Features

- 🔍 **AI Prediction**: Binary classification (Pneumonia / Normal) with confidence score.
- 🌡 **Grad-CAM Heatmap**: Highlights regions of concern.
- 🫁 **Lung Damage Map**: Zone-wise intensity visualization.
- 📊 Patient-specific dashboards with vital info, reports, and analysis.
- 📁 Upload patient details, X-ray images, and supporting reports.
- 🖼️ Clean, responsive UI using Bootstrap and custom styling.

---

## 🧠 Model

- **Format**: `.h5` (Keras model)
- **Input size**: `224x224`
- **Output**: Binary classification (`Normal` / `Pneumonia`)

---

## 📁 Project Folder Structure

<h3>📁 Project Folder Structure</h3>

<pre>
pneumonia-xray-dashboard/
│
├── app.py                          # Main Flask application
├── model/
│   └── xray_model.h5               # Pre-trained Keras CNN model
│
├── static/
│   ├── uploads/                    # Uploaded X-ray images
│   ├── heatmaps/                   # Grad-CAM heatmap outputs
│   ├── lung_maps/                  # Lung damage visualizations
│   └── default-avatar.png          # Default avatar for patient profile
│
├── templates/
│   ├── index.html                  # Upload page
│   ├── dashboard.html              # Doctor's dashboard
│   ├── result.html                 # AI result view
│   ├── report.html                 # Detailed report
│   └── Analysis.html               # Additional visual analysis
│
├── assets/
│   ├── Screenshot (190).png        # AI report screenshot
│   └── Screenshot (199).png        # Dashboard screenshot
│
└── README.md
</pre>

---

## 🖼️ Interface Screenshots

### 🔹 AI Result Analysis
![AI Result](assets/Screenshot%20(190).png)

### 🔹 Doctor Dashboard
![Dashboard](assets/Screenshot%20(199).png)

---

## 🚀 Setup Instructions

```bash
# 1. Clone the repository
git clone https://github.com/yourusername/pneumonia-xray-dashboard.git
cd pneumonia-xray-dashboard

# 2. (Optional) Create a virtual environment
python -m venv venv
source venv/bin/activate  # or venv\Scripts\activate on Windows

# 3. Install dependencies
pip install -r requirements.txt

# 4. Run the app
python app.py
