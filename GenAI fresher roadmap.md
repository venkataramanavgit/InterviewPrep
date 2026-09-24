Here is the **complete checklist to a fresher targeting GenAI Engineer roles**. You can use it directly as a learning tracker.

### 1. Python
- Syntax, variables, data types
- Conditions and loops
- Functions
- Lists, tuples, sets, dictionaries
- List/dict comprehensions
- Strings
- File handling
- JSON
- Exceptions
- Modules/packages
- OOP
- Iterators/generators basics
- Virtual environments
- `pip`
- HTTP requests
- Async basics

### 2. Git & GitHub
- Git basics
- Repository
- `clone`, `add`, `commit`, `push`, `pull`
- Branches
- Merge
- Pull requests
- `.gitignore`
- README
- Resolving simple conflicts

### 3. SQL
- SELECT
- WHERE
- ORDER BY
- GROUP BY
- HAVING
- Aggregate functions
- JOINs
- Subqueries
- CTE basics
- Window functions basics
- Primary/foreign keys
- Constraints
- Index basics
- Transactions

### 4. REST APIs + FastAPI
- HTTP basics
- GET/POST/PUT/PATCH/DELETE
- Request/response
- HTTP status codes
- JSON
- Headers
- Query/path parameters
- FastAPI routes
- Pydantic models
- Validation
- Exception handling
- Dependency injection basics
- Authentication basics
- Async endpoints
- API documentation

### 5. Machine Learning Fundamentals
- Supervised vs unsupervised learning
- Classification
- Regression
- Training vs inference
- Train/validation/test
- Features and labels
- Loss functions
- Gradient descent intuition
- Overfitting/underfitting
- Precision
- Recall
- F1
- Accuracy
- Cosine similarity

### 6. Deep Learning Fundamentals
- Neural networks
- Neurons
- Weights
- Bias
- Layers
- Activation functions
- Forward propagation
- Loss
- Backpropagation intuition
- Gradient descent
- Embeddings
- PyTorch basics

### 7. NLP Fundamentals
- Text preprocessing
- Tokenization
- Vocabulary
- Stop words — concept
- Stemming/lemmatization — concept
- Bag of Words — concept
- TF-IDF — concept
- Word embeddings
- Semantic similarity
- Text classification

### 8. Transformers ⭐
- Why transformers exist
- Tokens
- Tokenization
- Embeddings
- Positional information
- Attention intuition
- Self-attention
- Query/Key/Value intuition
- Multi-head attention
- Encoder
- Decoder
- Encoder vs decoder models
- Transformer architecture
- Autoregressive generation

### 9. LLM Fundamentals ⭐
- What an LLM is
- Next-token prediction
- Pretraining
- Instruction tuning
- Fine-tuning concept
- Inference
- Context window
- Tokens
- Temperature
- Top-p concept
- Hallucinations
- Model parameters
- Open vs closed models
- Model limitations

### 10. Prompting
- System instructions
- User messages
- Clear instructions
- Providing context
- Zero-shot
- Few-shot
- Examples
- Prompt templates
- Delimiters
- Asking for structured responses
- Prompt injection awareness

### 11. Structured Outputs
- JSON outputs
- JSON Schema basics
- Pydantic schemas
- Validation
- Required/optional fields
- Enums
- Nested objects
- Parsing model responses
- Handling invalid responses

### 12. LLM APIs
- Calling a model API
- Messages
- Model parameters
- Streaming
- Token usage
- Error handling
- Retries
- Rate limits
- Timeouts
- API keys/secrets
- Cost awareness

### 13. Embeddings ⭐
- What embeddings are
- Text → vector intuition
- Dimensions
- Semantic similarity
- Cosine similarity
- Creating embeddings
- Comparing embeddings
- Embedding models
- Batch embeddings

### 14. Vector Databases ⭐
- Why vector databases exist
- Store embeddings
- Similarity search
- Top-K retrieval
- Metadata
- Metadata filtering
- Index basics
- CRUD
- Learn **one** well:
  - pgvector **or**
  - Qdrant

