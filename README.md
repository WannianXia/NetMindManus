
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT) &ensp;
# 👋 NetMindManus

Manus is incredible, but you can create your own with NetMind without any subscriptions! 🛫!


Edit `config/config.toml` to add your NetMind API keys and customize settings:

```toml
# Global LLM configuration
[llm]
model = "deepseek-ai/DeepSeek-V3-0324"        # The LLM model to use
base_url = "https://api.netmind.ai/inference-api/openai/v1"  # API endpoint URL
api_key = "Your NetMind API Key"                    # Your API key
max_tokens = 8192                           # Maximum number of tokens in the response
temperature = 0.0                           # Controls randomness


# Optional configuration for specific LLM models
[llm.vision]
model = "deepseek-ai/DeepSeek-V3-0324"        # The vision model to use
base_url = "https://api.netmind.ai/inference-api/openai/v1"  # API endpoint URL for vision model
api_key = "Your NetMind API Key"                    # Your API key for vision model
max_tokens = 8192                           # Maximum number of tokens in the response
temperature = 0.0                           # Controls randomness for vision model

```
