# 🎬 AI Film Critics Panel  

An experimental **multi-agent discussion system** built entirely with the **OpenAI Agent Builder**.  
The project simulates a five-round film debate moderated by **Max Moderator**, who orchestrates five distinct critic personas — each with their own genre bias and personality.  

---

## 🧩 How It Works  
1. User input is received through chat.  
2. A **state variable** `discussion_round` tracks progress (1–5).  
3. In each round, the Moderator:
   - Interprets the user’s question and formulates a own question.
   - Selects one critic persona to answer.  
   - Saves the choice and question in state variables.  
4. The selected critic responds in their unique tone.  
5. After each answer, `discussion_round` increments.  
6. After round five, the discussion ends.

---

## 👥 The Critics  
- 👻 **Hexe Hella** – Horror nerd, A24 vibes, hates “safe” horror.  
- 💕 **Herzchen Hannah** – Rom-com romantic, lives for chemistry and cozy endings.  
- 🚀 **Dr. Phase** – Sci-fi purist, logical and analytical.  
- 🎩 **Monsieur Éclat** – Arthouse connoisseur, elegant and patient.  
- 💥 **Boomer Ben** – Action junkie, all about stunts and clarity.  

---

## 💼 Business Context  
This project demonstrates **multi-agent orchestration**, **personality-driven interaction**, and **state management** within the OpenAI Agent Builder.  
Such architectures can be applied to:
- **Creative recommenders** (entertainment, e-learning, product suggestions)  
- **Conversational UX** with humor and character depth  
- **Internal AI panels** for team simulations, analysis, or decision support  

---

## 🛠️ Roadmap  
- 🔄 **Dynamic Rounds** – adaptive discussion length instead of fixed five rounds  
- 🎥 **Live Film Data** – integrate TMDb/OMDb APIs for real recommendations  
- 🧠 **Critic Memory** – persistent preferences and personalities  
- 🖥️ **Frontend Demo** – interactive web interface using Agent Builder UI tools  
- 🔊 **Voice Mode** – text-to-speech playback for podcast-like discussions  

---

## 📚 Learnings  
- Multi-agent coordination is easier and more traceable using **Agent Builder state variables**.  
- Distinct **personas and tone control** create far more engaging AI interactions.  
- **Persistent state** enables complex conversation flows without external databases.  
- The model architecture can be reused for **expert panels, evaluators, or creative brainstorming systems**.  

---

## 🧾 Note  
This README was structured with the assistance of **ChatGPT (GPT-5)**.