### 15. Semantic Search
- Keyword vs semantic search
- Query embedding
- Document embeddings
- Similarity
- Top-K
- Metadata filtering
- Ranking
- Hybrid search basics
- Reranking basics

### 16. RAG ⭐⭐⭐
Master this especially well.

- Why RAG exists
- Document loading
- Parsing
- Cleaning
- Chunking
- Chunk size
- Chunk overlap
- Embeddings
- Vector storage
- Retrieval
- Top-K
- Metadata filtering
- Query rewriting
- Hybrid retrieval
- Reranking
- Context construction
- Prompt + retrieved context
- Grounded answers
- Citations
- Hallucination reduction

### 17. Tool / Function Calling ⭐
- What tools are
- Function schemas
- Tool parameters
- LLM choosing a tool
- Executing the tool
- Returning results to LLM
- Multiple tools
- Error handling
- Tool permissions
- Human approval for risky actions

### 18. AI Agents ⭐⭐⭐
- LLM vs agent
- Agent loop
- Goal
- Planning basics
- Tools
- State
- Memory concepts
- Multi-step workflows
- Tool selection
- Retry/failure handling
- Human-in-the-loop
- Agent limitations

### 19. LangChain
Don't overlearn it.

- Models
- Prompts
- Documents
- Embeddings
- Retrievers
- Vector stores
- Tools
- Structured outputs
- Basic RAG pipeline

### 20. LangGraph ⭐
- Graph concept
- Nodes
- Edges
- State
- Conditional routing
- Tool nodes
- Agent workflows
- Persistence/checkpoints
- Human-in-the-loop
- Error/retry flows

### 21. MCP
- What MCP solves
- MCP client
- MCP server
- Tools
- Resources
- Prompts
- Tool discovery
- Connecting an LLM application to an MCP server
- Security/permissions basics

### 22. LLM Evaluation ⭐⭐⭐
- Why evaluation matters
- Test datasets
- Expected answers
- Retrieval quality
- Answer correctness
- Groundedness
- Hallucination testing
- RAG evaluation
- Agent evaluation
- LLM-as-judge concept
- Human evaluation
- Latency
- Token usage
- Cost
- Regression testing

### 23. Guardrails & Security
- Prompt injection
- Jailbreak concept
- Data leakage
- PII
- Input validation
- Output validation
- Tool permissions
- Authentication/authorization
- Secrets management
- Content filtering basics
- RAG access control

### 24. Docker
- Images
- Containers
- Dockerfile
- Build
- Run
- Ports
- Environment variables
- Volumes basics
- Docker Compose basics
- Containerize FastAPI + GenAI application

### 25. Deployment / Cloud
- Environment variables
- Secrets
- Deploy API
- Database connection
- Vector DB connection
- Logging
- Monitoring basics
- Scaling basics
- CI/CD basics
- AWS/Azure/GCP basics — **choose one**

## Projects to Build Along the Way

**Project 1 — Resume Analyzer**
`Python + FastAPI + LLM + Structured Output`

**Project 2 — Semantic Search**
`Embeddings + Vector DB + Similarity Search`

**Project 3 — Production RAG Assistant ⭐**
`Documents + Chunking + Embeddings + Vector DB + Retrieval + Reranking + Citations + Evaluation`

**Project 4 — AI Agent ⭐**
`LLM + Tools + APIs + LangGraph + State + Human Approval`

**Project 5 — Final GenAI Project ⭐⭐⭐**
`FastAPI + SQL + RAG + Agents + Tools + MCP + Evaluation + Security + Docker + Cloud`

### Learn in this exact order

```text
Python + Git + SQL
        ↓
FastAPI
        ↓
ML + DL + NLP basics
        ↓
Transformers
        ↓
LLMs + Prompting
        ↓
Structured Output + LLM APIs
        ↓
Embeddings + Vector DB
        ↓
Semantic Search
        ↓
RAG ⭐
        ↓
Tool Calling
        ↓
Agents + LangGraph ⭐
        ↓
MCP
        ↓
Evaluation ⭐
        ↓
Security
        ↓
Docker + Cloud
        ↓
Production GenAI Project 🚀
```

