# DonnySavage Bot API Documentation

Programmatic access to Discord bot functionality and server data via REST API.

## 🔑 Authentication
- **API Key Generation**:  
  Use Discord command:  
  `/auth generate-key service="Your Service Name"`
- **Header Requirement**:  
  `x-api-key: YOUR_API_KEY`
- **Base URL**:  
  `http://bot.api.donnysavagebot.publicvm.com/`
- **Learn More**: [Full Documentation](https://abdo9616.github.io/DonnySavageApiDocumentationGuide.github.io/)

## 🚀 Getting Started
1. Generate API key via Discord command
2. Test authentication:
   ```bash
   curl.exe -H "x-api-key: YOUR_API_KEY" http://bot.api.donnysavagebot.publicvm.com/api/secure-data
