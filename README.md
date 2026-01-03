🤖 Code Gen AI

Code Gen AI is an AI-powered coding assistant built using Streamlit and Groq LLMs.
It helps users explain programming concepts, generate code, debug errors, and extract code/text from files using OCR, all in an interactive chat interface.

🚀 Features

     💬 Chat-based AI assistant for coding help
     
     📚 Explain concepts with examples
     
     💻 Generate & fix code
     
     💡 Project and coding ideas
     
     📎 File upload support (Images, PDFs, TXT, Python files)
     
     🔍 OCR integration using Tesseract (extract text from images & PDFs)
     
     🎤 Voice input support (Speech-to-text)
     
     🧠 Multiple model selection (Groq LLMs)
     
     🗂️ Multiple chat threads with history
     
     🎨 Modern UI with custom CSS styling

🛠️ Tech Stack

     Frontend & App Framework: Streamlit
     
     LLM API: Groq
     
     OCR: Tesseract, pdf2image
     
     Speech Recognition: SpeechRecognition
     
     Language: Python

📦 Installation & Setup

     1️⃣ Clone the repository
     
     git clone https://github.com/IshwariWalke/codegenai-ishwari.git
     
     cd codegenai-ishwari
     
     2️⃣ Create a virtual environment (recommended)
     
     python -m venv venv
     
     source venv/bin/activate   # On Windows: venv\Scripts\activate
     
     3️⃣ Install dependencies
     
     pip install -r requirements.txt
     
     
     If requirements.txt is not present:
     
     pip install streamlit groq speechrecognition pillow pytesseract pdf2image

🔑 API Key Setup

     Set your Groq API key as an environment variable:
     
     Windows
     set GROQ_API_KEY=your_api_key_here
     
     macOS / Linux
     export GROQ_API_KEY=your_api_key_here
     
     
     ⚠️ Do NOT hardcode API keys in production

▶️ Run the Application

     streamlit run app.py

     Then open:
     
     http://localhost:8501

📂 Supported File Types

     Images: png, jpg, jpeg
     
     Documents: pdf, txt
     
     Code files: py

🧠 Available Models

     llama-3.1-8b-instant
     
     llama-3.1-70b-versatile
     
     mixtral-8x7b-32768
     
     (Model can be selected from the sidebar)

⚠️ Known Limitations

     OCR accuracy depends on image quality
     
     Speech input may fail in noisy environments
     
     Large files may take longer to process

📌 Future Improvements

     Authentication & user profiles
     
     Persistent chat storage (database)
     
     Streaming responses
     
     Better error handling
     
     Deployment on cloud (AWS / Streamlit Cloud)
