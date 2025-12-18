```markdown
# 🤖 AI Prompt Injection & Red Teaming Research

## 🎯 Goal
Investigating **Jailbreak techniques** on Vietnamese Large Language Models (LLMs) to identify vulnerabilities and propose better **Guardrails**.

## 🧪 Methodology
1. **Dataset Creation:** Building `vn-malicious-prompts.csv` containing harmful intents specific to Vietnamese culture/slang.
2. **Techniques:** - DAN (Do Anything Now) adaptation.
   - Developer Mode simulation.
   - Fine-tuning attacks using LoRA.

## 📂 Repository Structure
- `/dataset`: Contains raw and processed prompt datasets.
- `/scripts`: Python scripts for automated testing against local LLMs.
- `/results`: Analysis of successful jailbreaks.

## ⚠️ Disclaimer
This project is for **Educational Purposes** and **Red Teaming** only.
