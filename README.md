# LangChain Career Guidance Chatbot 🎓

A career guidance chatbot built with **LangChain**, **LangGraph**, and **Google Gemini API**. It provides personalized career advice, skill recommendations, growth strategies, and online course suggestions.

## ✨ Features

- **Personalized Advice**: The bot provides tailored guidance based on user input.
- **Intelligent Memory**: It uses a stateful approach with LangGraph to maintain conversation history and user context.
- **Skill Recommendations**: It suggests relevant technical and soft skills to learn.
- **Course Suggestions**: The bot recommends popular online courses from platforms like Coursera, Udemy, and edX.

---

## 🚀 Getting Started

### Prerequisites

- Python 3.9+
- A Google Gemini API Key

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/langchain-career-guidance-chatbot.git
cd langchain-career-guidance-chatbot
```

### 2. Set Up Your Environment

The `requirements.txt` file ensures all dependencies are installed.

```bash
pip install -r requirements.txt
```

### 3. Add Your Google Gemini API Key

You can set your API key as an environment variable, which is a secure way to handle secrets.

**On macOS/Linux:**

```bash
export GOOGLE_API_KEY="your_api_key_here"
```

**On Windows:**

```bash
set GOOGLE_API_KEY="your_api_key_here"
```

*Alternatively, the application will prompt you to enter the key if it's not set.*

---

## 🏃‍♂️ How to Run

### Option A: Run the Python Script (Recommended)

This is the best way to run the chatbot for a clean, command-line experience.

```bash
python career_chatbot.py
```

*Type `exit` or `quit` to end the conversation.*

### Option B: Run the Jupyter Notebook

If you prefer a cell-by-cell interactive experience, you can run the notebook directly.

```bash
jupyter notebook careerchatbot.ipynb
```