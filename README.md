# Building AI Agents with MCP Servers using PydanticAI and Groq

A hands-on implementation of a multi-MCP AI agent using PydanticAI and Groq API. Covers custom tools, MCP server integration (time + fetch), and connecting multiple servers to a single agent. Adapted from the AMD AI Academy tutorial to run on Kaggle with Groq as a free hosted inference backend.

## 📓 View Full Notebook
👉 [Run on Kaggle](https://www.kaggle.com/code/movinduhiripitiya/building-ai-agents-with-mcp-servers-using-pydantic?scriptVersionId=323362240)

## What this project does
- Connects Llama 3.3 70B via Groq to multiple MCP servers
- Uses mcp-server-time for real-time date and time
- Uses mcp-server-fetch to retrieve live web content
- Coordinates everything using PydanticAI as the agent framework

## Stack
- PydanticAI — agent framework
- Groq API — LLM inference (free)
- mcp-server-time — time MCP server
- mcp-server-fetch — web fetch MCP server
- Python 3.12

## How to run
1. Get a free Groq API key from console.groq.com
2. Add it to Kaggle Secrets as `groq-api-key`
3. Run all cells in order
