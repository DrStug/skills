# SKILL.md - Odysseus Local Models Skills

**Repository:** Local Programming Models  
**Focus:** Code generation, software engineering, debugging, architecture, and multi-language programming support.

---

## 📋 Available Skills

### Primary Coding Models
- **[qwen3-coder-30b-skills.md](qwen3-coder-30b-skills.md)** — Best overall coding model (30B)
- **[qwen2.5-coder-14b-skills.md](qwen2.5-coder-14b-skills.md)** — Excellent mid-size coding specialist
- **[deepseek-r1-latest-skills.md](deepseek-r1-latest-skills.md)** — Strong reasoning & algorithmic coding

### General Purpose Models
- **[qwen3.6-35b-skills.md](qwen3.6-35b-skills.md)** — Strong general + coding performance (35B)
- **[qwen3.5-9b-skills.md](qwen3.5-9b-skills.md)** — Balanced 9B model
- **[mistral-7b-instruct-v0.3-skills.md](mistral-7b-instruct-v0.3-skills.md)** — Creative coding & scripting

### Fast / Lightweight Models
- **[gemma4-e4b-skills.md](gemma4-e4b-skills.md)** — Fast 4B model (Host 11434)
- **[gemma-4-e4b-skills.md](gemma-4-e4b-skills.md)** — Fast 4B model (Host 1234)
- **[deepseek-r1-1.5b-skills.md](deepseek-r1-1.5b-skills.md)** — Ultra-lightweight model

---

## 📊 Master Overview
**[programming-skills-overview.md](programming-skills-overview.md)** — Detailed comparison of all models' programming strengths, language support, and routing recommendations.

---

## Usage in Odysseus
All models are accessible via their respective hosts:
- **Host 1**: `http://host.docker.internal:11434/v1`
- **Host 2**: `http://host.docker.internal:1234/v1`

**Recommended Routing Tags** (used in prompts):
- `@qwen-coder` → qwen3-coder:30b
- `@qwen-coder-mid` → qwen2.5-coder-14b
- `@deepseek` → deepseek-r1:latest
- `@fast` → gemma4:e4b or gemma-4-e4b

---

**This repository provides specialized programming skills for all your local models.**
