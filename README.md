# 🧠 Interview Trainer Agent using IBM Watsonx.ai

This project is an AI-powered Interview Preparation Assistant built using **IBM Watsonx.ai** and the **Granite Foundation Model**. It helps users get role-specific interview questions, model answers, and preparation tips based on job title or resume input.

---

## 🚀 Features

- ✅ Generates **technical + HR interview questions**
- ✅ Provides **model answers and tips**
- ✅ Accepts **job role/title** as input
- ✅ Built using **IBM Granite LLM (Watsonx)**
- ✅ Easily extensible into a chatbot or app

---

## 🛠️ Tech Stack

- [IBM Watsonx.ai](https://www.ibm.com/watsonx)
- Granite Foundation Model (`granite-13b-chat-v2`)
- Python 3.11
- Jupyter Notebook (`.ipynb`)
- (Optional) Flutter/Web UI for frontend

---

## 📁 Project Structure

📦 interview-trainer-agent
┣ 📄 Interview_Trainer_Agent_Notebook.ipynb
┣ 📄 README.md


---

## 🧪 How to Run

### 1. 🔐 Set up IBM Cloud
- Create an account: https://cloud.ibm.com
- Launch Watsonx.ai
- Get your **API key**

### 2. 🚀 Run the notebook
- Upload `Interview_Trainer_Agent_Notebook.ipynb` to IBM Watsonx.ai Project
- Run all cells
- Enter your API key when prompted
- Enter job title (e.g., `Flutter Developer`)
- 💬 Get smart Q&A instantly!

---

## 📸 Sample Output

> 👨‍💻 Job Role: Flutter Developer

**Q1:** What is the role of `StatefulWidget` in Flutter?  
**A:** `StatefulWidget` is used when the UI can change dynamically. Example: checkbox, slider, etc.  
**💡 Tip:** Always separate logic from the UI using state management tools like Provider or Bloc.

... *(more questions generated)*

---

## 📌 Future Scope

- Upload resume and auto-detect skills
- Integrate into a chatbot (IBM Watson Assistant)
- Save Q&A sessions in user profile
- Track user progress

---

## 🧑‍💻 Author

**Dipu Mishra**  
🎓 B.Tech in IT @ KIET Group of Institutions  
📬 [dipumishra2003@gmail.com](mailto:dipumishra2003@gmail.com)

---

## 📄 License

Licensed under the [IBM ILAN License](https://www.ibm.com/legal)  
This project uses IBM Granite models under IBM Cloud T&Cs.

