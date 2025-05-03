This project is a simple ChatGPT clone built using the **Reflex** fullstack Python web framework. Thanks to Reflex's built-in `chat` template, the app requires minimal manual coding and integrates seamlessly with the OpenAI API.



## 🚀 Features

* Interactive ChatGPT-style chatbot interface
* Powered by OpenAI's GPT models
* Fully functional out-of-the-box via Reflex's chat template
* Responsive UI served on `http://localhost:3000`

---

## 🛠️ Getting Started

### 1. Install Reflex

Open your terminal and install Reflex:

```bash
pip install reflex --upgrade
```

### 2. Initialize the Project

```bash
reflex init
```

You’ll be prompted to choose a template.
Type `2` and press Enter to select the **"chat"** template.

This will generate the full project structure with prebuilt chatbot functionality.

---

### 3. Install OpenAI SDK

```bash
pip install openai
```

---

### 4. Set Your OpenAI API Key

Get your API key from: [https://platform.openai.com/api-keys](https://platform.openai.com/api-keys)

Then set your environment variable:

**Windows:**

```bash
setx OPENAI_API_KEY "your_openai_api_key_here"
```

**Mac/Linux:**

```bash
export OPENAI_API_KEY="your_openai_api_key_here"
```

Replace `"your_openai_api_key_here"` with your actual API key.

---

### 5. Run the App

```bash
reflex run
```

Open your browser and go to:
[http://localhost:3000](http://localhost:3000)

---

## 📦 Project Structure

```
pythonProject1/
├── .web/
├── assets/
├── pythonProject1/
│   ├── __init__.py
│   ├── chat.py           # Main app logic (auto-generated)
│   └── state.py          # Chat state logic (auto-generated)
└── rxconfig.py           # App config
```

---

## 📌 Notes

* Make sure you have **OpenAI API credits** or an active billing account.
* You can view usage at: [https://platform.openai.com/usage](https://platform.openai.com/usage)


