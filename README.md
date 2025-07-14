# url-scam-detection-using-gemini
Secure AI web app that leverages Google Gemini 1.5 Flash to classify URLs and detect scam messages. Built using Python, Flask, and LLM prompt engineering.

- Detect scam or legitimate content from `.pdf` or `.txt` files
- Classify URLs as **benign**, **phishing**, **malware**, or **defacement**

---

## 📁 Project Structure

```
url_Scam/
├── main.py             # Flask app logic
├── templates/
│   └── index.html      # HTML form UI
├── requirements.txt    # Python libraries
└── README.md           # Project info
```

---

## How to Run

1. **Clone the repository**
```bash
git clone https://github.com/Shivaleela-kallur/url-scam-detection-using-gemini.git
cd url-scam-detection-using-gemini/url_Scam
```

2. **Install dependencies**
```bash
pip install -r requirements.txt
```

3. **Set your Gemini API key** in `main.py`
```python
os.environ["GOOGLE_API_KEY"] = "your-api-key-here"
```

4. **Run the app**
```bash
python main.py
```

Then open your browser and go to:  
`http://127.0.0.1:5000/`

---

##  Features

- Upload `.pdf` or `.txt` files to scan for scam content
- Enter a URL to classify its risk level using AI
- Simple, clean interface built with HTML and Flask

---

##  Notes

- Keep your Gemini API key secure
- This app is intended for basic testing or learning purposes
