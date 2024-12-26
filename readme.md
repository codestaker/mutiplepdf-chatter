# 📚 Multiple PDF Chatter

> **Interact with Multiple PDF Documents Using Natural Language Queries**

## 🚀 **Introduction**
The **Multiple PDF Chatter** is a Python-powered application that allows you to chat with multiple PDF documents simultaneously. You can ask questions about the PDFs using natural language, and the app will provide accurate responses based on the content of the loaded documents. The application leverages a powerful language model to ensure precise and context-aware answers.

⚠️ **Note:** The app will only respond to questions related to the loaded PDFs.

---

## 🛠️ **How It Works**

![Multiple PDF Chatter Diagram](./docs/PDF-LangChain.jpg)

The app operates in the following steps:

1. **PDF Loading:** Extracts text content from multiple PDF documents.
2. **Text Chunking:** Divides extracted text into manageable chunks for processing.
3. **Text Embedding:** Generates vector embeddings for text chunks using a language model.
4. **Similarity Matching:** Matches user queries with the most relevant text chunks.
5. **Response Generation:** Passes the matched content to the language model to generate a context-aware response.

---

## 📦 **Dependencies and Installation**

Follow these steps to set up the **Multiple PDF Chatter**:

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/codestaker/pdf_chat-multiFiles-
   cd pdf_chat-multiFiles-
   ```

2. **Install Dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

3. **Set Up API Key:**
   - Obtain an API key from [OpenAI](https://platform.openai.com/signup).
   - Create a `.env` file in the root directory and add:
     ```env
     OPENAI_API_KEY=your_secret_api_key
     ```

---

## ▶️ **How to Run the Application**

1. Ensure all dependencies are installed and the API key is properly configured.
2. Launch the app using Streamlit:
   ```bash
   streamlit run app.py
   ```
3. The app will open in your default web browser.
4. Upload one or more PDF documents.
5. Start asking questions about the PDFs using the chat interface.

---

## 💻 **System Requirements**

- **Operating System:** Windows, macOS, or Linux
- **Python Version:** 3.8 or above
- **Memory:** Minimum 4GB RAM (8GB recommended)
- **Dependencies:** Listed in `requirements.txt`
- **API Access:** OpenAI API Key

---

## 🚀 **Deployment Options**

### **Local Deployment:**
- Follow the usage instructions above.

### **Cloud Deployment:**
- Deploy on cloud platforms such as **AWS**, **Azure**, or **Google Cloud Platform**.
- Use Docker to containerize the application for easier cloud deployment.

### **Streamlit Sharing:**
- Host your app directly on [Streamlit Cloud](https://streamlit.io/cloud).

---

## 💻 **Project Structure**
```
📁 pdf_chat-multiFiles-
├── app.py          # Main Streamlit application
├── main.py         # Backend logic
├── requirements.txt # Python dependencies
├── .env            # Environment variables (API Key)
└── docs
    └── PDF-LangChain.jpg  # Workflow diagram
```

---

## 🤝 **Contributing**
This repository is intended for **educational purposes** and currently **does not accept contributions**. It serves as a companion project to a **YouTube tutorial** demonstrating the development process. Feel free to fork, experiment, and customize the app for your own use.

---

## 📜 **License**
This project is licensed under the **[MIT License](https://opensource.org/licenses/MIT)**.

---

## 📧 **Contact**
For questions, feedback, or collaboration ideas, feel free to reach out:
- **Email:** codestake9@gmail.com
- **GitHub:** [codestaker](https://github.com/codestaker/pdf_chat-multiFiles-)
- **X (formerly Twitter):** [@mezzo_man](https://x.com/mezzo_man)

Happy chatting with your PDFs! 🚀📄✨

---

**⭐ Don't forget to star this repository if you find it useful!** 🌟
