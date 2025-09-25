*Google Lens Ditto – Powered by Gemini API*

This project is a Google Lens–like clone built using the Gemini API, designed to process images, extract insights, and provide contextual search results. It replicates the core idea of “point, capture, and understand” by combining computer vision with LLM-powered reasoning.

🚀 Features

🔍 Image Understanding – Upload an image and let the Gemini API describe it.

🌐 Contextual Search – Extracts relevant keywords/entities from the image for search.

🧠 Gemini-Powered Reasoning – Provides intelligent, contextual insights beyond simple labeling.

📊 Multi-Modal Support – Handles both text + image inputs.

⚡ Fast & Lightweight – Minimal setup, runs directly from notebook or API calls.

🛠️ Tech Stack

Gemini API (for vision + text processing)

Python (main driver)

Flask / FastAPI (optional) – for exposing as a backend service

Streamlit (optional) – for quick UI prototyping

📂 Project Structure
Google_Lens_Ditto/
│── Google_lens_ditto.ipynb   # Main notebook (development + testing)
│── requirements.txt          # Dependencies
│── README.md                 # Project documentation
│── /assets                   # Sample input images & outputs

🔧 Installation

Clone the repo

git clone https://github.com/Nivac05/Google-lens-ditto.git
cd google-lens-ditto


Create virtual environment & install requirements

pip install -r requirements.txt


Set up Gemini API key

Get an API key from Google AI Studio

Create a .env file and add:

GEMINI_API_KEY=your_api_key_here


![Python](https://img.shields.io/badge/Python-3.9-blue) 
![Gemini API](https://img.shields.io/badge/Gemini-API-orange)
![Status](https://img.shields.io/badge/Status-Active-brightgreen)
![License](https://img.shields.io/badge/License-MIT-purple)

<p align="center">
  <img src="assets/banner.png" width="600"/>
</p>


▶️ Usage
Run from Jupyter Notebook

Open Google_lens_ditto.ipynb

Upload an image

Run the cells → Get description + search insights

Run as Script
python app.py


(If you convert the notebook into a Flask/Streamlit app)

📸 Example

Input: 🖼️ A photo of a wristwatch
Output (Gemini API):

Description: "A luxury wristwatch with black leather strap and silver dial"

Entities extracted: watch, leather strap, luxury

Suggested search: “Best luxury watches with black leather strap”

📊 Future Enhancements

🔗 Integrate with Google Shopping API for direct product search

🧭 Add object detection for multi-object images

🖼️ Include image similarity search (like Lens reverse search)

📱 Deploy as a mobile app (React Native + Capacitor)


✨ Contributors

👨‍💻 Cavin Chandran
💡 Built as part of BAEon Internship (Gemini API projects)
