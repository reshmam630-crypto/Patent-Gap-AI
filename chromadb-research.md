# ChromaDB Research

## 1. Introduction

ChromaDB is an open-source vector database that can store text, metadata and embeddings. It supports semantic search, allowing relevant information to be retrieved based on meaning rather than exact keyword matching.

## 2. Why ChromaDB?

In a multi-agent AI system, agents may need to access information from previous investigations. ChromaDB could help store and retrieve relevant historical findings, rules and user clarifications.

## 3. Potential Use Cases

- Store previous investigation logs.
- Retrieve relevant patent-related information.
- Store reusable analysis rules.
- Maintain user clarifications and corrections.
- Provide relevant historical context to AI agents.

## 4. Proposed Application

ChromaDB is being explored as a possible local persistent storage solution for the Record Keeper module.

The proposed design includes four components:

- Book – manages investigation information.
- Logs – records investigation activities.
- Rules – stores reusable instructions.
- Clarifications – stores user corrections and explanations.

## 5. Current Status

Research and exploration phase. Implementation and integration have not yet started.

## 6. References

- https://docs.trychroma.com/
- https://cookbook.chromadb.dev/
