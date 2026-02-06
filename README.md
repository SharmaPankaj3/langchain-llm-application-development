# LangChain LLM Application Development

This repository contains **teaching-oriented notebooks and slides** that demonstrate how to move from **Prompt Engineering** to building **real-world, maintainable LLM applications** using **LangChain**.

The material is designed for learners who already understand basic prompting and now want to learn how full LLM systems are actually built.

---

## 📌 Why This Repository?

Prompt engineering is powerful, but **real applications are not built with a single prompt**.

Production-grade LLM systems typically require:
- Multiple LLM calls
- Prompt orchestration
- Structured output parsing
- Memory and context management
- External data access (RAG)
- Evaluation and debugging
- Tool usage and agents

**LangChain** provides abstractions to manage this complexity.  
This repository explains those abstractions step by step, with hands-on notebooks.

---

## 📚 Contents

### 📓 Notebooks

The notebooks are organized in a learning-friendly sequence:

1. **L1 – Models, Prompts & Parsers**  
   - LangChain model abstractions  
   - Prompt templates  
   - Output parsing using Pydantic  

2. **L2 – Memory in LangChain**  
   - Why LLMs are stateless  
   - Conversation buffer, window, token-based memory  
   - Summary-based memory  

3. **L3 – Chains**  
   - Prompt → LLM pipelines  
   - Sequential chains  
   - Routing and branching logic  

4. **L4 – Question Answering (RAG)**  
   - Embeddings and vector stores  
   - Document chunking  
   - Retrieval-Augmented Generation  

5. **L5 – Evaluation of LLM Applications**  
   - Why classical metrics fail  
   - LLM-based evaluation  
   - Debugging and regression testing  

6. **L6 – Agents**  
   - LLMs as reasoning engines  
   - Tools and action loops  
   - When (and when not) to use agents  

---

### 📑 Slides

- **LangChain For LLM Application Development**  
  Conceptual slides used for classroom teaching and LinkedIn learning posts.

---

## 🎯 Who This Is For

- Data Scientists  
- ML / AI Engineers  
- Developers working with LLMs  
- Educators and trainers  
- Anyone who has learned **Prompt Engineering** and wants to go further

---

## 🧠 Learning Philosophy

This repository focuses on:
- Concepts before code
- Clean abstractions over hacks
- Understanding *why* something exists, not just *how*
- Building systems, not demos

---

## ⚠️ Notes

- API keys are **not included** in notebook
