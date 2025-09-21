# 🩺 Healthcare Symptom Checker Agent

This project implements a simple **AI Healthcare Agent** that interacts with users to:
- Ask clarifying questions about symptoms
- Suggest possible general causes (non-diagnostic)
- Remind users that **this is not medical advice** and they should consult a doctor

The agent is built in two modes:
1. **Simulation Mode (Rule-Based)** → Free, works offline, no API required.
2. **LLM Mode (OpenAI GPT)** → Requires an API key (optional, commented out in code).

---

## 📂 Folder Structure

Healthcare_symptom_agent/
│
├── healthcare_agent.ipynb # Jupyter Notebook with code & explanations
├── README.md # Project documentation
├── .gitignore # Ignore unnecessary files (optional)


---

## ⚙️ Requirements

To run this project, you need:

- Python 3.10+  
- Jupyter Notebook / VS Code with Jupyter extension  
- Packages:
  ```bash
  pip install python-dotenv openai
  ```

---
***👉 Note: If you are only using Simulation Mode, no API key or .env file is required.***
---

## 🚀 How to Run

1. Clone the repository

  ```bash
  git clone https://github.com/your-username/Healthcare_symptom_agent.git
  cd Healthcare_symptom_agent
  ```

2. (Optional) Setup API key for LLM Mode

- Create a .env file:
  ```bash
  OPENAI_API_KEY=your_api_key_here
  ```
---
***⚠️ Keep it private — do not push it to GitHub***
---

3. Run the Notebook

- Open healthcare_agent.ipynb in Jupyter or VS Code

- Run all cells

4. Interact with the Agent

- Type symptoms like:
  ```
  You: I have a headache
  ```

- The agent responds with possible causes and disclaimers.
- Exit the chat with:
  ```
  bye/exit
  ```

---

## 🧠 Example Interaction (Simulation Mode)

```sql
Healthcare Agent: Hello! Tell me your symptoms (type 'bye' to exit).
You: I have a headache
Healthcare Agent: It sounds like you have a headache. Common causes include dehydration, stress, or eye strain. Please consult a doctor if it’s severe.

```

---

## 📌 Notes

- This is an educational demo only

- The agent does not provide real medical advice

- Always consult a licensed doctor for health concerns

---

## 👩‍💻 Authors
Selmah Tzindori
