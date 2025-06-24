# Langchain + OpenAI Streamlit App

This is a simple demo application built using [Langchain](https://www.langchain.com/), [OpenAI](https://platform.openai.com), and [Streamlit](https://streamlit.io). The app allows users to ask questions and get AI-generated responses using OpenAI’s GPT model.

---

## 🚀 Features

- Streamlit frontend for easy interaction  
- Langchain `ChatPromptTemplate` for structured prompts  
- Uses OpenAI's GPT-3.5-Turbo model via `langchain_openai`  
- Environment variables loaded securely using `.env`

---

## 🔧 Setup

1. Clone the repository

```bash
git clone https://github.com/YOUR-USERNAME/langchain-demo.git
cd langchain-demo
```

<<<<<<< HEAD
 2. Create a virtual environment & activate it
=======
### 2. Create a virtual environment & activate it
>>>>>>> 8d6af27 (Update README formatting and content)
Windows

```bash
python -m venv venv
venv\Scripts\activate
```

Mac/Linux

```bash
python3 -m venv venv
source venv/bin/activate
```

<<<<<<< HEAD
 3. Install dependencies
=======
### 3. Install dependencies
>>>>>>> 8d6af27 (Update README formatting and content)

```bash
pip install -r requirements.txt
```

<<<<<<< HEAD
 4. Create a .env file
=======
### 4. Create a .env file
>>>>>>> 8d6af27 (Update README formatting and content)

```bash
OPENAI_API_KEY=your_openai_key
LANGCHAIN_API_KEY=your_langchain_key
```

<<<<<<< HEAD
 5. Run the app
=======
### 5. Run the app
>>>>>>> 8d6af27 (Update README formatting and content)

```bash
streamlit run app.py
```

<<<<<<< HEAD

🛡️ Environment Variables

We use a .env file to store API keys. This file is excluded from Git using .gitignore for security reasons.

 🤖 Example Prompt
=======
### 🛡️ Environment Variables

We use a .env file to store API keys. This file is excluded from Git using .gitignore for security reasons.

### 🤖 Example Prompt
>>>>>>> 8d6af27 (Update README formatting and content)

Type something like:

    What is Langchain used for?

And get a structured response from the AI assistant.

### 📂 Folder Structure

langchain-demo/
│
├── app.py
├── requirements.txt
├── .gitignore
└── .env.example  # (optional placeholder)

<<<<<<< HEAD

 📄 License
=======
### 📄 License
>>>>>>> 8d6af27 (Update README formatting and content)

This project is licensed under the MIT License.

