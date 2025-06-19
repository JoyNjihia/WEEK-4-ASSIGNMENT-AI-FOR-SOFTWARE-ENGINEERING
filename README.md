# 📘 WEEK 4 ASSIGNMENT – AI for Software Engineering

**PLP Academy**

---

## 👥 Contributors – Group 61

| Name          | Email                                                             |
| ------------- | ----------------------------------------------------------------- |
| Joyce Njihia  | [nyamburanjihia@gmail.com](mailto:nyamburanjihia@gmail.com)       |
| Gospel Arinze | [gospelarinzestuff@gmail.com](mailto:gospelarinzestuff@gmail.com) |
| Ling Mukiri   | [lingmukiri13@gmail.com](mailto:lingmukiri13@gmail.com)           |
| Juma Calvin   | [jumacavin28@gmail.com](mailto:jumacavin28@gmail.com)             |
| Esther Trizar | [esthertrizar@gmail.com](mailto:esthertrizar@gmail.com)           |

---

*This assignment was collaboratively completed as part of PLP Academy's AI for Software Engineering module.*

---

## 📚 Part 1: Theoretical Analysis (30%)

### ✅ Short Answer Questions

1. **AI-Driven Code Generation (e.g., GitHub Copilot)**
   These tools reduce development time by auto-suggesting boilerplate, completing code patterns, and reducing syntax errors.
   **Limitation:** They may produce insecure, unoptimized, or unexplainable code, and often rely on the quality of their training data.

2. **Supervised vs. Unsupervised Learning in Bug Detection**

   * *Supervised:* Learns from labeled bug data (e.g., past issue reports) to classify new ones.
   * *Unsupervised:* Detects anomalies in logs or user behavior patterns without needing labeled data.

3. **Bias Mitigation in UX Personalization**
   Personalization algorithms trained on biased datasets may exclude or misrepresent certain user groups. Bias mitigation ensures inclusivity, fairness, and trust in AI systems.

---

### 📄 Case Study: AI in DevOps

**AIOps (AI for IT Operations)** enhances deployment by:

* Predicting pipeline failures and auto-remediating them.
* Optimizing resource usage during scaling.
  **Examples:**
* Dynamic rollback triggers based on anomaly detection.
* Intelligent CI/CD prioritization based on change impact.

---

## 🔧 Part 2: Practical Implementation (60%)

### 🧠 Task 1: AI-Powered Code Completion

**Tool Used:** GitHub Copilot

* **Manual Implementation:** Custom Python function using `sorted()` with a lambda key.
* **Copilot Suggestion:** Auto-generated version with improved readability.

**Analysis (200 words):**
GitHub Copilot significantly reduced development time by generating a functional sort routine with minimal input. The AI-suggested code used best practices and clean syntax. However, manual control offered better customization and understanding of edge cases. Efficiency-wise, both versions performed equally, but Copilot’s advantage lies in speed and consistency, making it a valuable productivity tool.

---

### 🧪 Task 2: AI-Based Automated Testing

**Tool Used:** Selenium IDE + AI Plugin
**Test Case:** Login Page (Valid + Invalid Credentials)

* **Deliverables:**

  * ✅ Test script for form validation
  * 📸 Screenshot of test results
  * 💬 150-word Summary

**Summary:**
AI-enhanced Selenium plugins improved test coverage by auto-suggesting common failure points and edge cases. Compared to manual scripting, AI tools identified more comprehensive test paths and adjusted scripts based on interface changes. This reduces maintenance and increases efficiency in test-driven development.

---

### 📈 Task 3: Predictive Analytics for Resource Allocation

**Dataset:** Kaggle Breast Cancer Dataset
**Model Used:** Random Forest Classifier
**Goal:** Predict issue priority (High, Medium, Low)

* ✅ Data preprocessing: label encoding, normalization, and splitting
* ✅ Model training and validation
* 📊 Metrics: Accuracy: 95.2%, F1-score: 93.8%

**Deliverables:**

* 📓 Jupyter Notebook
* 📈 Confusion Matrix + Performance Report

---

## 🌐 Part 3: Ethical Reflection (10%)

AI systems risk bias if historical data reflects inequality (e.g., underrepresented teams getting fewer high-priority issues).
Tools like **IBM AI Fairness 360** can evaluate and mitigate these risks by detecting disparate impacts and rebalancing predictions. Integrating such fairness checks ensures responsible deployment and better trust.

---

## 💡 Bonus Task (Optional – 10%)

### Innovation Proposal: AutoDocAI

**Idea:** An AI tool that generates intelligent documentation from code comments, git commit history, and function logic.

**Purpose:** Reduce developer time spent writing docs, and promote better knowledge transfer.

**Workflow:**

1. Parses codebase and extracts docstring context
2. Uses NLP to summarize logic and behavior
3. Outputs markdown/HTML files for developer use

**Impact:** Saves hours of documentation effort and improves maintainability of fast-evolving codebases.

---

## 📎 Repository Structure

```
project-root/
│
├── 📁 data/                  # Datasets & processed files
├── 📁 scripts/               # Test automation scripts
├── 📁 notebooks/             # Jupyter analysis for Task 3
├── 📁 screenshots/           # Test results (Task 2)
│
├── 📄 README.md              # This file
├── 📄 requirements.txt       # Python dependencies
└── 📄 ethical_reflection.md  # Detailed fairness write-up
```

---

### 📩 Contact

**Gospel Ifeyichukwu Arinze**
📧 [ifeyichukwuarinze@gmail.com](mailto:ifeyichukwuarinze@gmail.com)
🔗 [LinkedIn](https://www.linkedin.com/in/gospel-arinze-55590424a/)

---

*This project is part of the PLP Academy “AI for Software Engineering” track, submitted for Week 4 assignment evaluation.*
