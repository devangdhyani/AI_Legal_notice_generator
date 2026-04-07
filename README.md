# ⚖️ AI Legal Notice Generator

An AI-powered web application that helps users generate structured Indian legal notices instantly.
Built using Streamlit and Groq LLMs, the system transforms raw user input into formal, ready-to-use legal documents.

![legal7](https://github.com/user-attachments/assets/e05ddde3-481a-4992-8f4a-d3f4eeaf5c3e)















![legal8](https://github.com/user-attachments/assets/79891e3b-490a-49ea-b8c8-0f29cd9ab40f)
















![lega2](https://github.com/user-attachments/assets/92927dda-b1d9-45e0-883d-9f77331d1d2e)




















## 🚀 Features

* 🧠 **AI-Powered Notice Generation**
  Converts user input into structured legal notices

* 📊 **Smart Case Analysis**
  Classifies disputes (Salary, Rent, Fraud, Defamation)

* ⚠️ **Missing Information Detection**
  Identifies incomplete inputs before generating notices

* ✍️ **Editable Output**
  Users can modify the generated notice before download

* 📄 **PDF Export**
  Download professionally formatted legal notice

* 🔁 **Dual Model Fallback System**
  Ensures reliability using multiple AI models

* 🎨 **Modern UI (Streamlit Enhanced)**
  Custom styling + animations + improved UX

---
![legal9](https://github.com/user-attachments/assets/ee81317c-57b1-4604-b5e8-14262131054f)
















![legal3](https://github.com/user-attachments/assets/5b56238d-e03f-4338-8cee-5ace54fc7965)
























## 🧠 How It Works

1. User enters:

   * Sender Name
   * Recipient Name
   * Address
   * Issue description

2. System sends input to AI model

3. AI returns structured JSON:

   * Case classification
   * Completeness status
   * Legal notice draft

4. App:

   * Validates JSON
   * Displays results
   * Allows editing
   * Generates PDF

---

## 🛠 Tech Stack

### Frontend / UI

* Streamlit
* Custom CSS
* Lottie Animations

### AI Layer

* Groq API
* Models:

  * llama-3.1-8b-instant (Primary)
  * llama-3.3-70b-versatile (Fallback)

### Backend Logic

* Python
* JSON validation layer

### PDF Generation

* ReportLab

---
![lega7](https://github.com/user-attachments/assets/c15268cb-6f67-46fe-b574-bd95dd120f3f)
















## 📦 Installation
Clone the repository:

```bash
git clone https://github.com/your-username/ai-legal-notice-generator.git
cd ai-legal-notice-generator
```

Install dependencies:

```bash
pip install -r requirements.txt
```

---

## 🔑 Environment Setup

Create a `.streamlit/secrets.toml` file:

```toml
GROQ_API_KEY = "your_api_key_here"
```

---

## ▶️ Run the App

```bash
streamlit run app.py
```

---

## 🧪 Example Use Case

Input:

> "My employer has not paid my salary of ₹45,000 from January to March."

Output:

* Category: Salary_Dues
* Completeness: Checked
* Generated Legal Notice
* Downloadable PDF

---

## ⚠️ Disclaimer

This document is generated for educational and informational purposes only and does not constitute legal advice. Users are advised to consult a qualified legal professional before taking any action.

---

## 📌 Limitations

* Works only for civil notice scenarios
* Depends on input quality
* AI output should always be reviewed before use

---

## 🔮 Future Improvements

* Next.js frontend (premium UI)
* Multi-language support
* Legal templates expansion
* User authentication
* Cloud deployment

---

## 🤝 Contribution

Contributions are welcome. Feel free to fork the repo and submit a pull request.

---

## ⭐ Support

If you found this useful, consider giving it a star on GitHub.
