```markdown

#Rag-Dockling

## RAG over Documents with Dockling & Llama-3.3-70b-instruct

A Streamlit app that demonstrates Retrieval-Augmented Generation (RAG) over documents using Dockling, Llama-3.3-70b-instruct, and OpenRouter. This interactive tool allows you to upload Excel and CSV files, index their contents, and query your documents with an intelligent chat interface.

---

## 🚀 Features

- **Document Upload:**  
  Upload Excel files (`.xlsx`, `.xls`) and CSV files.
  
- **Document Indexing:**  
  Uses **DoclingReader** for Excel files and **Pandas** for CSV files to create searchable indexes.
  
- **LLM Integration:**  
  Powered by OpenRouter using the `meta-llama/llama-3.3-70b-instruct:free` model.
  
- **Interactive Chat Interface:**  
  Ask questions about your documents and get context-aware, step-by-step answers.
  
- **Customizable Prompt:**  
  Fine-tuned prompt template to guide responses from the language model.

---

## 🔧 Getting Started

### Prerequisites

- **Python 3.8+**
- **pip** package manager

### Installation

1. **Clone the Repository:**

   ```bash
   git clone https://github.com/yourusername/your-repo.git
   cd your-repo
   ```

2. **Create a Virtual Environment (Recommended):**

   ```bash
   python -m venv venv
   source venv/bin/activate   # On Windows: venv\Scripts\activate
   ```

3. **Install the Required Packages:**

   ```bash
   pip install -r requirements.txt
   ```

   > **Note:** Ensure your `requirements.txt` includes dependencies such as `streamlit`, `pandas`, `llama-index`, and any others you need.

---

## 🔑 Obtaining Your OpenRouter API Key

To power the LLM functionality, you'll need an OpenRouter API key. Follow these steps:

1. **Visit the OpenRouter Website:**  
   Go to [OpenRouter](https://openrouter.ai/) (or the respective provider's site).

2. **Sign Up / Create an Account:**  
   Click on "Sign Up" or "Register" and create your account. You might need to verify your email.

3. **Access Your Dashboard:**  
   Log in and navigate to your account dashboard.

4. **Generate an API Key:**  
   Find the section labeled "API Keys" or "Get API Key" and follow the prompts to generate a new key.

5. **Copy Your API Key:**  
   Copy the generated API key and paste it into the OpenRouter API key input field in the app's sidebar when you launch the app.

---

## ▶️ Running the App

1. **Launch the App:**

   ```bash
   streamlit run app.py
   ```

2. **Use the App:**

   - In the **sidebar**, enter your OpenRouter API key.
   - Upload your Excel or CSV file.
   - Once your document is indexed, use the chat interface to ask questions and get detailed answers.

---

## 💡 Usage

1. **Enter Your API Key:**  
   In the sidebar, provide your OpenRouter API key (you can update it at any time).

2. **Upload a Document:**  
   Choose a file (.xlsx, .xls, or .csv) and wait for it to be indexed.

3. **Chat with Your Document:**  
   Ask your questions in the chat interface. The app will process your query using the indexed document and the LLM, then display a step-by-step response.

---

## 🤝 Contributing

Contributions are welcome! If you have ideas, improvements, or bug fixes, please open an issue or submit a pull request.

---

## 📄 License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

## 🙏 Acknowledgements

- [Streamlit](https://streamlit.io/)
- [LlamaIndex](https://gpt-index.readthedocs.io/)
- [OpenRouter](https://openrouter.ai/)
- [Dockling](#) (if applicable)

---


