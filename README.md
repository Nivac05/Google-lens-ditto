<h1 align="center">📸 Google Lens Ditto – Powered by Gemini API</h1>

<p align="center">
   <i>A modern Google Lens–like clone built using the <b>Gemini API</b>, designed to process images, extract insights, and provide contextual search results.  
   Built as an add-on for <b>fashion apps</b> – "Point, Capture, and Understand".</i>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.9-blue?style=for-the-badge&logo=python" />
  <img src="https://img.shields.io/badge/Gemini-API-orange?style=for-the-badge&logo=google" />
  <img src="https://img.shields.io/badge/Status-Active-brightgreen?style=for-the-badge" />

</p>

---

## 🚀 Features

* 🔍 **Image Understanding** – Upload an image and let Gemini describe it
* 🌐 **Contextual Search** – Extracts keywords/entities for search
* 🧠 **Gemini-Powered Reasoning** – Goes beyond labeling → contextual insights
* 📊 **Multi-Modal Support** – Handles **image + text input**
* ⚡ **Fast & Lightweight** – Minimal setup, runs directly from notebook or script

---

## 🛠️ Tech Stack

* 🖼️ **Gemini API** – Vision + Text processing
* 🐍 **Python** – Core development
* 📓 **Jupyter Notebook** – Development & testing
* 🌐 *(Optional)* Flask / Streamlit – Deployment UI

---

## 📂 Project Structure

<details>
  <summary>Click to expand</summary>

```bash
Google_Lens_Ditto/
├── Google_lens_ditto.ipynb   # Main notebook (development + testing)
├── requirements.txt          # Dependencies
├── README.md                 # Project documentation
└── /assets                   # Sample input images & outputs
```

</details>

---

## ⚙️ Installation

```bash
# Clone the repo
git clone https://github.com/Nivac05/Google-lens-ditto.git
cd google-lens-ditto

# Install requirements
pip install -r requirements.txt
```

🔑 **Set up Gemini API key**

1. Get an API key from [Google AI Studio](https://aistudio.google.com/)
2. Create a `.env` file and add:

   ```
   GEMINI_API_KEY=your_api_key_here
   ```

---

## ▶️ Usage

### 🖥️ Run from Jupyter Notebook

1. Open **Google_lens_ditto.ipynb**
2. Upload an image
3. Run cells → Get **description + insights**

<p align="center">
   <img width="452" height="736" src="https://github.com/user-attachments/assets/6ed40454-1c02-4456-a35d-7601775f9759" />
</p>

<p align="center">
   <img width="608" height="256" src="https://github.com/user-attachments/assets/e0c59986-7fca-4ac1-9b42-b3e3dd415082" />
</p>

<p align="center">
   <img width="904" height="498" src="https://github.com/user-attachments/assets/5d90a217-7301-448d-b162-4bbded4ef284" />
</p>

<p align="center">
   <img width="1186" height="381" src="https://github.com/user-attachments/assets/187a9635-dda9-4e89-b38b-9ed79ca7a7f4" />
</p>

<p align="center">
   <img width="395" height="142" src="https://github.com/user-attachments/assets/a59835f8-74ed-4888-99b2-f028bc091741" />
</p>

---

### 🖥️ Run as Script

```bash
python app.py
```

---

## 🛣️ Future Enhancements

* 🔗 Integrate with **Google Shopping API**
* 🧭 Add **multi-object detection**
* 🖼️ Include **reverse image similarity search**
* 📱 Deploy as a **mobile app (React Native + Capacitor)**

---

## ✨ Contributors

👨‍💻 **Cavin Chandran**
💡 Built as part of **BAEon Internship (Gemini API projects)**

---





