# 📖 Translation Tool for Tech Documentation  

This Jupyter Notebook provides a simple yet powerful tool for translating technical documentation (e.g., Markdown files) from **English to Russian** using the `Helsinki-NLP/opus-mt-en-ru` model from Hugging Face.  

### 🛠️ Features  
- **Easy Setup**: Installs required libraries (`transformers`, `sacremoses`) automatically.  
- **Smart Translation**: Preserves code blocks, headings, and special Markdown syntax while translating only the text content.  
- **Google Colab Integration**: Upload files directly for translation.  

### 🚀 How to Use  
1. **Upload Your File**: Run the notebook in Google Colab and upload your Markdown file.  
2. **Automatic Processing**: The tool splits the content into sections (headings, code blocks, text) and translates only the relevant parts.  
3. **Download Results**: The translated file is saved with a prefix (e.g., `NLP_filename.md`).  

### ⚡ Why Use This?  
- **Saves Time**: No manual copying/pasting of text.  
- **Context-Aware**: Avoids translating code or syntax (e.g., ```` ``` ````, `# headings`).  
- **Scalable**: Works for large documents with mixed content.  

### 📝 Notes  
- For best results, review the output for technical terms that may need manual adjustment.  
- Supports **Markdown** files but can be adapted for other formats.  

---

**Happy translating!** 🌍✨  