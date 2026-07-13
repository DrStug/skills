name: Local Programming Models
description: Flexible programming skills using multiple local LLMs. Routes based on task and chosen model.
version: 1.0
type: skill
tags: [programming, coding, software-engineering, debugging]
---

# Local Programming Models Skill

**This skill provides access to multiple local coding models.**

## Available Models

| Model                        | Strength                              | Best For                          |
|-----------------------------|---------------------------------------|-----------------------------------|
| qwen3-coder:30b             | Excellent code quality                | Complex projects, refactoring     |
| qwen2.5-coder-14b           | Strong modern coding                  | Web dev, TypeScript, daily tasks  |
| deepseek-r1:latest          | Strong reasoning & algorithms         | Algorithms, math-heavy code       |
| qwen3.6:35b                 | Good general coding                   | Large context tasks               |
| mistral-7b-instruct-v0.3    | Creative & fast scripting             | Scripts, creative coding          |
| gemma4:e4b / gemma-4-e4b    | Very fast                             | Quick prototypes & small scripts  |
| qwen3.5-9b                  | Balanced                              | General use                       |
| deepseek-r1:1.5b            | Ultra fast                            | Simple tasks                      |

---

## Instructions for Use

- **Do not default** to one model.
- **Ask the user** which model to use if not specified.
- **Analyze the task** and suggest the best model when appropriate.
- Support all major programming languages: Python, JavaScript, TypeScript, Java, C++, Rust, Go, SQL, Bash, HTML/CSS, etc.

**When the user specifies a model** (e.g. "use qwen3-coder:30b"), always respect and use that model.

**When no model is specified**, recommend the most suitable one based on the task and explain why.
