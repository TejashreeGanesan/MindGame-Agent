# 🕵️‍♂️ MindGame: AI with Theory of Mind  

🚀 **Playing Imperfect Information Games with Theory of Mind-Aware GPT-4**  

> *"The greatest trick the AI ever pulled was making you believe it didn't know your next move."*  

## 🎭 About the Project  
**Suspicion-Agent** is an advanced AI framework designed to excel in **imperfect information games** by leveraging GPT-4's **Theory of Mind (ToM)** capabilities. It models and predicts the beliefs and strategies of other agents, giving it a unique edge in strategic decision-making.  

🧠 **Key Features:**  
✔️ Uses GPT-4's cognitive reasoning to model opponent strategies.  
✔️ Competes with various **rule-based AI models** like CFR, NFSP, DQN, and DMC.  
✔️ Implements **SkyAGI-based** multi-agent interaction for game simulations.  
✔️ Designed for research in **game theory, AI psychology, and ToM modeling.**  

---

## 🚀 Getting Started  

### 🔧 Prerequisites  
Ensure you have Python **3.8.5+** installed.  

### 📦 Installation  
Clone the repository and install dependencies:  

```bash
git clone  https://github.com/TejashreeGanesan/MindGame-Agent.git
cd MindGame-Agent
pip install -r requirements.txt
```

### 🔑 OpenAI Key Setup  
You'll need an **OpenAI API key** to run the model. Set it up by following the instructions in the `OPENAI_KEY` file.  

---

## 🎮 Running the Agent  

You can train and evaluate the agent using:  

```bash
python main_vs_baseline.py --user --verbose_print --rule_model [cfr/nfsp/dqn/dmc]
```

🔹 Replace `[cfr/nfsp/dqn/dmc]` with your preferred strategy model.  

---


