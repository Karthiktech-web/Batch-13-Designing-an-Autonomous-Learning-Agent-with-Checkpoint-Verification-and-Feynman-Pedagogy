# 🧠 Autonomous Learning Agent using LangGraph

## 📌 Project Overview

This project was implemented as part of the **Infosys Springboard Internship**.
It demonstrates the design and execution of an **Autonomous AI Learning Agent** capable of performing structured reasoning, research, and explanation using LangGraph.

The system follows an intelligent workflow that mimics human learning:
➡️ Understanding → Research → Explanation

---

## 🎯 Objective

The main goal of this project is to build an AI agent that:

* Understands user queries clearly
* Performs step-by-step reasoning
* Collects relevant information
* Generates structured and easy-to-understand outputs

---

## 🧠 System Architecture

The system is based on a **3-stage pipeline**:

### 1. Scope Phase

* Analyzes user input
* Identifies missing details
* Refines the problem statement

### 2. Research Phase

* Uses tools/APIs for data collection
* Performs iterative reasoning
* Processes intermediate results

### 3. Write Phase

* Generates final structured output
* Uses Feynman technique (simple explanation)

---

## ⚙️ Key Features

* 🔹 Multi-step AI reasoning
* 🔹 Autonomous decision-making workflow
* 🔹 API-based execution using FastAPI
* 🔹 Thread-based state management
* 🔹 Structured outputs using LangGraph
* 🔹 Real-time execution monitoring

---

## 🛠️ Tech Stack

| Technology | Purpose                |
| ---------- | ---------------------- |
| Python     | Core programming       |
| LangGraph  | Workflow orchestration |
| LangChain  | Agent + tools          |
| FastAPI    | Backend API            |
| Docker     | Containerization       |
| GitHub     | Version control        |

---

## 🚀 Implementation Steps

### Step 1: Clone Repository

```bash id="a1"
git clone <your-repo-link>
cd Autonomous-Learning-Agent
```

---

### Step 2: Setup Environment Variables

```bash id="a2"
cp .env.example .env
```

Add your API keys:

```env id="a3"
TAVILY_API_KEY=your_api_key
GROQ_API_KEY=your_api_key
```

---

### Step 3: Run the Application

```bash id="a4"
docker-compose up
```

---

### Step 4: Access API Interface

* Swagger UI: http://localhost:8000/docs
* API Base: http://localhost:8000

---

## 🔄 Workflow Execution (What I Performed)

During execution, the following steps were performed:

1. Created an Assistant
2. Created a Thread
3. Executed Runs
4. Monitored Run Status
5. Retrieved Final Output

---

## 📊 Sample Output

* Successfully executed AI workflow
* Generated structured response on topic: *Machine Learning*
* Maintained thread-based state
* Completed run with **status: success**

---

## 📈 Results

The system:

* Successfully performs autonomous reasoning
* Handles multi-step workflows
* Produces clear and structured explanations
* Demonstrates practical AI agent behavior

---

## 🎓 Learning Outcomes

* Understood **LangGraph architecture**
* Learned **Agent-based system design**
* Worked with **REST APIs and endpoints**
* Gained experience in **Docker-based deployment**
* Improved understanding of **AI workflow execution**

---

## ⚠️ Challenges Faced

* Understanding API flow (Assistants → Threads → Runs)
* Managing environment variables
* Handling errors in API requests
* Debugging Docker execution

---

## 📌 Conclusion

This project demonstrates how AI agents can simulate human-like learning and reasoning processes using structured workflows.

It provides hands-on experience in building intelligent systems using modern AI frameworks like LangGraph.

---

## 📌 Note

This project was executed for academic and learning purposes as part of the Infosys Springboard Internship.
