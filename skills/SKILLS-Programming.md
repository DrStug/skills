# Programming Skills Overview - Odysseus Local Models

This document summarizes the **coding strengths** of all your local models for programming tasks across various languages.

**Last Updated**: July 2026  
**Focus**: Code generation, debugging, refactoring, architecture, documentation, and multi-language support.

---

## Model Comparison Table (Programming Focus)

| Model                        | Size   | Overall Coding Strength | Best Languages                              | Speed     | Recommended For                          |
|-----------------------------|--------|--------------------------|---------------------------------------------|-----------|------------------------------------------|
| `qwen3-coder:30b`           | 30B    | ★★★★★ Excellent         | Python, JS/TS, Java, C++, Rust, Go, SQL    | Medium    | Professional software engineering        |
| `qwen2.5-coder-14b`         | 14B    | ★★★★☆ Very Strong       | Python, TypeScript, Java, Go, Rust         | Fast      | Daily coding & debugging                 |
| `deepseek-r1:latest`        | ~1.5B+ | ★★★★☆ Strong            | Python, C++, Rust, Math-heavy code         | Very Fast | Algorithmic & reasoning-heavy coding     |
| `qwen3.6:35b`               | 35B    | ★★★★☆ Strong            | Python, JS/TS, Java, SQL, Bash             | Medium    | General + large codebase tasks           |
| `mistral-7b-instruct-v0.3`  | 7B     | ★★★☆☆ Good              | Python, JavaScript, C#, PHP, HTML/CSS      | Very Fast | Creative coding, scripts, web dev        |
| `gemma4:e4b` / `gemma-4-e4b`| 4B     | ★★★☆☆ Good              | Python, JavaScript, SQL, Bash              | Extremely Fast | Quick scripts & prototypes          |
| `deepseek-r1:1.5b`          | 1.5B   | ★★☆☆☆ Fair              | Python, basic C++/JS                       | Lightning | Ultra-fast lightweight tasks             |
| `qwen3.5-9b`                | 9B     | ★★★☆☆ Good              | Python, JS/TS, Java, Go                    | Fast      | Balanced general programming             |

---

## Detailed Programming Strengths

### 1. Top Tier Coding Models
- **`qwen3-coder:30b`** — Best overall coder. Excellent at complex projects, architecture, refactoring, and multi-language support.
- **`qwen2.5-coder-14b`** — Outstanding code quality for its size. Great for modern web/devops (TypeScript, Rust, Go).

### 2. Strong Reasoning + Coding
- **`deepseek-r1:latest`** — Superior at algorithmic problems, competitive programming, math-heavy code, and logical reasoning in code.

### 3. Balanced / General Purpose
- **`qwen3.6:35b`** — Very capable across most languages with strong context understanding.
- **`qwen3.5-9b`** — Solid all-rounder for everyday development.

### 4. Fast / Lightweight
- **`mistral-7b-instruct-v0.3`** — Good for creative scripting, web development, and quick iterations.
- **Gemma 4B variants** — Best for speed when you need quick code snippets or simple scripts.

---

## Supported Languages Summary

**Excellent Support**: Python, JavaScript, TypeScript, Java, C++, Rust, Go, SQL  
**Strong Support**: Bash/Shell, PHP, C#, Ruby, HTML/CSS, Dockerfile, YAML  
**Fair Support**: Swift, Kotlin, R, Scala, Haskell

---

## Odysseus Routing Recommendations (Programming)

```yaml
coding:
  primary: qwen3-coder:30b
  secondary: qwen2.5-coder-14b
  fast: gemma4:e4b
  algorithmic: deepseek-r1:latest

language-specific:
  python: qwen3-coder:30b
  typescript: qwen2.5-coder-14b
  rust: deepseek-r1:latest
  web: mistral-7b-instruct-v0.3
