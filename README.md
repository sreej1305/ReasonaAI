# 🧠 Reasona AI – Decision Justification Engine

**Reasona AI** is a Jupyter Notebook–based project designed to solve the "Black Box" problem in AI decision-making. Instead of just delivering an outcome, Reasona AI provides structured, human-readable justifications that explain the *why* behind a decision or outcome.

🎯 **Project Objective**: Create an AI-driven reasoning layer that prioritizes transparency, ethics, and causal clarity over simple prediction.

---

## 🚀 Working Preview

Here is how **Reasona AI** processes a natural language decision statement:

### 1. Input Analysis
**User Input:** 
> "The mortgage application for applicant #4412 was denied despite a high credit score of 810. The system flagged the debt-to-income ratio as exceeding the 43% threshold due to a recent student loan consolidation."

### 2. Semantic Extraction (Output)
| Entity | Value |
| :--- | :--- |
| **Intent** | Financial Judgment / Mortgage Underwriting |
| **Outcome** | NEGATIVE / DECISION_DENIED |
| **Key Condition** | DTI > 43% Threshold |

### 3. Core Justification (Step-by-Step)
1. **Analyze** relationship between credit reliability (810 score) and payment capacity (DTI).
2. **Verify** policy constraints (43% ceiling).
3. **Determine** impact of student loan consolidation on monthly obligations.
4. **Conclude**: The denial is triggered by liquidity limits, not credit history.

### 4. Risk & Bias Flagging
- 🚩 **Bias Risk**: DTI thresholds may disadvantage young applicants with high student debt but high future earnings.
- 🚩 **Fairness Check**: Ignoring 99th-percentile credit history indicates an over-tuned risk model.

---

## 🧩 Notebook Structure

1. **Project Overview**: Motivation for AI transparency.
2. **Input Interface**: Natural language only (No SQL/Queries).
3. **Semantic Understanding**: Extracting intent, entities, and conditions.
4. **Core Justification Engine**: Step-by-step reasoning and causal links.
5. **Assumption & Gap Detection**: Identifying missing info and implicit logic.
6. **Risk & Bias Awareness**: Flagging fairness concerns.
7. **Alternative Reasoning Paths**: "What-If" scenario analysis.
8. **Explanation Quality Score**: Metics for clarity and completeness.
9. **Final Executive Summary**: Concise, jargon-free paraphrase.

---

## 🛠 Usage

1. Open `Reasona_AI_Engine.ipynb` in Jupyter Notebook or Google Colab.
2. Navigate to Section 2: **Input Interface**.
3. Modify the `user_input` variable with any natural language decision statement.
4. Run all cells top-to-bottom to generate the justification report.

## 🎓 Technical Focus
- **Prompt Engineering**: The core logic is driven by structured reasoning templates.
- **Explainable AI (XAI)**: Focusing on human-centric communication.
- **Responsible AI**: Built-in awareness for ethics and bias.

---
*Created by Sreej1305 as part of the Reasona AI Decision Justification initiative.*
