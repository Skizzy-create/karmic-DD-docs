# Reengineering for Scale- My Technical Evolution




# KARTIK ASLIA
## Full Stack AI Engineer | Machine Learning Engineer

**Email:** asliakartik@gmail.com | **Phone:** +91 7701923367  
**GitHub:** [Skizzy-Create](https://github.com/Skizzy-Create) | **LinkedIn:** [Kartik Aslia](https://linkedin.com/in/kartik-aslia)

---

## PROFESSIONAL SUMMARY

Full Stack Machine Learning Engineer with expertise in **Physics-Informed Neural Networks (PINNs)**, **deep learning architectures**, and **production AI systems** serving **100,000+ users**. Specialized in building sophisticated ML models using **TensorFlow, PyTorch**, and **Scikit-learn** for applications ranging from aerospace trajectory prediction to real-time recommendation engines. Expert in **LLM orchestration**, **vector embeddings**, **semantic document retrieval**, and **scalable distributed systems**. Proven track record of achieving **80% AI cost reduction** and **99.9%+ uptime** through intelligent optimization and robust architecture design. Strong foundation in combining **physics-based modeling** with **advanced deep learning** techniques including Mixture-of-Experts, attention mechanisms, and normalizing flows.

**Core Technologies:** Python, TensorFlow, PyTorch, Scikit-learn, TypeScript, Node.js, React, Google Gemini AI, MongoDB, PostgreSQL, Vector Embeddings, Semantic Search, REST APIs, Docker, Cloud Infrastructure

### System Diagram

For a concise, high-level view of the architecture and data flows, please review the system diagram: **[System Diagrams](https://github.com/Skizzy-create/karmic-DD-docs/blob/main/System%20Diagrams.md)**. The diagram captures the core components, integrations, and orchestration patterns so you can quickly understand the design without reading the entire document. Review it and we can discuss any part in detail — I can walk through specific modules, flows, or implementation trade-offs in a call or chat to accelerate alignment.

---

## KEY TECHNICAL ACHIEVEMENTS

### Production AI Systems at Scale
- **100,000+ users** on single Oracle 4vCPU server with sub-linear cost scaling
- **80% overall AI cost reduction** through multi-layer caching and optimization strategies
- **93% token reduction** (1M+ → 75K) via file-based LLM processing and semantic chunking
- **95% API response improvement** (30-90s → <200ms) using async job orchestration
- **98%+ job completion rate** with fault-tolerant architecture and adaptive retry logic
- **99.9%+ production uptime** serving real paying customers

### ML/AI Engineering Excellence
- Designed **Physics-Informed Neural Network (PINN)** with custom trainable physical constants and multi-component loss functions
- Built **Mixture-of-Experts architecture** with 3 specialized expert heads achieving balanced phase-specific learning
- Implemented **Conditional RealNVP normalizing flows** for probabilistic predictions with uncertainty quantification
- Engineered **TCN backbone with attention mechanisms** for long-range temporal dependency modeling
- Created **hybrid deep learning architecture** combining LSTM, Dense layers, and physics residual networks
- Developed **vector-based recommendation engine** with 85%+ match accuracy using cosine similarity and 5 ML algorithms
- Implemented **semantic document embedding system** for intelligent data retrieval and AI-powered analysis
- Built **4 specialized LLM agents** collaborating through shared data registries for production deployment
- Designed **distributed job orchestration** handling 50+ concurrent AI generations with intelligent deduplication
- Developed **multi-layered data augmentation pipeline** generating 11,000+ labeled trajectories for model training

---

## TECHNICAL STACK & EXPERTISE

### Machine Learning & AI
- **ML Frameworks:** TensorFlow, PyTorch, Scikit-learn
- **LLM Integration:** Google Gemini 2.0/2.5 (Flash, Pro), Multi-model orchestration, Context optimization
- **NLP & Document Processing:** OCR pipelines, Text extraction, Semantic analysis, Entity recognition
- **Vector Embeddings:** Cosine similarity, Semantic search, Document retrieval, Candidate matching
- **Recommendation Systems:** Collaborative filtering, Weighted scoring algorithms, Hybrid models, Similarity metrics
- **Prompt Engineering:** Structured output generation, Few-shot learning, Context management, JSON validation

### Backend Development & APIs
- **Languages:** TypeScript (Expert), Python (Proficient), JavaScript (Expert)
- **Frameworks:** Node.js, Express.js, RESTful APIs, Async job patterns
- **Databases:** MongoDB (Mongoose), PostgreSQL (Prisma), Compound indexing, Query optimization
- **API Design:** RESTful architecture, Webhook handling, Versioning, Swagger documentation

### Distributed Systems & Scalability
- **Job Orchestration:** In-memory registries, Deduplication, Promise-based coordination, State machines
- **Caching Strategies:** Multi-layer caching, MongoDB cache-first, TTL management, Invalidation policies
- **Concurrency Control:** Worker pools, Batch processing, Resource allocation, Graceful degradation
- **Performance Monitoring:** Structured logging, Metrics collection, Error tracking, Health checks

### Cloud & DevOps
- **Cloud Platforms:** Oracle Cloud (production), Google Cloud (Gemini AI), Render.com deployment
- **Process Management:** PM2, Cluster mode, Zero-downtime restarts, Health monitoring
- **Security:** JWT authentication, CSRF protection, Rate limiting, Input sanitization, Payment verification
- **Version Control:** Git, GitHub, Code review workflows

---

## MAJOR PROJECTS & TECHNICAL IMPLEMENTATIONS

### 1. Physics-Informed Neural Network for Ballistic Trajectory Prediction
**Role:** ML Research Engineer | **Academic Research Project**  
**Impact:** Long-horizon trajectory forecasting with uncertainty quantification for aerospace applications

**Technical Implementation:**
- Designed **Physics-Informed Neural Network (PINN)** with custom trainable physical constants and multi-component loss functions integrating gravity, drag, and atmospheric effects
- Built **hybrid deep learning architecture** combining Dense layers, dual LSTM pathways, and physics residual networks for temporal sequence modeling
- Implemented **Mixture-of-Experts (MoE) router** with 3 specialized expert heads for phase-specific learning (Boost, Coast, Re-entry) achieving balanced 33% expert utilization
- Developed **Conditional RealNVP normalizing flow decoder** for probabilistic trajectory predictions with confidence intervals
- Created **Temporal Convolutional Network (TCN) backbone** with attention mechanism for long-range dependency capture
- Built **residual learning framework** separating physics baseline predictions from neural corrections
- Engineered **multi-layered data augmentation pipeline** with noise injection, time-scaling, and environmental parameter variation (±5% gravity jitter, ±10% drag variability)
- Deployed **headless KSP simulation automation** generating 11,000+ labeled trajectories with phase segmentation
- Implemented **unsupervised K-Means clustering** for automatic trajectory phase detection and segmentation
- Designed **multi-step autoregressive rollout** for long-horizon forecasting with hybrid physics+ML predictions

**Performance Metrics:**
- **11,000+ labeled data rows** with diverse launch and atmospheric conditions
- **Balanced MoE expert usage** (~33% per phase) confirming effective gating mechanism
- **Phase-specific accuracy** through dedicated expert modules reducing cross-phase interference
- **Dockerized reproducible environment** ensuring consistent results across deployments

**Advanced Techniques:**
- Physics-informed residual blocks, attention mechanisms, normalizing flows, temporal convolutions
- Z-score normalization, temporal feature engineering, unsupervised clustering
- GPU-accelerated TensorFlow training with early stopping, batch normalization, dropout
- 3D trajectory visualization with interactive Plotly, comprehensive error analysis (MSE, MAE, MAPE, R², max error)
- Real-time KRPC telemetry streaming and incremental learning integration

**Technologies:** Python, TensorFlow, PyTorch, Scikit-learn, Keras, NumPy, Pandas, Docker, KSP/KRPC, Plotly

---

### 2. Vector-Based Bidirectional Recommendation Engine
**Role:** Lead ML Engineer | **Production Platform** serving 100K+ users  
**Impact:** Matching candidates based on multi-dimensional compatibility scoring

**Technical Implementation:**
- Designed hybrid recommendation system combining **5 ML algorithms**: Weighted Cosine Similarity (industry/stage matching), Jaccard Index (criteria overlap), Haversine Distance (location proximity), LLM Semantic Analysis (cultural fit), and Collaborative Filtering (network effects)
- Implemented **vector embedding pipeline** for candidate similarity matching with cosine distance scoring
- Built **bidirectional scoring system** providing separate perspective evaluations for both parties
- Created **semantic analysis layer** using Gemini AI for questionnaire-based compatibility assessment
- Developed **fuzzy matching algorithms** for partial matches with confidence scores

**Performance Metrics:**
- **85%+ match accuracy** for top 10 recommendations validated through user engagement
- **95%+ cache hit rate** for repeat queries using MongoDB-backed persistence
- **<200ms average response** for cached matches with compound index optimization
- **70%+ reduction** in irrelevant matches compared to rule-based baseline

**Technologies:** TypeScript, Google Gemini 2.0 Flash, MongoDB, Cosine Similarity, Jaccard Index, Vector Embeddings

---

### 2. Semantic Document Embedding & Intelligent Retrieval System
**Role:** Lead AI Engineer | **Production Document Analysis Pipeline**  
**Impact:** Enabling LLM agents to quote and reference specific data from documents with full provenance tracking

**Technical Implementation:**
- Built **document embedding engine** converting OCR text into semantic chunks with metadata preservation
- Implemented **intelligent retrieval system** allowing AI agents to fetch and cite specific passages from documents
- Designed **provenance tracking** system recording document source, page numbers, and extraction confidence
- Created **chunk-based processing** with overlap strategy ensuring context continuity across segments
- Developed **semantic search layer** enabling agents to query relevant document sections during analysis

**Key Features:**
- **Automatic citation generation**: AI agents quote exact text with document references and page numbers
- **Context-aware retrieval**: Semantic similarity search for relevant passages during real-time analysis
- **Metadata preservation**: Track document type, time period, entity identifiers, and source information
- **Multi-document synthesis**: Combine insights across different document types and sources
- **Confidence scoring**: Rate extraction quality and relevance for each retrieved passage

**Impact on AI Analysis:**
- **Improved accuracy** through precise data referencing instead of hallucination
- **Verifiable insights** with traceable citations to source documents
- **Enhanced trust** as stakeholders can validate AI findings against original documents
- **Reduced token usage** by selectively retrieving relevant sections vs. processing entire corpus

**Technologies:** Google Gemini File API, pdf-lib, Custom chunking algorithms, Semantic search, Metadata tagging

---

### 3. Distributed Job Queue & Orchestration System
**Role:** Backend Architect | **Production System**  
**Impact:** Managing 50+ concurrent AI report generations without duplicate processing

**Architecture Highlights:**
- Designed **multi-stage job state machine** with granular progress tracking (queued → ocr → file_upload → analysis → completed)
- Implemented **key-based deduplication** preventing duplicate processing for identical entity requests
- Built **promise-based coordination** allowing concurrent requests to wait for in-flight jobs
- Created **polling-based status updates** with cache headers preventing excessive API calls
- Developed **graceful failure handling** with detailed error messages and retry eligibility

**Deduplication Strategy:**
- In-memory job registry mapping unique keys to job IDs
- Active request tracking preventing concurrent processing of same entity
- Immediate 202 Accepted responses with job IDs for client polling
- Coordinated cleanup when jobs complete or fail

**Scalability Features:**
- **98%+ completion rate** across all analysis types
- **Zero duplicate reports** through strict key-based locking
- **Sub-second status polling** with intelligent cache headers (10s processing, 300s completed)
- **Documented migration path** to BullMQ + Redis for horizontal scaling to 10,000+ jobs/second

**Technologies:** TypeScript, In-memory Maps, Promise coordination, MongoDB persistence, State machines

---

### 4. Intelligent OCR Pipeline with Multi-Agent Data Sharing
**Role:** ML Pipeline Engineer | **Production Document Processing**  
**Impact:** 75% OCR cost reduction through intelligent result sharing across AI agents

**Technical Innovation:**
- Developed **combine-first OCR strategy** merging multiple PDFs before processing (75% fewer API calls)
- Implemented **coordination registry** enabling agents to wait for and reuse OCR results
- Built **file-based vs. memory-based** processing modes optimized for document size (93% token reduction)
- Created **adaptive retry logic** with exponential backoff ensuring 100% OCR success rate
- Designed **MongoDB caching layer** with checksum-based deduplication preventing re-processing

**OCR Sharing Flow:**
- **Primary Agent** processes documents → publishes results to coordination registry
- **Secondary Agents** check registry → wait if processing in-flight → reuse completed results
- **Tertiary Agents** leverage combined OCR → add supplementary documents → zero duplicate processing
- **Coordinated cleanup** removes temporary files when all agents complete

**Performance Achievements:**
- **75% OCR cost reduction** by sharing results across 4 specialized agent types
- **3x faster processing** with combine-first vs. sequential document approach
- **93% token savings** using file-based processing for large documents (1M+ → 75K tokens)
- **Zero duplicate OCR** for same documents across different analysis types

**Technologies:** pdf-lib, Google Gemini Vision, Coordination registries, MongoDB caching, SHA256 checksums

---

### 5. Multi-Agent LLM Collaboration System
**Role:** AI Systems Architect | **Production Report Generation**  
**Impact:** 4 specialized agents collaborating to generate comprehensive analytical reports

**Agent Specializations:**
- **Belief Analysis Agent** (Gemini 2.0 Flash): Cultural fit and value alignment assessment
- **Financial Analysis Agent** (Gemini 2.5 Flash): Statement processing, ratio calculations, anomaly detection
- **Legal Analysis Agent** (Gemini 2.5 Pro): Compliance review, contract analysis, regulatory requirements
- **Market Analysis Agent** (Gemini 2.5 Flash + Internet): Market sizing, competition analysis, positioning

**Inter-Agent Collaboration:**
- Shared **OCR registry** enabling data reuse without duplication
- **File Registry** managing uploaded documents for LLM context
- **Coordinated cleanup** removing temporary files when all agents complete
- **Structured JSON outputs** enabling cross-agent data validation and synthesis

**Prompt Engineering Framework:**
- **Persona-based prompts** (e.g., "25 years analyst experience") improving output quality
- **Strict formatting rules** preventing parsing errors (numeric values, no symbols, valid JSON)
- **Context injection** tailoring analysis to specific scenarios and requirements
- **Materiality guidance** reducing noise in findings and focusing on key insights
- **Jurisdiction-specific focus** for compliance and regulatory analysis

**Production Reliability:**
- **98%+ successful report generation** across all agent types
- **<5% hallucination rate** through structured prompts and output validation
- **100% valid JSON** output with cleaning and validation pipelines
- **Zero timeout failures** using indefinite retry with exponential backoff

**Technologies:** Google Generative AI SDK, Multiple Gemini models, Structured prompting, Inter-agent coordination

---

### 6. Cost Optimization & Scalability Engineering
**Role:** Performance Engineer | **Full Platform Optimization**  
**Impact:** 80% overall cost reduction while scaling to 100K+ users

**Optimization Strategies:**

**Dashboard Caching (98% reduction):**
- Implemented aggressive 48-hour cache for dashboard data with CDN + browser caching
- MongoDB persistence layer with TTL indexes and automatic expiration
- Result: 5x faster load times, 98% fewer API calls, 95%+ cache hit rate

**Report Caching (Infinite validity):**
- Analysis reports marked as immutable with infinite cache validity
- Cache-first architecture: instant returns for existing reports, generation only on cache miss
- Result: 95%+ cache hit rate for established entities, zero regeneration costs

**Token Usage Optimization (93% reduction):**
- File-based processing: Upload OCR as files vs. embedding in prompts (1M+ → 75K tokens)
- Selective context: Only include relevant document sections vs. full corpus
- Structured schemas: Concise JSON templates replacing verbose instructions

**OCR Result Sharing (75% reduction):**
- Coordination registry enabling 4 analysis types to share single OCR run
- Combine-first strategy: Process 10 documents as 1 combined PDF (70% token savings)

**Database Query Optimization (80% faster):**
- Compound indexes for common query patterns (userId + perspective + score)
- Projections reducing data transfer by 60% (select only needed fields)
- Lean queries removing ORM overhead for read-heavy operations

**Overall Results:**
- **100,000+ users** on single 4vCPU Oracle Cloud server
- **Sub-linear cost scaling** (2x users ≠ 2x costs due to caching)
- **<$500/month infrastructure** at 100K user scale
- **99.9%+ uptime** with fault-tolerant architecture

**Technologies:** MongoDB caching, Compound indexes, CDN integration, File-based LLM processing, TTL management

---

## SYSTEM ARCHITECTURE & DESIGN EXPERTISE

### Production Backend Architecture
- **Modular Design:** Controllers → Services → Models following SOLID principles
- **Dual Database Strategy:** MongoDB for flexible schemas and caching, PostgreSQL for ACID transactions
- **Async Job Pattern:** 202 Accepted responses with client polling for long-running AI operations
- **Multi-Layer Caching:** Cache-first architecture (CDN → MongoDB → API → Database)
- **Zero-Trust Security:** JWT rotation, payment verification, CSRF protection, input sanitization

### Security Implementation
- **Authentication:** JWT-based stateless auth with refresh token rotation
- **CSRF Protection:** JWT-based tokens rotating on sensitive operations
- **Rate Limiting:** 100 requests per 15 minutes per IP with graceful degradation
- **Input Validation:** XSS prevention, NoSQL injection guards, sanitization middleware
- **Payment Security:** Zero-trust triple-layer verification (webhook + polling + settlement)
- **Audit Logging:** Structured security event logging with categories

### API Design Patterns
- **RESTful Architecture:** Consistent endpoint naming, HTTP verb semantics
- **Async Processing:** Long-running jobs with polling endpoints and progress tracking
- **Versioning Strategy:** URL-based versioning for backward compatibility
- **Comprehensive Documentation:** Swagger/OpenAPI specs for all endpoints
- **Error Handling:** Structured error responses with codes and actionable messages

---

## EDUCATION & CONTINUOUS LEARNING

**Bachelor of Technology (B.Tech)** - Computer Science & Engineering  
*Relevant Coursework: Machine Learning, Data Structures & Algorithms, Database Systems, Distributed Computing*

**Self-Learning & Technical Growth:**
- Production ML Systems & LLM Engineering (hands-on implementation experience)
- Advanced Prompt Engineering & Context Optimization techniques
- Distributed Systems & Job Orchestration Patterns
- Real-time Data Processing, Semantic Search & Vector Embeddings

---

## COVER LETTER

Dear Hiring Team,

I am writing to express my strong interest in the **Machine Learning Engineer (Full Stack AI Developer)** position. After reviewing your requirements, I am confident that my experience aligns exceptionally well with what you're seeking, and I'm excited about the opportunity to contribute to your team.

### Why My Experience is a Perfect Match

**Building and Deploying Production ML Models**

I have successfully built and deployed **4 specialized LLM agents** currently serving over **100,000 users** in production. These agents handle NLP tasks including document analysis, semantic search, and recommendation generation. My experience includes:
- Deploying models with **98%+ success rates** through structured prompt engineering
- Implementing **vector-based recommendation systems** using cosine similarity and collaborative filtering
- Building **semantic document embedding engines** for intelligent retrieval
- Achieving **93% token reduction** through optimization techniques

**Robust Backend Services for AI Applications**

I architected and maintain a scalable backend handling **100,000+ users on a single server**, demonstrating extreme efficiency:
- **99.9%+ uptime** with fault-tolerant architecture
- **95% response time improvement** (30-90s → <200ms) through async job patterns
- **Distributed job orchestration** with 98%+ completion rate and zero duplicate processing
- **Dual-database architecture** (MongoDB + PostgreSQL) optimized for different use cases

**Model Performance Optimization**

Cost optimization and scalability are where my work truly shines:
- **80% overall AI cost reduction** through intelligent caching strategies
- **75% OCR cost savings** via multi-agent result sharing
- **Sub-linear cost scaling** (2x users ≠ 2x costs)
- **<$500/month infrastructure** at 100K user scale

**Data Collection, Preprocessing & Monitoring**

I built comprehensive data pipelines from scratch:
- **End-to-end OCR pipeline**: Upload → Extraction → Embedding → Analysis → Report
- **Multi-stage job tracking** with real-time progress monitoring
- **Structured logging** with performance metrics and error tracking
- **Semantic chunking** with overlap for context continuity

**Programming Skills: Python & TypeScript**

- **TypeScript (Expert)**: 15,000+ lines of production backend code
- **Python (Proficient)**: Data processing, ML prototyping, automation scripts
- Both languages used extensively in production systems

**ML API Development (REST)**

I designed and documented **30+ RESTful endpoints** including:
- Async job patterns for long-running ML tasks (202 Accepted + polling)
- Comprehensive Swagger/OpenAPI documentation
- Webhook handling for real-time integrations
- Versioning and backward compatibility

**Distributed Systems Understanding**

My production experience includes:
- **In-memory job registries** with key-based deduplication
- **Promise-based coordination** for concurrent request handling
- **Multi-agent data sharing** via coordination registries
- **Migration planning** for horizontal scaling (BullMQ + Redis)

**Cloud Platforms & MLOps**

- **Oracle Cloud**: Production deployment (4vCPU server handling 100K users)
- **Google Cloud**: Gemini AI integration for LLM workloads
- **Process Management**: PM2 with cluster mode, zero-downtime deployments
- **Monitoring**: Custom metrics collection and health checks

**End-to-End Product Development**

I have taken a complete AI product from **concept → prototype → production**, managing:
- Architecture design and technology selection
- Frontend (React) and backend (Node.js) development
- ML pipeline implementation and optimization
- Production deployment and monitoring
- Real user feedback and iterative improvements

### Confidentiality & NDA Considerations

Due to **strict NDA agreements**, I cannot share the complete codebase or disclose specific company details as the project is currently in **stealth mode**. However, I am happy to:
- Discuss technical implementations and architectural decisions in detail
- Demonstrate problem-solving approaches during technical interviews
- Share code samples for non-proprietary algorithmic implementations
- Provide references who can speak to my technical capabilities

### What I Bring to Your Team

**Fast Learner & Self-Starter**
- Built the entire platform **independently** (backend + ML pipeline + frontend integration)
- **Self-taught** advanced LLM techniques, prompt engineering, and cost optimization
- **Comprehensive documentation** of all systems and architectural decisions

**Cost-Conscious Engineering**
- Achieved sub-linear scaling through intelligent architecture
- Reduced AI costs by 80% while maintaining quality
- Built for scale from day one despite budget constraints

**Production Mindset**
- **99.9%+ uptime** and **98%+ reliability** metrics
- Error handling, retry logic, and graceful degradation
- Monitoring, logging, and observability from the start

**Alignment with Your Opportunity**
- **Location flexibility**: Open to remote or on-site (Himachal)
- **Learning mindset**: Excited about the one-month training period
- **Startup experience**: Comfortable with fast-paced, scrappy environment
- **Long-term commitment**: Interested in growing with your team or within your ecosystem

### Why This Role Excites Me

The opportunity to work on **impactful AI products** in a **collaborative environment** while being in the **mountains** is incredibly appealing. Your structure (training → internship → full-time/investment option) demonstrates a commitment to growth and flexibility that aligns with my career goals.

I am eager to bring my production ML experience, scalability engineering skills, and cost-optimization expertise to your team. I'm confident I can contribute meaningfully from day one and grow into a key technical contributor.

Thank you for considering my application. I look forward to discussing how my experience aligns with your needs and learning more about the exciting AI products you're building.

**Best regards,**  
**Kartik Aslia**

**Contact Information:**
- **Email:** asliakartik@gmail.com
- **Phone:** +91 7701923367
- **GitHub:** [Skizzy-Create](https://github.com/Skizzy-Create)
- **LinkedIn:** [Kartik Aslia](https://linkedin.com/in/kartik-aslia)

**Availability:** A few weeks (1-2) / can be expited to be immidieate  
**Notice Period:** None  
**Location Preference:** Remote / On-site (Himachal) - Flexible

---

*Note: Due to confidentiality agreements and stealth-mode status of previous work, specific company names and complete codebase cannot be shared. Technical implementations, architectural decisions, and non-proprietary code samples can be discussed during interviews.*
