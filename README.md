# 📝 AI Blog Generator with LLaMA 2 + Streamlit

![Python](https://img.shields.io/badge/Python-3.9%2B-blue)
![Streamlit](https://img.shields.io/badge/Streamlit-App-red)
![License](https://img.shields.io/badge/License-MIT-green)
![LLaMA 2](https://img.shields.io/badge/Model-LLaMA%202%207B%20Chat-purple)

An AI-powered blog generation tool built with **LLaMA 2 7B Chat** and **Streamlit**.  
Generate blogs for **Researchers**, **Data Scientists**, or a **General audience** — fully offline, no API keys required.

---

## 🚀 Features
- 🧠 **Runs locally** with the LLaMA 2 model — no API costs.
- 🎯 **Audience-specific writing** — choose from Researchers, Data Scientists, or General readers.
- 📏 **Custom word count** control.
- ⚡ **Fast** and responsive Streamlit UI.
- 🔒 Full control of your data — nothing leaves your machine.

---
### 1️⃣ Clone this Repository

git clone https://github.com/bhavithaveera-ai/llama-blog-generator.git
cd llama-blog-generator

### 2️⃣ Create a Virtual Environment (Recommended)

venv\Scripts\activate

### 3️⃣ Install Dependencies

pip install -r requirements.txt

### 4️⃣ Download the Model File

Go to TheBloke/Llama-2-7B-Chat-GGML

Accept Meta’s LLaMA 2 license on Hugging Face.

Download the desired .bin file (e.g., llama-2-7b-chat.ggmlv3.q8_0.bin).

Place it in your project folder.

Update the model_file path in llama_blog_app.py if needed.

### ▶️ Running the App

streamlit run llama_blog_app.py

