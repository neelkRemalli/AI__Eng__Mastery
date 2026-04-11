# 🏢 AI System Architect Roadmap: Training Series
Welcome to my AI System Architect training repository. This project documents a multi-stage journey from cloud-based LLM integration to local deployment and high-level system design.

## 🚀 Project Overview
This repository contains 8 progressive labs focused on mastering AI infrastructure, prompt engineering, and local model deployment.

---

## 🛠️ Technical Stack
- **Languages:** Python 3.10+
- **Frameworks:** Gradio (UI Layer), OpenAI SDK
- **Providers:** OpenRouter (Cloud), Ollama (Local - Upcoming)
- **Infrastructure:** Google Colab (Testing), Dell Precision T5500 Workstation (Deployment)

---

## 🧪 Labs Directory

### [Lab 01] - Cloud-Based LLM Playground (Current)
- **Objective:** Build a functional UI to interact with Cloud LLMs (Gemini 2.0 via OpenRouter).
- **Core Concepts:** Inference Pipelines, API Integration, Hyperparameter Tuning (Temperature, Max Tokens).
- **Status:** ✅ Completed
- day-03 Live Demo: https://huggingface.co/spaces/neelkRemalli/ai-system-architect-lab01

### [Lab 02] - Enterprise RAG Pipeline for Customer Support
- **Objective:** To architect and deploy a high-performance Retrieval-Augmented Generation (RAG) pipeline entirely within the Google Colab ecosystem. This project focuses on leveraging cloud-elasticity to process multi-document datasets without the need for local hardware maintenance or upfront infrastructure costs.
- **Core Concepts:** Cloud-Native Orchestration: Using Google Colab's ephemeral environments to manage document ingestion, semantic chunking, and real-time inference.

Elastic Vector Storage: Utilizing Google Drive as a persistent storage layer for FAISS indices, ensuring that vector data survives across different Colab sessions.

API-First Intelligence: Integrating Gemini 3 Flash (via Google AI Studio) to provide low-latency, high-reasoning capabilities while staying within the generous free-tier quotas available in 2026.
- **Status:** 📅 Completed

### [Lab 03] - Get Weather
- **Objective:** Manual Orchestration: Understanding how to bridge the gap between LLM reasoning and Python execution without using high-level frameworks like LangChain.
Structured Output Control: Forcing the LLM to adhere to a specific JSON schema for reliable parsing.
Introspection: Using Python's inspect module to dynamically generate tool definitions from function signatures.
- **Core Concepts:** The ReAct Loop (Think/Act/Observe): The model thinks about the query, acts by generating a TOOL_CALL, and expects the system to provide an observation (the result).
Function Schemas: Converting Python logic into a language the LLM understands (JSON description of parameters and types).
Parsing Strategy: Using Regular Expressions (re) to isolate structured commands from unstructured conversational text.
- **Status:** 📅 Completed

### [Lab 04] - Agentic Workflows & Tool Use
- **Objective:** Computer Vision Integration: Bridge the gap between raw visual data and nutritional intelligence using GPT-4o-Vision.
Seamless UX/UI: Provide a high-performance, responsive interface using Gradio for real-time user interaction.
Architectural Decoupling: Implement a "Model-Agnostic" backend via OpenRouter to ensure the system can swap LLM providers without code refactoring.
- **Core Concepts:** Vision-to-JSON Pipeline: The system bypasses traditional OCR by using multimodal LLMs to interpret food volume and type directly into structured JSON.
Stateless Execution: Leveraging memory buffers (BytesIO) to process images in-RAM, ensuring high speed and compatibility with ephemeral cloud environments like Hugging Face.
CSS Injection for Branding: Utilizing advanced CSS overrides to transform a standard Gradio layout into a professional, branded dashboard
- **Status:** 📅 completed

### [Lab 05] - Agentic Workflows & Tool Use
- **Objective:** Building an AI agent that can execute Python code and search the web.
- **Core Concepts:** Function Calling, ReAct Logic, Autonomous Agents.
- **Status:** 📅 Planned

---



