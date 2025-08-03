# 🖼️ UI Design Generator using Generative AI

A Generative AI-powered tool that transforms natural language prompts into responsive UI designs — instantly, and without writing any code.

Built to make frontend prototyping faster and more accessible, the platform supports multiple input types (text, voice, and sketches) and produces clean HTML + Tailwind CSS output. Designed for developers, designers, educators, and beginners alike.

---

## ✨ Key Features

-  **Text-to-UI Generation**  
  Convert plain English prompts (e.g., "Create a login form") into responsive HTML and Tailwind CSS layouts using local LLMs.

-  **Voice-to-Prompt Support**  
  Use speech input via the Web Speech API to describe your UI hands-free.

-  **URL to UI Conversion**  
  Parse and replicate layout structure from any existing web page URL.

-  **Live Preview & Code Editing**  
  Instantly see the generated UI, modify the code, and view changes in real time.

-  **One-Click Export**  
  Download the generated UI as `.html`, `.jsx`, or `.json`.

-  **Framework Selection**  
  Supports Tailwind by default, with DaisyUI and Flowbite integration for pre-built components.

---

## 🧩 System Architecture & Workflow

### 🔄 Input to UI Flow

```plaintext
User Input (Text / Voice / Image / URL)
       ↓
Prompt Preprocessing & Enhancement
       ↓
LLM Code Generation (HTML + Tailwind)
       ↓
Accessibility + Syntax Enhancements
       ↓
Live UI Preview + Code Editing
       ↓
Export / Save / Customize
```
---
## 🛠 Tech Stack

| **Layer**        | **Technology**                                                     |
|------------------|---------------------------------------------------------------------|
| Frontend         | HTML, JavaScript, Tailwind CSS |
| Backend          | Node.js, Express.js, axios,body-parser |
| AI Engine        | Ollama (CodeLlama for text, LLaVA for image/sketch input)          |
| Multimodal Input | Web Speech API, Image Upload, URL Scraper                          |
| Export Options   | HTML, JSX, JSON (with syntax highlighting + one-click download)    |



