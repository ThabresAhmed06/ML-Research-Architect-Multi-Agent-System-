# ML Research Architect (Multi-Agent AI System)

An intelligent **multi-agent system** built using CrewAI that transforms complex machine learning research topics into **structured theoretical insights**.

---

## Overview

ML Research Architect is designed to help students, researchers, and engineers quickly understand the **core concepts of ML papers** by extracting:

* Motivation behind the model
* Architecture breakdown
* Mathematical formulations (LaTeX formatted)
* Tensor dimensions and data flow

The system uses an **AI Research Agent** to analyze and structure information in a clean, exam-ready format.

---

## Key Features

* **Agent-Based Architecture** using CrewAI
* **State Management** with Pydantic
* **Structured Output Formatting** (LaTeX + Markdown tables)
* **Research-Focused Summarization**
* **Interactive UI** built with Gradio
* Lightweight and fast inference using `gpt-4.1-nano`

---

## System Architecture

User Input → Research Agent → Structured Output → Gradio UI

The system follows a **Flow-based execution model**, ensuring modular and scalable design.

---

## Workflow

1. User enters a research topic (e.g., *Vision Transformers*)
2. Research Agent analyzes the topic
3. Extracts:

   * Model architecture
   * Mathematical equations
   * Tensor shapes
4. Outputs a clean **research dossier**

---

## Tech Stack

* **CrewAI** → Multi-agent orchestration
* **Gradio** → UI interface
* **Pydantic** → State management
* **Python** → Core development

---

## Use Cases

* ML Interview Preparation
* Research Paper Understanding
* Academic Study Assistance
* AI System Design Learning

---

## Example Input

```bash
Attention Is All You Need
```

## Example Output

* Transformer architecture breakdown
* Multi-head attention equations
* Tensor dimension tables

---

## Setup Instructions

1. Clone the repository
2. Install dependencies:

```bash
pip install crewai[tools]
pip install gradio
```

3. Add your API credentials:

```python
base_url="YOUR_BASE_URL"
api_key="YOUR_API_KEY"
```

4. Run the notebook or script

---

## Future Improvements

* Arxiv API integration
* RAG-based memory system
* Auto code generation from research
* Model visualization

---

## Author

Built as part of an **AI/ML learning journey** focusing on:

* Agentic AI systems
* Real-world ML workflows
* Research automation

---

*This project demonstrates how multi-agent systems can simplify complex AI research into actionable knowledge.*
