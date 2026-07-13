# gemma4:e4b Skills - Odysseus

**Model**: `gemma4:e4b`  
**Host**: `host.docker.internal:11434`  
**Base URL**: `http://host.docker.internal:11434/v1`

## Capabilities
- Efficient 4B parameter model
- Good instruction following
- Balanced performance

## Recommended Use Cases
- General chat
- Fast responses
- Daily assistant tasks

## Odysseus Routing Tag
`@gemma-fast`

## Example Call
```bash
curl http://host.docker.internal:11434/v1/chat/completions \
  -H "Content-Type: application/json" \
  -d '{
    "model": "gemma4:e4b",
    "messages": [{"role": "user", "content": "Your prompt here"}]
  }'