# deepseek-r1:latest Skills - Odysseus

**Model**: `deepseek-r1:latest`  
**Host**: `host.docker.internal:11434`  
**Base URL**: `http://host.docker.internal:11434/v1`

## Capabilities
- Latest DeepSeek R1 reasoning model
- Strong logical thinking and problem solving

## Recommended Use Cases
- Complex reasoning chains
- Math and logic problems
- Research assistance

## Odysseus Routing Tag
`@deepseek`

## Example Call
```bash
curl http://host.docker.internal:11434/v1/chat/completions \
  -H "Content-Type: application/json" \
  -d '{
    "model": "deepseek-r1:latest",
    "messages": [{"role": "user", "content": "Your prompt here"}]
  }'