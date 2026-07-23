from pathlib import Path
import pypandoc

md = r"""# Hi 👋, I'm Abdullah Shah

<div align="center">

# 🤖 AI Engineer • React Native Developer • Full-Stack JavaScript

Building **AI-powered mobile applications** with **OpenAI APIs, LLMs, React Native, TypeScript, Node.js & Firebase**.

![Profile Views](https://komarev.com/ghpvc/?username=abddullah&label=Profile%20Views&color=0e75b6)

</div>

---

## 🚀 About Me

- 💼 5+ years building production mobile & web apps
- 🤖 AI Engineer focused on LLM-powered applications
- 📱 React Native specialist
- 🧠 Learning Agentic AI, RAG, MCP & Prompt Engineering
- 🌍 Open to Remote AI Engineer opportunities

## 🛠 Tech Stack

`React Native` `TypeScript` `JavaScript` `Node.js` `Express` `MongoDB` `Firebase` `OpenAI` `LLMs` `Git` `Docker`

## 🤖 AI Stack

- OpenAI API
- LLM Integration
- AI Chatbots
- Prompt Engineering
- Function Calling
- RAG
- MCP
- Vector Search

## 🚀 Featured Projects

### 🩺 AI Health Assistant
AI-powered mobile application that analyzes symptoms and provides health insights using LLMs.

### 💬 AI Chat Assistant
Conversational assistant powered by OpenAI APIs.

### 📱 React Native Apps
Cross-platform mobile applications with modern UI/UX.

## 📫 Contact

- Email: **abddullahshah@gmail.com**
- Upwork: https://www.upwork.com/freelancers/~01124e8bcb0ba30114

---

## 📊 GitHub Stats

<p align="center">
<img src="https://github-readme-stats.vercel.app/api?username=abddullah&show_icons=true&theme=tokyonight"/>
</p>

<p align="center">
<img src="https://github-readme-streak-stats.herokuapp.com/?user=abddullah&theme=tokyonight"/>
</p>

<p align="center">
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=abddullah&layout=compact&theme=tokyonight"/>
</p>

---

<div align="center">

### 🚀 Building the Future with AI

</div>
"""
out="/mnt/data/README.md"
Path(out).write_text(md,encoding="utf-8")
print(out)
