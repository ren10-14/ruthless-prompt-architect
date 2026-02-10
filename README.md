# Ruthless Prompt Architect (Meta-Prompt)

A systematic, engineering-grade meta-prompt for creating robust, safe, and production-ready LLM prompts. Designed to force LLMs (like GPT-4, Claude, or local models) to generate prompts that are resistant to hallucinations, prompt injection, and misalignment.

## 🎯 Core Idea
Most prompts are vague. This prompt is a **specification**. It turns prompt engineering from an art into a repeatable engineering process with safety checks, priority fallback, and a catastrophic failure protocol.

## 📁 Repository Structure
- `prompts/` - Source meta-prompts.
  - `ruthless_architect_EN.md` - English version.
  - `ruthless_architect_RU.md` - Russian version.
- `cases/` - Real-world examples by language.
  - `cases/en/` - Examples in English.
  - `cases/ru/` - Examples in Russian.
- `README_RU.md` - Russian documentation.

## 🚀 Quick Start
1.  Copy the prompt from `prompts/ruthless_architect_EN.md` (or `_RU.md` for Russian).
2.  Feed it to your target LLM (GPT-4, Claude, Gemma, etc.).
3.  Answer its three diagnostic questions (Objective, Input, Anti-Goals).
4.  Receive a structured, production-ready prompt.

**See working examples:**
- [Tech Consultant (English)](./cases/en/tech_consultant.md)
- [Tech Consultant (Russian)](./cases/ru/tech_consultant.md)

## 🔧 Key Features
- **CO-STAR+ Framework:** Extended with Priority & Fallback system.
- **Anti-Goals Definition:** Forces consideration of model weaknesses.
- **Catastrophic Failure Protocol:** Hard stop on safety/format violations.
- **Vulnerability Self-Check:** The prompt includes instructions for the LLM to critique its own output.

## 🛡️ Safety & Ethics
This meta-prompt includes an automatic security protocol to reject requests for generating harmful, unethical, or malicious content. It prioritizes safety over all other objectives.

---
*Created with a focus on deterministic output and real-world application. Not just a template — an engineering framework.*
