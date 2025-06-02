# ProMPT – Professional Modeling Prompting Tool

This repository was developed as part of the course **01HZROV — Crafting Tech: Conceiving, Designing, and Communicating Tech Ideas**. It contains the full project for **ProMPT**, the *Professional Modeling Prompting Tool*.

## Overview

**ProMPT** is designed to assist users in making well-informed decisions about the implementation of Artificial Intelligence (AI) solutions in **post-conflict regions**. By leveraging large language models (LLMs), the tool helps users assess potential benefits, risks, and mitigation strategies for AI applications in sensitive post-war contexts. 

Overview Video: https://youtu.be/Mgbl7d8YLOg

---

## Repository Structure

### 📄 `Feasibility Study`
Contains the feasibility study for the ProMPT tool. This includes:

- **Macro-level market analysis**
- **Industry landscape**
- Justification for tool relevance and positioning

---

### 📄 `RAI Guidelines Test`
This folder documents the testing process for responsible AI design using RAI (Responsible AI) guidelines. It evaluates how ProMPT aligns with principles for ethical and accountable AI development.

---

### 📂 `War Taxonomy/`
Includes Python notebooks and resources used to develop the **conflict and problem database**, a key component of the prompt-generation process. This taxonomy defines post-conflict scenarios and key challenges that ProMPT addresses.

---

### 📂 `ProMPT/`
This is the core folder containing the tool itself.

- **`ProMPT.py`** — Main entry point. Users can input their selected problem and provide their LLM API key (defaults to ChatGPT).
- **`generate_cards.py`** — Formats the LLM output into visually structured *Impact Assessment Cards*.
- Example cards used in the tool’s evaluation study are also included for reference.

---

## How to update the database

1. Navigate to the `War Taxonomy/` directory.
2. Run `extractConflicts.py` to make list of ongoing conflicts up-to-date.
   - Optional: change filtering settings.
4. Run `findProblems.py` to update list of post-war related problems.
   - Input a webpage, for example a Wikipedia-page, from where you want to extract problems.
   - Optional: change filtering settings.
  
---

## How to Use

1. Navigate to the `ProMPT/` directory.
2. Run `ProMPT.py` to initiate the tool:
   - Input the selected post-conflict problem.
   - Provide an API key for your preferred large language model (e.g., OpenAI's ChatGPT).
3. Use `generate_cards.py` to convert raw LLM outputs into formatted cards.
4. Review the generated **Impact Assessment Cards (IACs)** for structured insights into benefits, risks, and mitigation strategies.

---

## Target Users

- Government agencies
- International organizations
- Civic groups and policy makers involved in post-conflict recovery

---


For questions or contributions, feel free to open an issue or submit a pull request.
