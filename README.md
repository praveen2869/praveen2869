# Praveen Kumar

## AI Engineer | Backend Engineer | Agentic AI and RAG Systems

I design and build AI-enabled backend systems that connect LLM capabilities with reliable software engineering. My work focuses on retrieval-augmented generation, tool-using agents, MCP integrations, natural-language data systems, and Java/Python APIs.

I am especially interested in the engineering details behind useful AI products: data ingestion, retrieval quality, structured outputs, tool validation, state management, security boundaries, observability, and graceful failure handling.

- Based in India
- Focused on AI Engineering, Agentic AI, and backend development
- Building with Java 17, Spring Boot, Python, FastAPI, RAG, LLMs, vector databases, and MCP
- Exploring evaluation, guardrails, agent memory, human approval workflows, and LLMOps
- Open to AI Engineer, GenAI Engineer, Agentic AI Engineer, AI Backend Engineer, and Java Backend opportunities

[GitHub](https://github.com/praveen2869)

## Engineering Profile

### AI Systems

- Design retrieval pipelines for documentation, structured data, and domain knowledge
- Connect LLMs to controlled tools instead of relying only on free-form generation
- Use structured prompts, schemas, validation, and citations to improve response quality
- Explore agent planning, task decomposition, memory, approvals, and bounded execution
- Treat prompt injection, unsafe tool use, hallucination, and data leakage as engineering risks

### Backend Systems

- Design REST APIs with explicit contracts and clear responsibility boundaries
- Build persistence-backed services with relational and analytical data stores
- Work with asynchronous processing, queues, background jobs, and event-driven workflows
- Apply authentication, authorization, validation, error handling, logging, and testing
- Develop Java/Spring Boot microservices and Python/FastAPI AI services

## Technical Stack

### Languages and Frameworks

`Java 17` `Python` `TypeScript` `JavaScript` `Spring Boot` `Spring Data JPA` `Hibernate` `FastAPI` `React` `Streamlit` `Maven`

### AI and LLM Engineering

`Generative AI` `LLMs` `RAG` `AI Agents` `Agentic AI` `MCP` `Tool Calling` `LangChain` `crewAI` `Embeddings` `Vector Databases` `Knowledge Bases` `Guardrails` `Human-in-the-Loop`

### Data and Messaging

`Microsoft SQL Server` `SQL` `SQLite` `DuckDB` `Redis` `RabbitMQ` `FAISS`

### Engineering and Delivery

`REST APIs` `Microservices` `WebSocket` `Docker` `Git` `GitHub` `CI/CD` `Unit Testing` `Integration Testing` `API Documentation`

## Selected Projects

### [Acadia Insights Engine](https://github.com/praveen2869/acadia-insights-engine)

A natural-language analytics system for uploading transactional CSV data and asking questions in plain English. The application converts requests into validated, read-only SQL and returns data-backed answers.

**Technical focus**

- FastAPI service boundary for request handling
- Redis/RQ for asynchronous processing
- DuckDB for analytical queries over uploaded data
- Streamlit interface for interactive analysis
- Read-only query execution as a safety boundary
- Separation between language interpretation, query validation, and execution

### [Automatisor Financial Agent](https://github.com/praveen2869/automatisor-financial-agent)

An MCP-grounded financial research agent with a FastAPI backend, Streamlit interface, and real-data SQLite snapshot.

**Technical focus**

- MCP-based access to controlled tools and data
- Agent workflow for grounded financial research
- FastAPI endpoints for application integration
- SQLite-backed data access
- Tool-oriented design instead of unrestricted model actions

### [Documentation Crawler and RAG Agent](https://github.com/praveen2869/Documentation-Crawler-and-RAG-Agent)

A documentation-focused RAG application that crawls technical content and makes it available for contextual question answering.

**Technical focus**

- Source ingestion and document processing
- Chunking and embedding-oriented retrieval
- Knowledge-base construction
- Context assembly for LLM responses
- A foundation for citations, retrieval evaluation, and access control

### [MCP Streamlit Agent](https://github.com/praveen2869/mcp-streamlit-agent)

An interactive agent application combining a Streamlit interface with MCP-oriented tool integration.

**Technical focus**

- Agent-to-tool communication
- MCP integration patterns
- User-facing workflow orchestration
- Clear boundary between interface, agent logic, and tool execution

### [ZOOMHOPR](https://github.com/praveen2869/ZOOMHOPR)

A ride-sharing and self-drive car rental platform with a Spring Boot microservices backend and React frontend.

**Technical focus**

- Java and Spring Boot service development
- REST API design for a business domain
- Microservice-oriented system structure
- React frontend integration
- Distributed application boundaries and domain workflows

### [Financial Agent](https://github.com/praveen2869/financial-agent)

An AI application exploring financial analysis workflows and agent-assisted reasoning.

**Technical focus**

- Domain-specific AI workflow design
- Structured task execution
- LLM-assisted analysis
- Practical automation around financial information

## How I Approach AI Applications

```text
Ingest data
    -> clean and validate
    -> index or structure knowledge
    -> retrieve relevant context
    -> call the model with constraints
    -> validate the output
    -> request approval when risk requires it
    -> return an observable result
```

The goal is not simply to call an LLM. The goal is to build a system where the model has appropriate context, limited authority, clear failure behavior, and an auditable path from input to result.

## Engineering Practices

- Use explicit API contracts and versioned interfaces
- Keep business logic separate from transport and persistence concerns
- Validate inputs before database, model, or tool operations
- Return consistent error responses from backend services
- Use structured logs and correlation-friendly diagnostics
- Add retries and timeouts only where their behavior is understood
- Make asynchronous work observable and safe to retry
- Protect credentials and sensitive data through configuration and access control
- Document setup, architecture, tradeoffs, and known limitations
- Test both normal behavior and failure paths

## Current Learning Areas

- RAG evaluation, reranking, chunking, and retrieval quality
- Multi-agent coordination, state, memory, and termination policies
- MCP tool ecosystems and secure integrations
- Guardrails, structured outputs, and human-in-the-loop workflows
- Spring Boot microservices and event-driven backend design
- Observability, deployment, and LLMOps practices

## GitHub Activity

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=praveen2869&show_icons=true&hide_border=true&rank_icon=github" height="165" alt="Praveen's GitHub statistics" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=praveen2869&layout=compact&hide_border=true" height="165" alt="Praveen's most used languages" />
</p>

## Open To

- AI Engineer roles
- Generative AI and LLM Engineer roles
- Agentic AI Engineer roles
- AI Backend Engineer roles
- Java Backend and Spring Boot roles
- Microservices and platform engineering opportunities

## Connect

[![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/praveen2869)

> Building intelligent systems with strong engineering foundations.
