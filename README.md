# This is for CI/CD pipline 

# medical-ai-assistant
 AI Medical Report Assistant

This project is an AI-powered medical assistant that helps users understand their medical reports in a simple and interactive way. Users can upload reports (PDF or TXT), ask questions, and get AI-generated insights such as health risks, explanations, and doctor recommendations.

====== Features======

 Upload medical reports (PDF / TXT)

 Store files securely in Azure Blob Storage

 AI-based report analysis using Azure OpenAI

 Chat interface for asking medical questions

 Detect health risks automatically

 Suggest specialist doctors

 Show nearby hospitals using Google Maps

 Clean medical-themed UI

 Disclaimer for safe usage

====== How It Works=====

Upload report

Store in Azure Blob Storage

Extract text

Ask questions

Azure OpenAI analyzes report

Show insights + doctor suggestions + map

===== Tech Stack =======

Python

Streamlit

Azure Blob Storage

Azure OpenAI

PyPDF2

===== Setup & Run===== (CMD Commands)
1️⃣ Clone the Repository
git clone https://github.com/YOUR_USERNAME/medical-ai-assistant.git
cd medical-ai-assistant
2️⃣ Create Virtual Environment
python -m venv venv
3️⃣ Activate Environment (Windows)
venv\Scripts\activate
4️⃣ Install Dependencies
pip install -r requirements.txt
5️⃣ Run the Application
streamlit run main.py
