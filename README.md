## Improvements Over Original LightRAG

| Component | Original LightRAG | Enterprise-LightRAG |
|------------|------------------|---------------------|
| Graph Storage | In-Memory Graph | Neo4j Graph Database |
| Retrieval | Graph-Based Retrieval | Hybrid BM25 + Vector Search |
| Ranking | Standard Retrieval | Reciprocal Rank Fusion |
| Query Processing | Basic Queries | Query Compression |
| Scalability | Research Prototype | Enterprise-Oriented Design |
# Enterprise-LightRAG

## Overview

Enterprise-LightRAG is an enhanced Retrieval-Augmented Generation (RAG) architecture designed to overcome limitations of traditional LightRAG systems in enterprise environments.

The framework introduces:

* Native Neo4j graph database integration
* Hybrid lexical-semantic retrieval
* Reciprocal Rank Fusion (RRF)
* Query compression mechanisms
* Distributed graph storage
* Enterprise-scale evaluation framework

## Motivation

Traditional LightRAG implementations rely heavily on in-memory graph structures, which introduce scalability constraints, memory overhead, and retrieval inefficiencies under production workloads.

This work proposes an enterprise-grade evolution focused on throughput, retrieval quality, and deployment scalability.

## Key Contributions

### Graph Persistence Layer

Replaced volatile in-memory graph storage with Neo4j graph persistence.

### Hybrid Retrieval

Combined BM25 lexical retrieval with vector similarity search using Reciprocal Rank Fusion.

### Query Optimization

Introduced query compression techniques to reduce token consumption and retrieval latency.

### Enterprise Evaluation

Evaluated performance across multiple enterprise-oriented scenarios and datasets.

## Repository Structure

* paper/ → Research paper
* docs/ → Design notes and future work
* src/ → Prototype implementation
* results/ → Experimental findings
* figures/ → Architecture diagrams

## Authors

Sanskriti Singh

SRM Institute of Science and Technology

## Research Focus

Retrieval-Augmented Generation (RAG)
Knowledge Graphs
GraphRAG
Information Retrieval
Enterprise AI Systems
Large Language Models
