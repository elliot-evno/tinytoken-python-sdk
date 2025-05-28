# TinyToken

Text compression API client.

## Install

```bash
pip install tinytoken
```

## Usage

```python
import tinytoken

# Compress text
result = tinytoken.compress("Your text here", "your-api-key")
print(result)

# Or use the class
client = tinytoken.TinyToken("your-api-key")
result = client.compress("Your text here")
print(result)
```
