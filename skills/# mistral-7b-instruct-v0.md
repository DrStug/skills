# mistral-7b-instruct-v0.3 Skills - Odysseus

**Model**: `mistral-7b-instruct-v0.3`  
**Host**: `host.docker.internal:1234`  
**Base URL**: `http://host.docker.internal:1234/v1`

## Capabilities
- Strong instruction-tuned 7B model
- Creative writing and roleplay

## Recommended Use Cases
- Storytelling
- Creative tasks
- Chatbot personalities

## Odysseus Routing Tag
`@mistral`

## Example Call
```bash
curl http://host.docker.internal:1234/v1/chat/completions \
  -H "Content-Type: application/json" \
  -d '{
    "model": "mistral-7b-instruct-v0.3",
    "messages": [{"role": "user", "content": "Your prompt here"}]
  }'