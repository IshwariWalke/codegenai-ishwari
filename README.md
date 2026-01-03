# codegenai-ishwari

CodeGenAI 💬

Infosys Springboard – AI Virtual Internship (CodeGen AI)

AI-powered code generation and document analysis assistant built using Streamlit and a locally hosted LLaMA-3 model.

🚀 Features

     AI chat for code generation & Q&A
     
     PDF, DOCX, TXT, CSV file analysis
     
     Image OCR support
     
     User login/signup
     
     Chat history management
     
     Local LLM inference using Ollama

🛠 Tech Stack

     Python
     
     Streamlit
     
     LLaMA-3 (Ollama)
     
     PyPDF2, python-docx
     
     pytesseract (OCR)

📂 Supported Inputs

     📄 PDF, DOCX
     
     📝 TXT, CSV
     
     🖼 PNG, JPG (OCR)

⚙️ Setup
     git clone https://github.com/<username>/springboard-codegen-ai-ishwari-walke.git
     cd springboard-codegen-ai-ishwari-walke
     pip install streamlit requests pillow PyPDF2 python-docx pytesseract


Run Ollama:

     ollama run llama3


Start app:

     streamlit run app.py

🧠 Architecture
     User → Streamlit UI
          → File/Text Processing
          → Ollama API (LLaMA-3)
          → AI Response

🎓 Internship Context

     Developed as part of Infosys Springboard AI Virtual Internship – CodeGen AI to demonstrate practical AI application development using LLMs.
