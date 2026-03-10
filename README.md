
![Logo](./public/FFFFFF-1.png)
# Slooze take home challenge-!!
**ROLE: Software Engineer AI**

## AI Agent Technical Challenges

This repository contains two technical challenges designed to evaluate a candidate’s ability to build **AI-powered systems using LLMs, external tools, and retrieval pipelines**.

The goal is to assess:
- Understanding of LLM integration
- System design for AI agents
- Data retrieval and processing
- Code structure and maintainability

Candidates may implement solutions for any/all of the challneges below, in **Python or Node.js**.

---

## Challenge A — AI Web Search Agent

### Objectives
Build an AI agent capable of searching the web and generating answers based on live internet information.

The system should demonstrate the ability to:
- Integrate an LLM
- Use external tools for information retrieval
- Synthesize responses using retrieved data
- Provide source references

### Tasks to be Performed

1. Build an agent that accepts a **natural language query** from a user.

2. Implement a **web search tool integration** using any provider such as:
   - DuckDuckGo
   - Tavily
   - SerpAPI
   - Any search API of your choice.

3. Retrieve the **top relevant search results**.

4. Pass the retrieved content to an **LLM** to generate a summarized answer.

5. Return a response that includes:
   - A clear answer
   - A list of sources used

**For eaxmple,**
  **Question input:** What are the latest specs in Macbook this year
  
  **Example output:**
  
  Answer:
  Recent MacBook Pro models feature Apple's latest M5 family chips for enhanced AI performance and efficiency. New models became available starting March 11, 2026
  
  Sources:
  [https://example.com/article1](https://www.apple.com/in/mac/compare/#:~:text=MacBook%20Pro%2014%E2%80%B3%20(M5))
  https://example.com/article2

### Expected Features

- Query processing
- Search tool integration
- Retrieval of relevant results
- LLM-based answer generation
- Source attribution
---
## Challenge B — AI Agent for PDF Summarization and Question Answering

### Objectives
Build an AI system capable of reading a PDF document, summarizing its content, and answering questions about the document.

The system should demonstrate:
- Document ingestion
- Text extraction
- Retrieval-Augmented Generation (RAG)
- Context-aware question answering

## Tasks to be Performed

1. Accept a **PDF file as input**.

2. Extract text content from the document.

3. Split the extracted text into **smaller chunks** for processing.

4. Generate **embeddings** for the chunks.

5. Store the embeddings in a **vector store** (e.g., FAISS, Chroma, Pinecone).

6. When a user asks a question:
   - Retrieve the most relevant document chunks
   - Provide them as context to an LLM
   - Generate a grounded answer

**For eaxmple,**
  **Question input:** Summarize the document
                      What methodology was used in the study?
  
  **Example output:**
  
  Answer:
  Summary:
  The document discusses the impact of AI-driven automation in enterprise
  workflows and evaluates productivity improvements across multiple
  organizations.

  Methodology: 
  The study used case studies combined with experimental evaluations
  across three enterprise environments.

### Expected Features

- PDF text extraction
- Chunking and embedding generation
- Vector similarity search
- Context-based answer generation
- Document summarization

---


## 📤 Submission
Provide a public or private GitHub repository containing your solution.
Your repository should include:
- README.md
  - Setup instructions
  - How to run the project
  - Dependencies used
  - Architecture overview
  - Design decisions and trade-offs
- agent/
- requirements.txt or package.json
**The repository should include clear instructions to run the project locally.**

> 💡 **Tip:** Creativity in your data analysis approach and depth in your insights will be rewarded. Think of this as a mini day-to-day job at Slooze.

## Connect with Us:

Reach out to **[interview@slooze.xyz](mailto:interview@slooze.xyz)** to submit your solutions or if you may have any questions related to the challenege

## © Copyright Notice

**© Slooze. All Rights Reserved.**

Please do not share or distribute this material outside the intended evaluation process.  
For queries, contact us !!
