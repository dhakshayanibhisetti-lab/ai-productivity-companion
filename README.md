# 🚀 Agentic Productivity Companion

An AI-powered productivity assistant built using **Python**, **Streamlit**, and **Google Gemini AI**. This application helps users transform large tasks into actionable plans by generating intelligent task breakdowns, urgency scores, personalized schedules, and productivity recommendations.

---

## ✨ Features

* 🤖 AI-generated task breakdown
* 📋 Step-by-step action plan
* ⏱️ Estimated time for each task
* 📊 AI-based urgency score (out of 10)
* 📅 Personalized daily schedule
* 🚧 Identifies possible obstacles
* 💡 Smart productivity tips
* 🌐 Interactive web interface built with Streamlit

---

## 🛠️ Tech Stack

* Python 3.11
* Streamlit
* Google Gemini API
* Google AI Studio
* python-dotenv

---

## 📁 Project Structure

```
ProductivityCompanion/
│
├── app.py
├── requirements.txt
├── .env (not included)
├── README.md
└── venv/
```

---

## ⚙️ Installation

### 1. Clone the repository

```bash
git clone https://github.com/your-username/ProductivityCompanion.git
cd ProductivityCompanion
```

### 2. Create a virtual environment

Windows

```bash
python -m venv venv
venv\Scripts\activate
```

Mac/Linux

```bash
python3 -m venv venv
source venv/bin/activate
```

### 3. Install dependencies

```bash
pip install -r requirements.txt
```

---

## 🔑 Configure API Key

Create a `.env` file in the project root and add:

```env
GEMINI_API_KEY=AQ.Ab8RN6L8djxwsMcB7bRbR7i9COpij2oMxja1vMqeelkuyEtWbg
```

You can generate your API key from Google AI Studio.

---

## ▶️ Run the Application

```bash
streamlit run app.py
```

The application will open in your browser at:

```
http://localhost:8501
```

---

## 📸 Demo

Enter your task and available hours, then click **Generate Plan**.

Example Input:

```
Task:
Build my UI/UX Portfolio

Available Hours:
6
```

The AI generates:

* Action Plan
* Estimated Time
* Urgency Score
* Daily Schedule
* Productivity Tips
* Potential Challenges

---

## 🚀 Future Enhancements

* Task history
* Calendar integration
* PDF export
* Voice input
* Smart reminders
* Progress tracking dashboard
* Dark mode
* Database integration

---

## 👩‍💻 Author

**Dhakshayani Bhisetti**

UI/UX Designer | ECE Student | AI Enthusiast

---

## 📄 License

This project is open-source and available under the MIT License.
