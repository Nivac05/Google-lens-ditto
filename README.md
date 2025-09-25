## *Google Lens Ditto – Powered by Gemini API*

This project is a Google Lens–like clone built using the Gemini API, designed to process images, extract insights, and provide contextual search results. It replicates the core idea of “point, capture, and understand” by combining computer vision with LLM-powered reasoning, this is created to serve as an addon for fashion aps.

🚀 Features

🔍 Image Understanding – Upload an image and let the Gemini API describe it.

🌐 Contextual Search – Extracts relevant keywords/entities from the image for search.

🧠 Gemini-Powered Reasoning – Provides intelligent, contextual insights beyond simple labeling.

📊 Multi-Modal Support – Handles both text + image inputs.

⚡ Fast & Lightweight – Minimal setup, runs directly from notebook or API calls.

🛠️ Tech Stack

Gemini API (for vision + text processing)

Python (main driver)


## 📂 Project Structure

```bash
Google_Lens_Ditto/
├── Google_lens_ditto.ipynb   # Main notebook (development + testing)
├── requirements.txt          # Dependencies
├── README.md                 # Project documentation
└── /assets                   # Sample input images & outputs
```

# Installation

Clone the repo

git clone https://github.com/Nivac05/Google-lens-ditto.git
cd google-lens-ditto


Create virtual environment & install requirements

pip install -r requirements.txt


Set up Gemini API key

Get an API key from Google AI Studio

Create a .env file and add:

GEMINI_API_KEY=your_api_key_here



▶️ Usage
Run from Jupyter Notebook

Open Google_lens_ditto.ipynb

Upload an image

<img width="452" height="736" alt="image" src="https://github.com/user-attachments/assets/6ed40454-1c02-4456-a35d-7601775f9759" />



Run the cells → Get description + search insights


<img width="608" height="256" alt="image" src="https://github.com/user-attachments/assets/e0c59986-7fca-4ac1-9b42-b3e3dd415082" />
<img width="904" height="498" alt="image" src="https://github.com/user-attachments/assets/5d90a217-7301-448d-b162-4bbded4ef284" />
<img width="1186" height="381" alt="image" src="https://github.com/user-attachments/assets/187a9635-dda9-4e89-b38b-9ed79ca7a7f4" />
<img width="395" height="142" alt="image" src="https://github.com/user-attachments/assets/a59835f8-74ed-4888-99b2-f028bc091741" />



Run as Script
python app.py



📊 Future Enhancements

🔗 Integrate with Google Shopping API for direct product search

🧭 Add object detection for multi-object images

🖼️ Include image similarity search (like Lens reverse search)

📱 Deploy as a mobile app (React Native + Capacitor)


✨ Contributors

👨‍💻 Cavin Chandran
💡 Built as part of BAEon Internship (Gemini API projects)

![Python](https://img.shields.io/badge/Python-3.9-blue) 
![Gemini API](https://img.shields.io/badge/Gemini-API-orange)
![Status](https://img.shields.io/badge/Status-Active-brightgreen)


