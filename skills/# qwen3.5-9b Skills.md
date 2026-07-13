# qwen3.5-9b Skills - Odysseus

**Model**: `qwen3.5-9b`  
**Host**: `host.docker.internal:1234`  
**Base URL**: `http://host.docker.internal:1234/v1`

## Capabilities
- Balanced 9B general model
- Good speed vs quality trade-off

## Recommended Use Cases
- Everyday tasks
- General assistance

## Odysseus Routing Tag
`@qwen-mid`

## Example Call
```bash
curl http://host.docker.internal:1234/v1/chat/completions \
  -H "Content-Type: application/json" \
  -d '{
    "model": "qwen3.5-9b",
    "messages": [{"role": "user", "content": "Your prompt here"}]
  }'