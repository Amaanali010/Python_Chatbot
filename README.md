🤖 Groq AI Chatbot

A modern AI-powered chatbot built using Python, Streamlit, and Groq API. This application allows users to interact with an AI assistant and receive intelligent responses in real time.

🚀 Features
Modern and user-friendly chatbot interface.
AI-powered conversations using Groq API.
Real-time AI responses.
Chat history management.
Clear chat functionality.
Secure API key management using Streamlit Secrets.
Free online deployment using Streamlit Community Cloud.
🛠️ Technologies Used
Python
Streamlit
Groq API
Llama 3.3 70B Versatile
Git and GitHub
📂 Project Structure
text
groq-ai-chatbot/
│
├── app.py
├── requirements.txt
├── README.md
├── .gitignore
│
└── .streamlit/
    └── secrets.toml

⚙️ Installation and Setup
1. Clone the repository
bash
git clone https://github.com/YOUR_USERNAME/groq-ai-chatbot.git

2. Navigate to the project folder
bash
cd groq-ai-chatbot

3. Create a virtual environment
bash
python -m venv venv


Activate the environment:

Windows:

bash
venv\Scripts\activate


Mac/Linux:

bash
source venv/bin/activate

4. Install dependencies
bash
pip install -r requirements.txt

5. Configure Groq API Key

Create a .streamlit folder and add a file named secrets.toml.

Add your Groq API key:

toml
GROQ_API_KEY = "your_groq_api_key_here"


Get your API key from:

https://console.groq.com/

Important: Never upload your API key or secrets.toml file to GitHub.

6. Run the application
bash
streamlit run app.py


The application will open in your browser at:

http://localhost:8501

☁️ Deployment on Streamlit Community Cloud

Follow these steps to deploy your chatbot:

Upload your project to GitHub.
Visit https://share.streamlit.io/
Sign in using your GitHub account.
Click on Create App.
Select your GitHub repository.
Choose the main branch.
Set the main file path to app.py.
Add your API key in Advanced Settings → Secrets:
toml
GROQ_API_KEY = "your_groq_api_key_here"

Click Deploy.

Your AI chatbot will be available online!

🔑 Environment Variables
Variable	Description
GROQ_API_KEY	Your secret Groq API key
📸 Application Preview

The application provides a clean, modern interface where users can communicate with an AI assistant.

👨‍💻 Author

Your Name

GitHub: https://github.com/YOUR_USERNAME

📄 License

This project is open-source and available under the MIT License.