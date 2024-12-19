# Distributed Systems Project

This project demonstrates the application of distributed systems concepts using the Neo4j graph database. The IMDB dataset, containing information about movies, actors, directors, and their relationships, is analyzed to extract insights using distributed cluster setups and graph algorithms.

## Table of Contents
- [Introduction](#introduction)
- [Features](#features)
- [Setup](#setup)
- [Technologies Used](#technologies-used)
- [Acknowledgments](#acknowledgments)

## Introduction

The project focuses on:

1. **Practicing Distributed Systems Concepts**
   - Including fault tolerance, consistancy, scalability and concurrency.

2. **Analyzing Large-Scale Data**
   - Utilizing a causal cluster setup in Neo4j to manage and analyze a dataset of **4.5GB**.

3. **Gaining Insights from the IMDB Dataset**
   - **Shortest Paths** between industry professionals.
   - **Community Detection** among actors and directors.
   - **Popular Movie Genres** by decade.

## Features

- **Causal Cluster Setup**
  - High availability with primary and secondary Neo4j nodes.

- **Graph Algorithms**
  - Shortest path, community detection, and genre analysis.

- **Concurrent Query Testing**
  - Simulates multiple clients accessing the graph.

- **Fault Tolerance**
  - Demonstrates system recovery during node failure.
 
## Technologies Used

- **Neo4j**
  - Graph database for data storage and analysis.

- **Docker**
  - Containerization platform used to set up the Neo4j causal cluster.

- **Python**
  - For data preprocessing and scripting.

- **Cypher**
  - Query language for Neo4j.

## Acknowledgments

- **IMDB**
  - For providing the comprehensive dataset.

- **Neo4j**
  - For their extensive documentation and powerful graph database tools.



