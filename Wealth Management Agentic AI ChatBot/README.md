# Build a Wealth Management Agentic AI Chatbot with MS Fabric

## Overview

Managing personal wealth involves analyzing diverse financial data, assessing risks, and designing investment strategies. Traditionally, this requires significant manual effort and expertise. This project introduces an **Agentic AI-powered financial assistant** built with **LangChain**, **Microsoft Fabric**, and **ChromaDB**. The system autonomously analyzes financial portfolios, evaluates risks, and generates personalized investment strategies through a multi-agent framework.

By combining **Agentic AI**, **OpenAI GPT models**, and **Microsoft Fabric components** such as OneLake, Lakehouse, and Data Warehouse, this project demonstrates how intelligent automation can enhance wealth management. Users interact with the system through an **HTML chatbot interface** powered by a **Flask API**, making real-time, context-aware financial recommendations possible.

> **Note:** Before starting, ensure completion of prerequisite projects: LLM Project for model fine-tuning and Microsoft Fabric Financial Reporting Agent project.

## Project Objectives

- Understand how **Agentic AI** enables autonomous decision-making via task selection.  
- Use **LangChain agents** to decompose complex financial risk analysis into modular components.  
- Implement **agentic execution chains** to dynamically invoke relevant financial tools.  
- Store and retrieve financial data using **Microsoft Fabric OneLake, Lakehouse, and Data Warehouse**.  
- Implement **ChromaDB vector store** for long-term memory and context-aware recommendations.  
- Build a **Flask API** as the agent execution engine for real-time queries.  
- Create Python functions for **portfolio risk evaluation** and **asset diversification analysis**.  
- Configure LangChain agents to orchestrate **multi-step AI-driven financial processes**.  
- Develop an **HTML chatbot interface** for real-time interaction with the agent.  
- Retain **user-specific financial preferences** using long-term memory modules.

## Introduction to the Wealth Management Agentic AI Project

This project extends the Microsoft Fabric Financial Reporting Agent by adding **Agentic AI capabilities**. Unlike traditional systems, which rely on predefined workflows, the agent autonomously selects financial tools and executes complex workflows based on user intent.  

The system operates through specialized tools such as stock position analysis, portfolio risk assessment, investment strategy generation, and risk mitigation modeling. Using reasoning and memory retention via **ChromaDB**, the assistant provides **personalized, context-aware recommendations** rather than one-time responses.

## Prerequisites

Before starting this project, ensure you have:

- Completed the **LLM Project** for building and fine-tuning large language models.  
- Completed the **Microsoft Fabric Financial Reporting Agent Project**.  
- Basic knowledge of **LLMs, Python, Streamlit, and Flask**.  
- Familiarity with **Azure Cloud**, **Microsoft Fabric**, and **vector databases**.  

> **Important:** Using Microsoft Fabric and Azure services may incur costs. A 60-day free trial is available for testing features.

## How to Build the Wealth Management Agent

This project guides you through building a **multi-agent financial assistant** using LangChain and Microsoft Fabric. The system executes autonomous financial analysis, dynamically selects tools, and provides interactive responses through a Flask-based chatbot interface.

## Tech Stack

- **Language**: Python 3.9  
- **Libraries**: pandas, numpy, Azure SDK, langchain, openai, Flask  
- **Cloud Platform Components**: Microsoft Fabric (OneLake, Lakehouse, Data Warehouse)  
- **Model**: Retrieval-Augmented Generation (RAG) with GPT  
- **API Framework**: Flask API with HTML frontend  
- **Vector Store**: ChromaDB  

## Solution Approach

### 1. Defining the Goal and Task Decomposition
- Establish the main goal: **assess financial risks and provide mitigation strategies**  
- Break down tasks:
  - Analyze stock positions and portfolio distribution  
  - Identify and quantify risk exposure (market volatility, diversification gaps)  
  - Generate tailored risk mitigation strategies  
  - Refine recommendations based on user feedback  

### 2. Building the Agentic AI Framework
- Develop an autonomous **LangChain agent** for dynamic tool selection  
- Use **Chain of Thought reasoning** to optimize decision-making  
- Implement **task selection logic** for goal-driven execution  

### 3. Creating Modular Financial Analysis Tools

#### Stock Position Analysis Tool
- Retrieves portfolio composition from Microsoft Fabric  
- Evaluates stock performance and volatility  

#### Risk Calculation Tool
- Computes exposure, diversification, and historical risk trends  
- Evaluates risk-to-reward ratios for assets  

#### Risk Mitigation Tool
- Suggests reallocation, hedging strategies, or alternative investments  
- Adjusts recommendations based on user risk profile  

### 4. Implementing Memory Management
- Store conversation history and financial preferences in **ChromaDB**  
- Enable context-aware and personalized recommendations  

### 5. Developing Decision-Making Logic
- Implement **intent detection** to classify user queries:
  - Risk Analysis  
  - Investment Planning  
  - Fallback for unrelated queries  
- Dynamically invoke appropriate financial analysis tools  

### 6. Creating a Flask-Based API
- Develop **Flask endpoints** to handle user queries  
- Route queries to agents and tools, return responses  
- Integrate with **HTML chatbot UI** for real-time interaction  
- Store conversation history and maintain context  

## Expected Outcomes

By completing this project, you will:

- Build a production-grade **Agentic AI financial assistant**  
- Gain hands-on experience with **LangChain multi-agent orchestration**  
- Learn to integrate **Microsoft Fabric** for structured and unstructured data storage  
- Implement **contextual memory** for personalized, long-term recommendations  
- Develop an interactive **Flask-based chatbot UI** for financial advisory  

## Project Link

[Build a Wealth Management Agentic AI Chatbot with MS Fabric](https://www.projectpro.io/project-use-case/wealth-management-agentic-ai-chatbot)

## Next Steps

- Extend the assistant with **real-time stock market integration**  
- Implement **voice interaction capabilities** using speech APIs  
- Add **persistent memory modules** for long-term financial planning  
- Deploy on **Azure Cloud** for scalability and accessibility  
- Integrate with **Microsoft Teams or Slack** for enterprise usage
