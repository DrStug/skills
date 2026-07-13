# qwen2.5-coder-14b Skills - Odysseus

**Model**: `qwen2.5-coder-14b`  
**Host**: `host.docker.internal:1234`  
**Base URL**: `http://host.docker.internal:1234/v1`

## Capabilities
- Excellent 14B coding model
- Strong code generation and understanding

## Recommended Use Cases
- Software development
- Code debugging
- Technical documentation

## Odysseus Routing Tag
`@qwen-coder-mid`

## Example Call
```bash
curl http://host.docker.internal:1234/v1/chat/completions \
  -H "Content-Type: application/json" \
  -d '{
    "model": "qwen2.5-coder-14b",
    "messages": [{"role": "user", "content": "Your prompt here"}]
  }'