# 🤖 AI Code Generator (Postman Collection to Code) ✨


> **Effortlessly convert your Postman Collection JSON into runnable API client code in any major programming language using the power of the Gemini API and LangChain.**

This tool automates the tedious process of writing API integration code. Simply upload your Postman Collection JSON, select your desired language, and get instant, production-ready code.

---

## 💡 About The Project



The **AI Code Generator** is a powerful utility designed to accelerate API integration by leveraging generative AI. It takes a **Postman Collection (V2.1 JSON)** file as input and uses the **Gemini API** orchestrated by **LangChain** to understand the API requests and translate them into native client code.

### 🎯 Key Features

* **Core Technology:** Powered by the **Gemini API** for advanced code generation capabilities.
* **AI Framework:** Uses **LangChain** to process and intelligently handle the Postman Collection data.
* **Input:** Accepts standard **Postman Collection JSON** files.
* **Output Languages:** Supports generation for a wide range of popular languages, including **Java**, **Python**, **JavaScript**, **C++**, **Go**, **PHP**, and **Ruby**.
* **User Flow:** Upload document → Select language → Generate code → Copy or Download as `.txt` file.

### 🛠️ Built With

* **Generative AI:** [![Gemini API Badge](https://img.shields.io/badge/Google%20Gemini%20API-1A73E8?style=for-the-badge&logo=google&logoColor=white)](https://ai.google.dev/gemini-api)
* **LLM Orchestration:** [![LangChain Badge](https://img.shields.io/badge/LangChain-111111?style=for-the-badge&logo=langchain&logoColor=white)](https://www.langchain.com/)
* **[Web Framework used, e.g., Flask/Streamlit/React]**
* **[Frontend Library, e.g., HTML/CSS/JS]**

---

## 🚀 Live Demo

See the AI Code Generator in action! The video below shows the process of uploading a Postman Collection, selecting a language (Java is shown), and generating the complete API request code for various endpoints defined in the collection.

[![Watch the Demo Video on Google Drive](https://img.shields.io/badge/Google%20Drive-Watch%20Demo-3F51B5?style=for-the-badge&logo=googledrive&logoColor=white)](https://drive.google.com/drive/folders/1Z_YOvblpJ96Dz-lSsvhk1sJd9O5QYr5E?usp=sharing)

---

## 💻 Getting Started

Follow these steps to set up and run the application locally.

### Prerequisites

* **API Key:** A **Gemini API Key**.
* **[Python 3.x]**
* **[pip]**

### Installation

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/JSXHive/API-Generator-ChatBOT.git](https://github.com/JSXHive/API-Generator-ChatBOT.git)
    ```
2.  **Navigate to the project directory:**
    ```bash
    cd api-generator-chatbot
    ```
3.  **Install dependencies:**
    *(If using Python and a standard setup)*
    ```bash
    pip install -r requirements.txt 
    ```
4.  **Set up your environment variable:**
    Create a file named `.env` in the root directory and add your key:
    ```
    GEMINI_API_KEY="YOUR_GEMINI_API_KEY"
    ```
    *Alternatively, export your key in your shell environment.*

5.  **Run the application server:**
    *(Replace `[script_name].py` with your main server file)*
    ```bash
    python [script_name].py
    ```

### Usage Flow

1.  Open your browser and navigate to the local address (e.g., `http://127.0.0.1:5000`).
2.  Click **"Browse Files"** to upload your Postman Collection JSON file.
3.  Select your desired programming language from the dropdown menu.
4.  Click **"Generate Code"**. The generated code will appear in the output box.
5.  Use the **"Copy"** option to quickly grab the code, or click **"Download Code"** to save it as a `.txt` file.

---

## 🤝 Contributing

Contributions are welcome! If you have suggestions for new languages, feature enhancements, or bug fixes, please open an issue or create a pull request.

---

## 📜 License

Distributed under the **MIT License**. See `LICENSE.md` for more information.

---

## 📞 Contact

**Sharvari Shet Karmalkar** - [shetkarmalkarsharvari@gmail.com](mailto:shetkarmalkarsharvari@gmail.com)

Project Link: [https://github.com/SJSXHive/API-Generator-ChatBOT](https://github.com/JSXHive/API-Generator-ChatBOT)