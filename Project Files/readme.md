project executable file

# 📁 Project Files

This folder contains all essential files required to run and test the HematoVision project:

- `app.py` – Flask web application for classifying blood cell images.
- `train_model.py` – Script to train the CNN model using transfer learning (VGG16).
- `BloodCellClassifier.h5` – The trained model file used for prediction.
- `.jpg` images – Sample blood cell images for testing.
- `requirements.txt` – List of Python libraries to install before running the app.

Run `app.py` to launch the web interface.

# HematoVision: Advanced Blood Cell Classification Using Transfer Learning

## 🧠 Overview
HematoVision is a deep learning web app that classifies blood cell images into four categories using transfer learning. It helps in identifying blood disorders by analyzing microscopic images.

## 🔍 Classes
- Eosinophil
- Lymphocyte
- Monocyte
- Neutrophil

## 🛠️ Technologies Used
- Python, TensorFlow, Keras
- VGG16 Pre-trained Model
- Flask Web Framework
- HTML/CSS (for UI)

## 📁 Project Structure
Here's a complete and professional README.md you can paste into your GitHub project:


---

# HematoVision: Advanced Blood Cell Classification Using Transfer Learning

## 🧠 Overview
HematoVision is a deep learning web app that classifies blood cell images into four categories using transfer learning. It helps in identifying blood disorders by analyzing microscopic images.

## 🔍 Classes
- Eosinophil
- Lymphocyte
- Monocyte
- Neutrophil

## 🛠️ Technologies Used
- Python, TensorFlow, Keras
- VGG16 Pre-trained Model
- Flask Web Framework
- HTML/CSS (for UI)

## 📁 Project Structure

Project Files/ ├── app.py                  # Flask application ├── train_model.py          # Model training script ├── BloodCellClassifier.h5  # Saved Keras model ├── requirements.txt        # Python dependencies ├── templates/              # HTML templates ├── static/                 # Uploaded images

## 🚀 How to Run Locally

### 1. Clone the Repository
```bash
git clone https://github.com/ShaikSabeer31/HematoVision-Advanced-Blood-Cell-Classification-Using-Transfer-Learning.git
cd "Project Files"

2. Install Dependencies

pip install -r requirements.txt

3. Launch Flask App

python app.py

Then open your browser and go to http://127.0.0.1:5000 to upload an image and view predictions.

🧪 Model Performance

Accuracy: ~98%

Model: VGG16 with frozen base layers

Loss Function: Categorical Crossentropy


📷 Sample Demo

See the Video Demo/ folder for a walkthrough of the application.

📄 License

For academic and educational use only.

---

