# Backend Node.js Interview Preparation

## Table of Contents
- [Introduction](#introduction)
- [Roadmap](#roadmap)
  - [Day 1 - Day 21](#day-1---day-21)
- [Detailed Notes](#detailed-notes)
  - [Data Structures & Algorithms](#data-structures--algorithms)
  - [System Design](#system-design)
  - [Databases (MySQL & MongoDB)](#databases-mysql--mongodb)

---

## Introduction
This repository is designed to help backend developers prepare for **Node.js interviews**. It covers **Data Structures & Algorithms (DSA)**, **System Design (SD)**, and **Databases (MySQL & MongoDB)** with a structured 21-day roadmap.

---

## Roadmap

### Day 1 - Day 21

| Day | Data Structures | System Design | Database |
|---|---|---|---|
| 1 | Arrays | Load Balancing | ACID Transactions (MySQL) |
| 2 | Linked Lists | Caching Strategies | CRUD & BSON (MongoDB) |
| 3 | Stacks & Queues | DB Scaling | Indexing & Joins (MySQL) |
| 4 | HashMaps & HashSets | Message Queues | Aggregation Framework (MongoDB) |
| 5 | Trees & BSTs | API Rate Limiting | Normalization vs. Denormalization (MySQL) |
| 6 | Tries | Authentication & Authorization | Schema Design (MongoDB) |
| 7 | Graphs (BFS, DFS) | Microservices vs Monolith | Query Optimization (MySQL) |
| 8 | Shortest Path (Dijkstra, Bellman-Ford) | Event-Driven Architecture | Indexing (MongoDB) |
| 9 | Heaps | CAP Theorem | Stored Procedures & Triggers (MySQL) |
| 10 | Segment Trees | Distributed Caching | Sharding & Replication (MongoDB) |
| 11 | Union-Find (Disjoint Set) | Unique ID Generation | Partitioning & MVCC (MySQL) |
| 12 | DP Basics | Distributed Transactions | Transactions (MongoDB) |
| 13 | String Matching (KMP, Rabin-Karp) | Circuit Breakers | Replication & Failover (MySQL) |
| 14 | LRU Cache | Consistency Models | Performance Tuning (MongoDB) |
| 15 | Probabilistic DS | Reverse Proxy & CDN | Query Caching (MySQL) |
| 16 | Review Coding Problems | Real-Time Communication | Change Streams (MongoDB) |
| 17 | Mixed DSA | Containerization & Kubernetes | Archiving & Backup (MySQL) |
| 18 | Mock DSA Interview | Observability | Advanced MongoDB (TTL, GridFS) |
| 19 | System Design Exercise | Review & Improvements | Combined DB Discussion |
| 20 | Timed DSA Challenges | Iterative Design Review | Deep Performance Optimization |
| 21 | Final Mock Interviews | System Design Wrap-up | Database Wrap-up |

---

## Detailed Notes

### Data Structures & Algorithms

#### Arrays
- **Operations:** Access, Insert, Delete
- **Time Complexity:** O(1) access, O(n) insert/delete in worst case
- **Use Cases:** Caching, Lookups

#### Linked Lists
- **Types:** Singly, Doubly, Circular
- **Time Complexity:** O(n) search, O(1) insert/delete at head
- **Use Cases:** Implementing stacks, memory-efficient structures

#### Stacks & Queues
- **Stack Operations:** LIFO (push, pop)
- **Queue Operations:** FIFO (enqueue, dequeue)
- **Use Cases:** Function calls, task scheduling

#### Trees & BST
- **Binary Search Tree:** Ordered nodes for fast lookups (O(log n))
- **Balanced Trees:** AVL, Red-Black Tree
- **Use Cases:** Databases, File Systems

#### Graphs (BFS & DFS)
- **BFS:** Shortest path (O(V+E))
- **DFS:** Cycle detection (O(V+E))
- **Use Cases:** Route optimization, Social Networks

---

### System Design

#### Load Balancing
- **Types:** Round Robin, Least Connections
- **Use Case:** Distributing load across servers

#### Caching
- **Strategies:** LRU, LFU, Write-back, Write-through
- **Tools:** Redis, Memcached

#### Microservices vs Monolith
- **Monolith:** Easier development, harder scaling
- **Microservices:** Independent services, better scaling, more complexity

#### Message Queues
- **Brokers:** Kafka, RabbitMQ, SQS
- **Use Case:** Decoupling systems, asynchronous processing

#### Database Scaling
- **Vertical Scaling:** Adding more resources to a single server
- **Horizontal Scaling:** Adding more servers (sharding, replication)

---

### Databases (MySQL & MongoDB)

#### MySQL

##### ACID Transactions
- **Atomicity:** Ensures complete success or failure
- **Consistency:** Ensures DB remains valid after transaction
- **Isolation:** Controls concurrent execution
- **Durability:** Ensures transaction permanence

##### Indexing & Query Optimization
- **Index Types:** Primary, Secondary, Composite
- **EXPLAIN:** Analyzing query plans for optimization

##### Normalization vs Denormalization
- **Normalization:** Avoids redundancy (1NF, 2NF, 3NF)
- **Denormalization:** Increases redundancy for performance

##### Partitioning
- **Types:** Range, List, Hash Partitioning
- **Use Case:** Large dataset performance optimization

##### Replication & Failover
- **Types:** Master-Slave, Master-Master
- **Use Case:** High Availability (HA)

---

#### MongoDB

##### CRUD Operations
- **Create:** `db.collection.insertOne()`
- **Read:** `db.collection.find()`
- **Update:** `db.collection.updateOne()`
- **Delete:** `db.collection.deleteOne()`

##### Schema Design
- **Embedding:** Stores related data together (fast reads)
- **Referencing:** Stores related data separately (normalized, flexible)

##### Aggregation Framework
- **Stages:** `$match`, `$group`, `$sort`, `$project`
- **Use Case:** Data analytics, reporting

##### Sharding & Replication
- **Sharding:** Splits data across multiple servers
- **Replication:** Ensures redundancy for failover

##### Performance Optimization
- **Indexes:** Improves query performance
- **Profiling:** `db.setProfilingLevel(2)` to analyze slow queries

##### Change Streams
- **Use Case:** Real-time updates in event-driven architectures

---

## How to Use This Repo?
1. **Follow the Roadmap** - Study one topic from each section per day.
2. **Practice Coding** - Implement DSA problems using JavaScript/Node.js.
3. **Build Projects** - Apply system design and database concepts.
4. **Mock Interviews** - Practice coding & system design discussions.

---

### **Happy Learning & Best of Luck with Your Backend Interview!** 🚀
