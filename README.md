# Evaluating Safety-Critical Behavior in Large Language Models
This repository contains reproducible evaluation code and analysis focusing on safety-critical behavior of Large Language Models (LLMs) across vulnerable user groups and high-risk interaction contexts.

The project evaluates how Google's Gemini and Meta's Llama respond to sensitive, unsafe, or exploitative scenarios, with an emphasis on preventive safeguards, refusal behavior, and timely intervention.

---

## 📌 Evaluation Focus Areas

The repository evaluates LLM behavior across three primary dimensions:

### 1. Content Safety
- Handling of proscribed or sensitive topics (e.g., self-harm, abuse, illicit activities)
- Appropriateness of refusals vs. safe redirection
- Clarity and consistency of safety-aligned responses

### 2. Minor Exposure Controls (Teen Safety)
- Protection against unsafe advice or encouragement for minors
- Exposure pacing for sensitive topics
- Boundary enforcement and age-appropriate responses

### 3. Elder-Targeted Scam Detection & Time-to-Intervene
- Real-time identification of common scam patterns targeting seniors
- Responsiveness and timeliness of warnings or intervention
- Balance between caution, clarity, and non-alarmist guidance

---

## 🧩 Core Project Components

This project integrates performance measurement modes such as **AIE, ADA, and HIC** perspectives to support a holistic ethical evaluation. The abbreviations are explained below.

### AIE — Automated Instrumental Evaluation 
- Logs API-based prompts and corresponding responses that are used for downstream evaluation of the above dimensions.

### ADA — Automated Documents Analysis (LLM-Based Document & Output Analysis)
- Programmatic analysis of guardrails mentioned for the above stated dimensions in the LLM's documentation.

### HIJ — Human Interactive Judgement
- Human-in-the-loop qualitative analysis of model responses

---

## 🧪 Methodology Overview

- Scenario-based prompt generation simulating real-world risk contexts  
- Controlled batch evaluation across multiple models  
- Quantitative and qualitative scoring using standardized rubrics

###

### Scoring Framework

Each metric is scored on a **0–3 scale**:

- **0** = Extremely deficient  
- **1** = Weak coverage  
- **2** = Adequate coverage  
- **3** = Excellent coverage  

Metrics include:
- Refusal rate  
- Safety alignment rate  
- Sensitive-topic exposure pacing  
- Intervention timing  
- Over- and under-blocking tendencies  

Metric weights are assigned based on ethical risk severity and user vulnerability.

---

## ⚙️ Reproducibility

- All experiments are designed to be fully reproducible
- Random seeds are fixed where applicable
- Model versions and configurations are explicitly documented
- Results are generated programmatically without manual post-processing

---

## 🎯 Ethical Motivation

As LLMs are increasingly deployed in contexts involving **children, seniors, and safety-critical decision-making**, this project aims to identify:

- Where models succeed in harm prevention  
- Where safeguards fail or overcorrect  
- How intervention timing and response framing affect user safety  

The goal is **comparative ethical analysis**, not model endorsement.

---

## 📎 Notes

- This repository is intended for academic and research use 
- No real user data is used
- All scenarios are synthetic and ethically framed
