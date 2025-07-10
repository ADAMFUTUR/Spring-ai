# MCP-Spring-Python-AI: Multi-Protocol Chatbot 🚀  

![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)  
![Spring Boot](https://img.shields.io/badge/Spring%20Boot-3.x-brightgreen.svg)  
![Angular](https://img.shields.io/badge/Angular-20.x-red.svg)  
![Python](https://img.shields.io/badge/Python-3.x-blue.svg)  
![NodeJS](https://img.shields.io/badge/NodeJS-18+-green.svg)  

A **Model Context Protocol (MCP)**-based chatbot integrating **Spring Boot (AI + Ollama)**, **Python/NodeJS MCP servers**, and an **Angular frontend**.  

**Author**: [ER-RAHOUTI ACHRAF](https://github.com/your-profile)  

---

## 📌 Table of Contents  
- [Overview](#-overview)  
- [Key Features](#-key-features)  
- [Architecture](#-architecture)  
- [Installation](#-installation)  
- [Usage](#-usage)  
- [Technologies](#-technologies)  
- [Configuration](#-configuration)  
- [Testing](#-testing--debugging)  
- [Screenshots](#-screenshots)  

---

## 🌟 Overview  
A modular chatbot demonstrating **MCP protocol** implementation with:  
- **Spring Boot** (SSE-based MCP client/server)  
- **Python/NodeJS** (STDIO-mode MCP tools)  
- **Angular** frontend for interactive chat.  

---

## ✨ Key Features  
- **Multi-Backend Integration**:  
  - Spring AI + Ollama (Qwen3 model)  
  - Python/NodeJS MCP servers for tool execution.  
- **Real-Time Communication**: SSE for streaming responses.  
- **Agent-Based UI**: Angular frontend with thinking/reply distinction.  
- **Tool Ecosystem**: Stock lookup, file ops, employee info, etc.  

---

## 🏗️ Architecture  
mcp-spring-python-ai/
├── mcp-client/ # Spring Boot MCP Client
│ ├── src/main/java/
│ │ └── net/achraf/mcpclient/
│ │ ├── agents/ # AI agents
│ │ └── controllers/ # REST controllers
│ ├── src/main/resources/
│ │ ├── application.properties
│ │ └── mcp-servers.json
│ └── pom.xml
├── mcp-server/ # Spring Boot MCP Server
│ ├── src/main/java/
│ └── pom.xml
├── mcp-frontend/ # Angular Frontend
│ ├── src/app/
│ │ ├── app.component.ts
│ │ ├── app.component.html
│ │ └── app.component.css
│ ├── package.json
│ └── angular.json
├── python-mcp-server/ # Python MCP Server
│ ├── server.py
│ ├── main.py
│ └── pyproject.toml
├── Screenshots/ # Project screenshots
└── README.md

### ⚙️ Installation

#### Prerequisites
- [Ollama](https://ollama.ai/) (`ollama pull qwen3`)
- [Node.js 18+](https://nodejs.org/)
- Angular CLI (`npm install -g @angular/cli`)
- [Postman](https://www.postman.com/) (for API testing)

#### Steps:
1. **Clone & Navigate**:
   ```bash
   git clone https://github.com/your-username/mcp-spring-python-ai.git  
   cd mcp-spring-python-ai  
