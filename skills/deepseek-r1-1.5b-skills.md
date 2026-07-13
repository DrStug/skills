# deepseek-r1:1.5b Skills - Odysseus

**Model**: `deepseek-r1:1.5b`  
**Host**: `host.docker.internal:11434`  
**Base URL**: `http://host.docker.internal:11434/v1`

## Capabilities
- Fast lightweight reasoning
- Basic code generation and explanation
- Quick Q&A and instruction following

## Recommended Use Cases
- Rapid prototyping
- Lightweight agents
- Low-latency tasks

## Odysseus Routing Tag
`@deepseek-light` or `@fast-reason`

## Example Call (OpenAI compatible)
```bash
curl http://host.docker.internal:11434/v1/chat/completions \
  -H "Content-Type: application/json" \
  -d '{
    "model": "deepseek-r1:1.5b",
    "messages": [{"role": "user", "content": "Your prompt here"}]
  }'
