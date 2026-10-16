# 🌐 Language Translator in Python (`googletrans`)

A concise Python command-line utility (`lang_translator.py`) that translates user-input text into Hindi (or any configurable target language code) using the **Google Translate API (`googletrans`)**.

---

## 📂 Repository Structure

- `lang_translator.py`: Interactive CLI translation script.
- `README.md`: Project documentation.

---

## 🚀 Getting Started

1. **Clone the repository**:
   ```bash
   git clone https://github.com/sparsh0106/Google-Translator.git
   cd Google-Translator
   ```

2. **Install dependencies**:
   ```bash
   pip install googletrans==4.0.0-rc1
   ```

3. **Run the script**:
   ```bash
   python lang_translator.py
   ```

---

## ⚙️ Customization

To translate into a different language, change the `dest` ISO-639-1 language code in `lang_translator.py`:
```python
translated = translator.translate(text, dest='hi')  # e.g., 'es', 'fr', 'de', 'ja'
```

---

## 👤 Author

**Sparsh Agarwal** — [GitHub](https://github.com/sparsh0106) · [LinkedIn](https://www.linkedin.com/in/sparsh-agarwal-4b443b304/)
