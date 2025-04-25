# Health-and-Wellness-Chatbot

## Overview
This project presents a Health Assistant built using cutting-edge technologies like LangChain, OpenAI's GPT-3.5 Turbo, Azure, FAISS, and LangGraph to provide personalized workout and diet recommendations. The assistant uses advanced prompting techniques such as zero-shot, few-shot, and chain-of-thought prompting to generate tailored advice for users. It also includes a custom dataset fine-tuning for better health insights, the use of embeddings with FAISS vector stores for fast retrieval of relevant context, and integrated Azure tools for system optimization and monitoring.

## Features
- Personalized Health Recommendations: Powered by GPT-3.5 Turbo, providing tailored workout and diet plans.

- Advanced Prompting Techniques: Utilized zero-shot, few-shot, and chain-of-thought methods to create context-aware, responsive health advice.

- Fine-tuning with Custom Dataset: The model was fine-tuned with a specific health-related dataset to improve the relevance and accuracy of recommendations.

- Efficient Context Retrieval: Employed OpenAI embeddings and FAISS vector stores to quickly retrieve relevant information based on the user's needs.

- Optimized Workflow: Integrated Azure Prompt Flow, LangGraph, and LangSmith for monitoring and optimizing the system performance.

- Adversarial Testing: Simulated adversarial input with hacking prompts to test vulnerabilities, followed by the implementation of defense strategies to make the assistant more robust.

## Technologies Used
- LangChain: Framework for building complex language-based applications, integrating multiple tools and models seamlessly.

- OpenAI GPT-3.5 Turbo: Language model for generating health advice and recommendations.

- Azure: Platform used for managing workflows and providing cloud-based infrastructure for scaling.

- FAISS: A library for efficient similarity search and clustering of embeddings, used for fast context retrieval.

- LangGraph: A tool for managing and optimizing the interactions between different components in the pipeline.

- LangSmith: Monitoring and observability tool for tracking model performance and optimizing prompts.

## How It Works
- User Input: The user provides their preferences, goals, and current health status.

- Contextual Understanding: The assistant uses FAISS to retrieve relevant context (e.g., workout routines, nutritional plans) based on the user's input.

- Model Interaction: The fine-tuned GPT-3.5 Turbo model processes the user's input and generates personalized recommendations using a combination of zero-shot, few-shot, and chain-of-thought prompting.

- Optimization: Using Azure Prompt Flow and LangGraph, the system dynamically adjusts based on performance feedback and optimizes the model responses.

- Security & Defense: To improve robustness, the assistant is tested against adversarial inputs (such as tricky prompts designed to confuse the model) and defensive strategies are implemented to prevent exploitation.

