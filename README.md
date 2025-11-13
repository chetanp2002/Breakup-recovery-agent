![My Image](https://raw.github.com/chetanp2002/images/main/breakup-recovery.png)


# Breakup Recovery AI

**An AI-powered companion to help users cope, heal, and grow after a breakup.**

This project uses **Python, Flask, and Groq AI** to provide:

* Therapist-style responses
* Closure messages
* 7-day personalized recovery plans
* Honest advice when needed

All responses are generated using **AI and Markdown** for clear, easy-to-read guidance.

---

## Features

* **Therapist Response:** Empathetic advice to help process emotions.
* **Closure Messages:** Helps users express unsaid feelings and find emotional release.
* **7-Day Recovery Planner:** Step-by-step plan to rebuild oneself.
* **Honest Advice:** Straightforward guidance for faster emotional growth.
* **Image Support:** Users can upload images for context (optional).
* **Markdown Output:** Responses are rendered clearly with headers, bullets, and formatting.

---

## Tech Stack

* **Backend:** Python, Flask
* **AI Model:** Groq AI (LLaMA-3.3-70B Versatile)
* **Frontend:** Tailwind CSS, Marked.js for Markdown rendering
* **File Handling:** Flask `request.files`, UUID for unique uploads

---

## How it Works

1. User inputs their breakup story and/or uploads images.
2. Flask sends input to **Groq AI** via agents:

   * Therapist
   * Closure Message
   * Recovery Planner
   * Honest Advice
3. Each agent returns a Markdown-formatted response.
4. Frontend renders responses using **Marked.js** for proper formatting.

---

## Installation

1. Clone the repository:

```bash
git clone https://github.com/chetanp2002/Breakup-Recovery-AI.git
cd Breakup-Recovery-AI
```

2. Create a virtual environment:

```bash
python -m venv venv
source venv/bin/activate  # Linux/macOS
venv\Scripts\activate     # Windows
```

3. Install dependencies:

```bash
pip install -r requirements.txt
```

4. Set your Groq API key:

```bash
export GROQ_API_KEY="YOUR_API_KEY"  # Linux/macOS
set GROQ_API_KEY="YOUR_API_KEY"     # Windows
```

5. Run the app:

```bash
python app.py
```

6. Open your browser at `http://127.0.0.1:5000`

---

## Future Improvements

* Multi-language support
* Customizable recovery plans
* Mobile-friendly interface
* Persistent user history

---

## Repository Structure

```
Breakup-Recovery-AI/
│
├── app.py             # Flask backend
├── templates/
│   └── index.html     # Frontend
├── uploads/           # Uploaded images
├── static/            # CSS/JS files if needed
├── requirements.txt
└── README.md
```

---

## Contact

Created by **Chetan Pawar**

* [GitHub](https://github.com/chetanp2002)
* [LinkedIn](https://www.linkedin.com/in/data-scientist-chetan)
