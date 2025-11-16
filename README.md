# 🤖 crewAI Hands-On Exercises: Multi-Agent Systems Implementation

This repository contains my completed exercises and practical notebooks from the **crewAI + deeplearning.ai** course, focused on building and deploying autonomous, collaborating multi-agent systems.

The notebooks demonstrate hands-on implementation of the core `crewAI` framework across various real-world use cases.

---

## 🌟 Project Goal

The primary objective of these exercises is to gain practical mastery over:

1.  **Agent Specialization:** Defining agents with specific roles, skills, and backstories.
2.  **Collaborative Workflow Design:** Orchestrating complex tasks where agents work together to achieve a final goal.
3.  **Tool Utilization:** Integrating search tools and custom tools to give agents real-time, external capabilities.
4.  **Complex Use Cases:** Applying the framework to solve business problems ranging from content generation to financial analysis.

---

## 📁 Course Notebooks & Use Cases

The repository is structured around the specific lessons (L2 through L7) and practical applications covered in the course. Each `.ipynb` file represents a fully functional multi-agent crew designed to solve the corresponding problem.

| Notebook | Focus/Lesson Topic | Key Concepts Demonstrated |
| :--- | :--- | :--- |
| **`L2_research_write_article.ipynb`** | Research and Content Generation | Sequential Process, Tool Integration (Search), Multi-Agent Collaboration. |
| **`L3_customer_support.ipynb`** | Autonomous Customer Support Crew | Role Definition, Task Delegation, Handling specific customer queries. |
| **`L4_tools_customer_outreach.ipynb`** | Customer Outreach with Tools | Advanced Tool Creation and Usage, Targeted Communication Strategy. |
| **`L5_tasks_event_planning.ipynb`** | Event Planning & Logistics | Complex Task Breakdowns, Iterative Planning, Task dependencies. |
| **`L6_collaboration_financial_analysis.ipynb`** | Financial Analysis & Reporting | Inter-Agent Collaboration, Data Interpretation, Synthesis of structured reports. |
| **`L7_job_application_crew.ipynb`** | Job Application Automation | Highly specialized agents, Generating personalized outputs, End-to-end process. |

---

🛠️ Prerequisites & Setup
To run these exercises locally, you need Python and an active API key for an LLM provider (e.g., OpenAI, Groq, etc.).

1. Dependencies
Install the required Python packages:

pip install crewai 'crewai[tools]' jupyter

2. Configuration
You must set your LLM API key as an environment variable before running the notebooks:


# Example for OpenAI
export OPENAI_API_KEY="YOUR_API_KEY"


3. Execution
Open the notebooks using Jupyter Lab or Jupyter Notebook and run the cells sequentially:

jupyter notebook
