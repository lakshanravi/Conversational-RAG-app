# Farmscap AI Chatbot (Gemini LLM)

Farmscap AI Chatbot is an AI-powered assistant built for the Farmscap AI-Enhanced Livestock Management System.

This chatbot uses Google's Gemini large language model with a Retrieval-Augmented Generation (RAG) architecture to provide accurate and context-aware answers based on Farmscap system documentation.

------------------------------------------------------------

PROJECT OVERVIEW

The chatbot is designed to help farmers and farm managers by answering questions related to:

- Animal management
- Milk yield monitoring
- Breeding records
- Feeding management
- Government aid information
- Geofencing and farm security
- AI-based monitoring features

The responses are generated using Farmscap documentation as the knowledge base.

------------------------------------------------------------

ARCHITECTURE

The chatbot follows a RAG (Retrieval-Augmented Generation) pipeline:

1. Document Loader
   Loads Farmscap documentation files.

2. Text Splitter
   Splits large documents into smaller chunks.

3. Embedding Model
   Converts text into vector embeddings.

4. Vector Database (e.g., FAISS)
   Stores document embeddings for semantic retrieval.

5. Gemini LLM
   Generates responses using retrieved relevant context.

This ensures domain-specific and accurate answers.

------------------------------------------------------------
