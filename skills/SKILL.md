name: local-programming-models-pack
description: Specialized skills for code generation across multiple programming languages using local LLMs
version: 1.0
type: skill-pack
status: published
tags: [coding, programming, software-development, debugging, python, javascript, rust, go]
models:
  - qwen3-coder:30b
  - qwen2.5-coder-14b
  - deepseek-r1:latest
  - qwen3.6:35b
  - mistral-7b-instruct-v0.3
  - gemma4:e4b
---

# Local Programming Models Pack

**Purpose**: Enable high-quality code generation, refactoring, debugging, and architecture tasks using locally hosted models.

**Best Used For**:
- Writing new code
- Debugging existing code
- Code review and refactoring
- Learning new languages/frameworks

**Routing Logic**:
- Default → `qwen3-coder:30b`
- Algorithmic / Complex logic → `deepseek-r1:latest`
- Fast prototyping → `gemma4:e4b` or `mistral-7b-instruct-v0.3`

**Supported Languages**: Python, JavaScript, TypeScript, Java, C++, Rust, Go, SQL, Bash, and more.

---
