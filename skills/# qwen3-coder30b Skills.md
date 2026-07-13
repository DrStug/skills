# qwen3-coder:30b Skills - Odysseus

**Model**: `qwen3-coder:30b`  
**Host**: `host.docker.internal:11434`  
**Base URL**: `http://host.docker.internal:11434/v1`

## Capabilities
- Strong coding specialist (30B)
- Excellent software engineering & debugging
- High-quality code generation

## Recommended Use Cases
- Programming tasks
- Code review
- Full-stack development assistance

## Odysseus Routing Tag
`@qwen-coder` or `@code`

## Example Call
```bash
curl http://host.docker.internal:11434/v1/chat/completions \
  -H "Content-Type: application/json" \
  -d '{
    "model": "qwen3-coder:30b",
    "messages": [{"role": "user", "content": "Write a Python function for..."}]
  }'