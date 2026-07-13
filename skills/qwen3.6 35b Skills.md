# qwen3.6:35b Skills - Odysseus

**Model**: `qwen3.6:35b`  
**Host**: `host.docker.internal:11434`  
**Base URL**: `http://host.docker.internal:11434/v1`

## Capabilities
- Strong general-purpose 35B model
- Excellent multilingual support
- Robust reasoning

## Recommended Use Cases
- Research
- Content creation
- Complex multi-step tasks

## Odysseus Routing Tag
`@qwen-general`

## Example Call
```bash
curl http://host.docker.internal:11434/v1/chat/completions \
  -H "Content-Type: application/json" \
  -d '{
    "model": "qwen3.6:35b",
    "messages": [{"role": "user", "content": "Your prompt here"}]
  }'
