# OpenAI Agent Builder

<img width="1280" height="720" alt="image" src="https://github.com/user-attachments/assets/d0644786-e727-49f4-b7b2-bdca2a892856" />


This repository contains resources and projects related to building AI agents using OpenAI's technologies, focusing on Retrieval-Augmented Generation (RAG) and specialized agent instructions.

## Repository Structure

### 1. RAG Project (`RAG_project/`)
This directory houses a complete RAG implementation setup, including datasets and agent configurations.

*   **`RAG_agent/`**: Contains the specific instructions and logic for different types of agents:
    *   **Health Agent** (`health_agent_instructions.txt`): specialized in answering health-related queries using file search.
    *   **Finance Agent** (`finance_agent_instructions.txt`): Specialized in analyzing financial reports and data.
    *   **Generic Agent** (`generic_agent_instructions.txt`): Handles general queries, utilizing web search when necessary.
    *   **Classifier Agent** (`Classifier_agent_instructions.txt`): Likely routes user queries to the appropriate specialist agent.
    *   **Guide**: `Step_by_Step_RAG.pdf` offers a walkthrough of the RAG process.

*   **`rag-dataset-main/`**: A comprehensive dataset used for the RAG system, containing:
    *   **Finance Data**: 10-K/10-Q reports, tables, and financial documents (e.g., for Meta).
    *   **Health/Gym Data**: PDFs and documents related to supplements, fitness, and health research.

### 2. Basics (`Basics_of_open_ai_agent_builder/`)
Contains introductory materials and guides for understanding and using the OpenAI Agent Builder.
*   *Intro to Open AI agent builder.pdf*
*   *openai-agent-builder-guide.md*

## specialized Agents

The project defines distinct personas for agents to ensure high-quality, domain-specific responses:

*   **Health Agent**: Strictly uses file search to answer medical queries, citing evidence from provided documents.
*   **Finance Agent**: Analyzes financial documents to provide data-backed answers with strict reasoning.
*   **Generic Agent**: A versatile assistant that balances internal knowledge with web search for real-time information.

## Getting Started

1.  Review the `Step_by_Step_RAG.pdf` in the `RAG_agent` folder to understand the workflow.
2.  Explore the `rag-dataset-main` to see the types of documents the agents can query.
3.  Use the instruction files in `RAG_agent` to configure your OpenAI Assistants or compatible agent framework.

## Author

**Ashu Mishra**  
Connect on LinkedIn: [https://www.linkedin.com/in/ashumish/](https://www.linkedin.com/in/ashumish/)
