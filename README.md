# 🧠 LangChain Chatbot using OpenAI GPT-4o  
This project is a simple command-line chatbot built using LangChain and OpenAI's GPT-4o model. It allows users to ask natural language questions and receive AI-generated answers. The chatbot supports continuous conversation and real-time behavior, such as returning the current date when asked. It is designed to run smoothly in Google Colab or in any local Python environment like VSCode or Jupyter Notebook. This chatbot is built using LangChain’s modular components: a prompt template, a language model (LLM), and an output parser. The project uses OpenAI's GPT-4o model to generate intelligent responses based on user input. A special feature of this chatbot is that it dynamically injects the current date into the system prompt, enabling it to respond accurately to time-based questions like “What’s today’s date?”. It also runs in a loop, allowing multiple queries during a single session. For safety, the OpenAI API key is securely handled using Python’s `getpass()` method to prevent hardcoding and accidental key exposure.  
## 🚀 How to Run  
### 🔹 Run on Google Colab  
1. Open the notebook in [Google Colab](https://colab.research.google.com)  
2. Install the required packages:  
   `pip install langchain langchain-openai`  
3. Run the code blocks and enter your OpenAI API key when prompted  
### 🔹 Run Locally (Optional)  
1. Clone this repository  
2. Create and activate a virtual environment (optional but recommended)  
3. Install the dependencies:  
   `pip install langchain langchain-openai python-dotenv`  
4. Run the chatbot script using any Python IDE or terminal  
## 🔐 API Key Security  
This project uses Python’s `getpass()` method to securely input your OpenAI API key. This ensures that the key is never hardcoded or saved in the code, making it safe for sharing or uploading the notebook to GitHub.  
## 📁 Project Files  
- `chatbot_langchain.ipynb` – The main notebook file to run the chatbot  
- `README.md` – Documentation for understanding and running the project  
## 🔮 Future Enhancements  
Here are a few ideas to expand this chatbot project further:  
- [ ] Add a UI using Streamlit or Gradio  
- [ ] Add memory to keep track of previous messages  
- [ ] Store chat logs in a file or database
- [ ] Connect to documents (like PDFs) for Q&A
- [ ] Upgrade to a RAG (Retrieval-Augmented Generation) system 

## 👩‍💻 Author  
Created by **Beaula Medikonda**
# Feel free to fork, customize, and build upon this project!
