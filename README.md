# 📚 Smart Study Break Advisor

An AI-powered study break recommendation system that understands how a student feels while studying and calculates a personalized break duration using **Gemini AI and Fuzzy Logic**.

The project combines **Natural Language Processing (NLP)** with **Fuzzy Logic** to provide an intelligent and personalized study-break recommendation through an easy-to-use Streamlit web application.

---

## 🚀 Project Overview

Students often study for long periods without taking appropriate breaks, which can lead to tiredness, stress, and reduced concentration.

**Smart Study Break Advisor** solves this problem by allowing students to describe their current study condition in natural language.

The application:

1. Takes study-related information from the user.
2. Uses **Gemini AI through LangChain** to understand the user's situation.
3. Processes the input using **Fuzzy Logic**.
4. Calculates a suitable break duration.
5. Displays the personalized break recommendation.

---

## ✨ Features

* 🧠 **AI-based Understanding** – Gemini AI understands the student's natural-language input.
* 🔍 **Fuzzy Logic Decision Making** – Calculates an appropriate break duration based on different input conditions.
* ⏱️ **Personalized Break Duration** – Provides a specific break time instead of a generic suggestion.
* 💻 **Simple Streamlit Interface** – Easy-to-use web interface.
* 📊 **Intelligent Recommendation** – Combines AI reasoning with rule-based fuzzy decision making.
* 🔐 **Environment Variable Support** – API keys are stored securely using `.env`.

---

## 🏗️ System Architecture

```text
                User
                 │
                 ▼
       ┌───────────────────┐
       │  Streamlit UI     │
       │  User Input       │
       └─────────┬─────────┘
                 │
                 ▼
       ┌───────────────────┐
       │   Gemini AI       │
       │   + LangChain     │
       │ Natural Language  │
       │   Understanding   │
       └─────────┬─────────┘
                 │
                 ▼
       ┌───────────────────┐
       │   Fuzzy Logic     │
       │  Decision System   │
       └─────────┬─────────┘
                 │
                 ▼
       ┌───────────────────┐
       │ Break Duration     │
       │ Recommendation     │
       └───────────────────┘
```

---

## 🛠️ Technologies Used

| Technology    | Purpose                             |
| ------------- | ----------------------------------- |
| Python        | Main programming language           |
| Streamlit     | Web application interface           |
| Google Gemini | AI/Natural Language Understanding   |
| LangChain     | LLM integration and prompt handling |
| Fuzzy Logic   | Personalized break calculation      |
| Scikit-Fuzzy  | Implementation of fuzzy logic       |
| NumPy         | Numerical calculations              |
| Pydantic      | Input validation                    |
| python-dotenv | Environment variable management     |

---

## 📂 Project Structure

```text
Smart-Study-Break-Advisor/
│
├── app.py
├── requirements.txt
├── .env
├── .gitignore
└── README.md
```

> **Note:** Do not upload your `.env` file or API key to GitHub.

---

## ⚙️ Installation

### 1. Clone the Repository

```bash
git clone https://github.com/shaalu/Smart-Study-Break-Advisor.git
```

### 2. Open the Project

```bash
cd Smart-Study-Break-Advisor
```

### 3. Create a Virtual Environment

```bash
python -m venv venv
```

### 4. Activate the Virtual Environment

**Windows:**

```bash
venv\Scripts\activate
```

**Mac/Linux:**

```bash
source venv/bin/activate
```

### 5. Install Required Libraries

```bash
pip install -r requirements.txt
```

---

## 🔑 API Key Configuration

Create a `.env` file in the project folder.

Add your Gemini API key:

```env
GOOGLE_API_KEY=your_api_key_here
```

Make sure `.env` is included in `.gitignore`:

```text
.env
venv/
__pycache__/
```

---

## ▶️ Run the Application

Run the following command:

```bash
streamlit run app.py
```

The application will open in your browser.

---

## 🖥️ How It Works

### Step 1 — User Input

The student provides information about their current study session and how they feel.

Example:

```text
I have been studying for several hours and I am feeling tired and unable to concentrate.
```

### Step 2 — AI Processing

Gemini AI analyzes the natural-language input and identifies relevant information about the student's study condition.

### Step 3 — Fuzzy Logic

The extracted information is passed to the fuzzy logic system.

Fuzzy rules determine the appropriate break duration based on the student's condition.

### Step 4 — Recommendation

The system displays a personalized break recommendation.

Example:

```text
Recommended Break: 15 minutes
```

---

## 🧠 AI + Fuzzy Logic

The project uses two important components:

### Artificial Intelligence

Gemini AI is responsible for understanding the user's natural-language description.

### Fuzzy Logic

Fuzzy Logic is responsible for making the final decision regarding the break duration.

This combination makes the system more flexible than a simple fixed-rule application.

```text
Natural Language Input
          ↓
       Gemini AI
          ↓
   Extracted Information
          ↓
     Fuzzy Logic
          ↓
 Personalized Break
```

---

## 📌 Example

### Input

```text
Study Hours: 4

Feeling:
I am feeling very tired and my concentration is low.
```

### Output

```text
Recommended Break Duration: 20 minutes
```

The exact recommendation depends on the values processed by the fuzzy logic system.

---

## 🎯 Objectives

* To develop an intelligent study-break recommendation system.
* To use AI for understanding natural-language student input.
* To apply fuzzy logic for personalized decision-making.
* To provide an easy-to-use web application for students.
* To demonstrate the practical combination of **AI and Fuzzy Logic**.

---

## 🌟 Advantages

* Personalized recommendations
* Easy to use
* Natural-language input
* AI-powered understanding
* Fuzzy decision-making
* Fast recommendations
* Simple web-based interface

---

## 🔮 Future Scope

The project can be further improved by adding:

* 📱 Mobile application
* 📈 Study-performance tracking
* ⏰ Automatic break reminders
* 📊 Productivity analytics
* 🎙️ Voice-based input
* 🧠 More advanced personalization
* 📅 Study schedule integration
* 🌐 Multi-language support
* 📋 Study history and reports

---

## ⚠️ Limitations

* Requires a Gemini API key for AI processing.
* Recommendation quality depends on the information provided by the user.
* Internet connection may be required for Gemini API communication.
* Fuzzy rules are predefined and can be expanded for better personalization.

---
Links : 

GitHub Link : `https://github.com/shaalu`

Deployment Link : 

---

## ⭐ Acknowledgement

This project was developed as an **AI + Fuzzy Logic Mini Project** to demonstrate the practical application of Artificial Intelligence, Large Language Models, LangChain, and Fuzzy Logic in an educational domain.

---
## Author :
Name : Shalu Shrivastav
Course : TY-IT
Topic : Smart Study Break Advisor
