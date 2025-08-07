# 🧠 7 Building Blocks of AI Agents

This repository contains hands-on implementations of the **7 core components** required to build robust, intelligent, and production-ready AI agents using LLMs like **Groq**, **Gemini**, and frameworks like **LangChain** and **LangGraph**.

To understand more, check out: [7 Building Blocks by Dave Ebbelaar](https://github.com/daveebbelaar/ai-cookbook/tree/main/agents/building-blocks)

---

## 📦 Repository Structure

Each Jupyter Notebook corresponds to one key building block of AI agents:

| Notebook File             | Block Name     | Description |
|--------------------------|----------------|-------------|
| `1_intelligence.ipynb`   | Intelligence   | Uses LLMs (Groq, Gemini) for text generation and task handling. |
| `2_memory.ipynb`         | Memory         | Maintains conversation history for context-aware responses. |
| `3_tools.ipynb`          | Tools          | Integrates external tools using Groq's Tool Use, Gemini’s Function Calling, and LangChain’s `@tool` decorator. |
| `4_validation.ipynb`     | Validation     | Validates and parses structured outputs using `Pydantic`. |
| `5_control.ipynb`        | Control        | Controls agent flow using logic conditions and intent routing. |
| `6_recovery.ipynb`       | Recovery       | Implements error handling and retry logic using the `Tenacity` library. |
| `7_feedback.ipynb`       | Feedback       | Adds human-in-the-loop feedback to the agent for safer decision-making. |

---

## ⚙️ Environment Setup

Before running the notebooks, make sure you have Python 3.9+ installed and the following dependencies:

### 1. Create a virtual environment

```bash
python -m venv venv
source venv/bin/activate    # On Windows: venv\Scripts\activate
```

### 2. Install Dependencies

```cmd
pip install -r requirements.txt
```

### 3. Set up Environment Variables
Make a file named `.env`, then add the following api keys

```.env
GROQ_API_KEY = your_groq_api_key
GEMINI_API_KEY = your_gemini_api_key
TAVILY_API_KEY = your_tavily_api_key
```

## 🙌 Contributions
Feel free to fork and contribute by expanding use cases or integrating more tools!
