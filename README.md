# 🛡️ ComplianceGuard AI

## AI-Powered Company Handbook Compliance Analysis

ComplianceGuard AI is an AI-assisted system designed to analyze company handbook policies against Indian labour-law references using Retrieval-Augmented Generation (RAG), vector search, and Generative AI.

The project combines document processing, semantic retrieval, AI-assisted policy analysis, compliance scoring, report generation, and a natural-language handbook assistant into a single Streamlit application.

---

## 🎯 Project Objective

Company handbooks can contain a large number of policies that are difficult to review manually and compare consistently against applicable labour-law references.

ComplianceGuard AI was developed to explore how AI and RAG can assist with:

- 📄 Processing company handbook documents
- ⚖️ Comparing policy content with Indian labour-law references
- 🔎 Retrieving relevant policy and legal context
- 🤖 Performing AI-assisted policy analysis
- 📊 Calculating compliance scores and grades
- 📑 Generating detailed compliance reports
- 💬 Answering handbook questions using natural language

---

## 🧠 How It Works

```text
Company Handbook PDF
        +
Indian Labour Law PDF
        ↓
Document Processing
        ↓
Text Extraction & Chunking
        ↓
Vector Database
     ChromaDB
        ↓
RAG Retrieval
        ↓
Gemini AI Analysis
        ↓
Policy-Level Compliance Analysis
        ↓
Compliance Score & Grade
        ↓
Detailed Compliance Report
```

## 🔍 Core Capabilities

### 📄 Document Processing

Processes company handbook and labour-law PDF documents and divides their content into searchable sections.

### 🔎 RAG-Based Retrieval

Relevant document context is retrieved from the vector database before AI analysis.

### 🤖 AI-Assisted Compliance Analysis

Gemini is used to analyze retrieved policy and legal context.

### 📊 Compliance Scoring

The system calculates an overall compliance score and assigns a compliance grade based on the analyzed policies.

### 📑 Compliance Report Generation

Generates a detailed compliance report containing policy-level findings and analysis.

### 💬 AI Handbook Assistant

Users can ask questions about the handbook using natural language and receive answers based on retrieved handbook context.

### 🖥️ Streamlit Dashboard

Provides an interactive interface for document upload, compliance analysis, scoring, reporting, and AI-assisted handbook queries.


## 📊 Project Test Result

In the demonstrated project analysis:

| Metric | Result |
|---|---:|
| Policies analyzed | **59** |
| Compliance Score | **69.5%** |
| Compliance Grade | **C** |

The system also generated a downloadable compliance report containing policy-level analysis.

> **Note:** These results represent the demonstrated project test dataset and should not be interpreted as a legal opinion or certification of compliance.


## 🏗️ Technology Stack

| Technology | Purpose |
|---|---|
| 🐍 Python | Application development |
| ✨ Gemini | Generative AI and policy analysis |
| 🔎 RAG | Context-grounded document retrieval |
| 🗄️ ChromaDB | Vector database and semantic retrieval |
| 🖥️ Streamlit | Interactive application interface |
| 📄 PDF Processing | Document extraction and processing |


## 🔄 System Workflow
```text
1. Upload company handbook PDF
              ↓
2. Upload Indian labour-law reference PDF
              ↓
3. Extract document text
              ↓
4. Split documents into manageable chunks
              ↓
5. Store searchable document representations
              ↓
6. Retrieve relevant context using RAG
              ↓
7. Analyze policies using Gemini
              ↓
8. Generate policy-level compliance findings
              ↓
9. Calculate compliance score and grade
              ↓
10. Generate downloadable compliance report
              ↓
11. Ask handbook questions through AI Assistant
```


## 💡 Key Project Features

- Retrieval-Augmented Generation (RAG)
- Semantic document retrieval
- AI-assisted policy analysis
- Company handbook analysis
- Indian labour-law reference comparison
- Compliance scoring
- Compliance grading
- Automated compliance report generation
- Natural-language handbook Q&A
- Interactive Streamlit dashboard
- PDF document processing
- Privacy-conscious project structure


## 🖼️ Project Showcase

This public repository contains selected visuals demonstrating the application interface and workflow.

### 🖥️ Application Dashboard

The dashboard provides document upload, compliance audit execution, compliance scoring, report download, and AI assistant functionality.

### 💬 AI Handbook Assistant

The AI assistant allows users to ask natural-language questions about the uploaded handbook and receive context-based answers.

### 📑 Compliance Report

The application generates a downloadable compliance report containing policy-level analysis and compliance findings.

### 🏗️ System Architecture

The architecture demonstrates the flow from PDF document processing through chunking, vector retrieval, RAG, Gemini analysis, compliance scoring, and report generation.


## 🔐 Privacy & Source Code

This repository is a **public project showcase**.

The complete application source code is maintained separately in a **private GitHub repository**.

The following private project materials are intentionally not included in this showcase repository:

- ❌ Application source code
- ❌ Private company handbook PDFs
- ❌ Labour-law source PDFs
- ❌ API keys or credentials
- ❌ Vector database
- ❌ Generated private reports
- ❌ Python virtual environment

### 🔒 Source Code Available on Request

The source code is maintained privately to provide controlled access to the implementation.

If you are interested in reviewing or accessing the source code, please connect with me on LinkedIn and send your GitHub username.

Access may be provided selectively.


## 🛡️ Security Considerations

The project follows a privacy-conscious repository structure.

Sensitive information such as API credentials and private project documents are not intended to be published in the public showcase repository.

The public repository is designed only to present the project's:

- Architecture
- Features
- Technology stack
- Demonstrated results
- Application screenshots
- Project documentation


## 🚀 Project Highlights

### 🤖 AI + Document Intelligence

Combines document processing, vector retrieval, RAG, and Generative AI to analyze structured and unstructured policy information.

### 🎯 Context-Grounded AI

The AI assistant retrieves relevant handbook information before generating responses.

### 📊 Automated Compliance Analysis

The system assists with policy-level analysis and generates structured compliance findings.

### 🖥️ Interactive Application

The Streamlit dashboard brings document processing, compliance analysis, scoring, reporting, and the AI assistant together in one interface.


## ⚠️ Disclaimer

ComplianceGuard AI is an AI-assisted analysis and research project.

The generated results are intended to support document review and should not be treated as legal advice, legal certification, or a substitute for review by a qualified legal professional.

Labour-law requirements can depend on jurisdiction, applicability, effective dates, employee categories, and other legal factors.


## 👤 Project Author

### Kshitij Rajesh Yadav

**AI | RAG | Python | Automation**

Interested in AI-powered automation, document intelligence, Retrieval-Augmented Generation, and practical engineering applications.


## 🔐 Interested in the Source Code?

The complete source code is maintained in a private repository.

If you would like to review the implementation, please connect with me on LinkedIn and send a request with your GitHub username.

**Source code access is provided selectively.**


## 📌 Project Status

**Project Status: Completed Prototype / Demonstration**

The current implementation successfully demonstrates:

- Document ingestion
- PDF processing
- Text chunking
- Vector-based retrieval
- RAG workflow
- Gemini-powered analysis
- Compliance scoring
- Compliance report generation
- Streamlit dashboard
- AI Handbook Assistant


⭐ If you find the project interesting, feel free to connect with me on LinkedIn and discuss AI, RAG, document intelligence, or automation.
