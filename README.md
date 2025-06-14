# 🧠 AI Medical Chatbot: Multimodal Clinical Query Analysis Using Groq-LLaMA Vision Models and Reinforcement-Inspired Evaluation

*AI Medical Chatbot* is an advanced healthcare assistant capable of handling both textual and image-based medical queries. It leverages Meta’s LLaMA Vision Models via Groq to analyze inputs and provide real-time diagnostic insights.

By integrating powerful multi-modal AI with a clean and responsive user interface, the system empowers medical students, researchers, and healthcare enthusiasts to explore clinical diagnostics in an interactive and intelligent way.

---

## 🚀 Features

- 📝 Accepts *text input* and *image uploads* for symptom diagnosis  
- 🧠 Powered by *Meta’s LLaMA 11B and 90B Vision Models* (via *Groq*)  
- ⚡ Provides *real-time* and intelligent medical query responses  
- 🚀 Built with *FastAPI* and served via a clean, responsive *frontend*  
- 🏷 Supports *image classification + diagnosis* for visible symptoms  
- 🎓 Ideal for *medical learning*, interactive demos, and research  

---

## 🛠 Tech Stack

*Backend:* Python, FastAPI  
*Frontend:* HTML, Tailwind CSS  
*AI Models:* LLaMA 11B & 90B (via Groq API)  
*Tools:* Virtualenv, Uvicorn  
*Image Preprocessing:* OpenCV  

---

## 📁 Project Structure

bash 
ai-medical-chatbot/
├── ai_medical_chatbot-main/
│ ├── app.py                 # FastAPI endpoints & routing
│ ├── main.py                # Entry point for FastAPI app
│ ├── templates/
│ │ └── index.html           # Main frontend UI
│ ├── static/                # CSS, JS, and media assets
│ └── ...                    # Additional support files
├── .venv/                   # Virtual environment
├── requirements.txt         # Python dependencies
└── README.md


---

## UI Preview image
![Screenshot 2025-06-14 105222](https://github.com/user-attachments/assets/f02bb414-e075-4a31-8184-a95164f9441f)

## 🔐 API Keys Required

This project uses *Groq’s LLaMA API* for multimodal image and text processing.

In main.py or app.py, insert your key:

python
GROQ_API_KEY = "YOUR_GROQ_API_KEY"



### ⚠ Important: Never upload your actual API key to GitHub. Use a .env file or environment variables for security.

---

## ⚙ Installation & Setup

1. *Clone the Repository*
    bash
    git clone https://github.com/Kushal0006/ai-medical-chatbot.git
    cd ai-medical-chatbot
    
    
2. *Create and Activate a Virtual Environment*
   bash
   python -m venv .venv
   .venv\Scripts\activate
   

3. *Install Dependencies*
   bash
   pip install -r requirements.txt
   
   
5. *Add Your API Key* : Insert your Groq API key in the appropriate file (main.py or use .env).
   
   
7. *Run the Application*
   bash
   uvicorn main:app --reload
   
   
9. *Open in Your Browser*
   bash
   Go to: http://127.0.0.1:8000
   
   
---

## 🙌 Contributors
This project was built as a collaborative academic effort by:

- Kushal S
- Kiran S Nair
- Asritha Y
- Prajwal V

---

## 📄 License
This project is for academic and demonstration purposes only.
Feel free to fork, improve, and contribute — just give credit where due!

---

## 🌐 Citation
Published in the *International Journal of Research Publication and Reviews (IJRPR)*

*📅 May 2025, Volume 6, Issue 5, Pages 1259–1263*
*ISSN: 2582-7421*

---

## 📬 Feedback

Feel free to open issues or submit pull requests.  
We welcome suggestions to improve functionality and UI/UX!
