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
| 1 | Arrays | [Load Balancing](#load-balancing) | ACID Transactions (MySQL) |
| 2 | Linked Lists | [Caching Strategies](#caching) | CRUD & BSON (MongoDB) |
| 3 | Stacks & Queues | [DB Scaling](#database-scaling) | Indexing & Joins (MySQL) |
| 4 | HashMaps & HashSets | Message Queues | Aggregation Framework (MongoDB) |
| 5 | Trees & BSTs | API Rate Limiting | Normalization vs. Denormalization (MySQL) |
| 6 | Tries (Prefix Tree) | Authentication & Authorization | Schema Design (MongoDB) |
| 7 | Graphs (BFS, DFS) | Microservices vs Monolith | Query Optimization (MySQL) |
| 8 | Shortest Path (Dijkstra, Bellman-Ford) | Event-Driven Architecture | Indexing (MongoDB) |
| 9 | Heaps | CAP Theorem | Stored Procedures & Triggers (MySQL) |
| 10 | Segment Trees | Distributed Caching | Sharding & Replication (MongoDB) |
| 11 | Union-Find (Disjoint Set) | Unique ID Generation | Partitioning & MVCC (MySQL) |
| 12 | Dynamic Programing Basics | Distributed Transactions | Transactions (MongoDB) |
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
Disturbing traffics across the servers for high availability, Scalability.
- **Algorithm's:** 
  1. Round Robin: Redirects traffic in cyclic order without considering the server size.
  2. Weighted Round Robin: Similar to round robin but more the weight more the traffic. 
  3. Least Connections: Redirects traffic to least active connection server.
  4. least response time: Redirects traffic which has least response time.
  5. IP Hash: Depends on the IP Address
  6. URL Hash: Depends on the URL
- **Types of Load balancers** 
  1. Hardware Load Balancers: Application specific designed IC (Integrated Circuit) used.
  2. Software Load Balancers: Specific software used with Algorithm using standard server or VM (Virtual Machine).
  3. DNS Load Balancing: In Domain Name System, loads are balanced by passing the same different IP address for same domain.
  4. Global Server Load Balancers:  

- **Use Case:** Distributing load across servers

#### Caching
Caching is the process of storing copies of data in a temporary storage (called a cache) so that future requests can be served faster.
- **Importance**:
  1. Reduces latency.
  2. Reduces load on DB or API.
  3. Improves efficiency.
- **Layers**:
  1. Client-side caching: browser caching.
  2. CDN Caching: Eg Cloudflare, Akamai.
  3. Application level: Local caching in code.
  4. DB level Caching: Redis, Memcached.
  
- **Strategies:** 
  1. LRU (Least Recently Used): 
    - Removes least recently used data.
    - Good for data which is repeatedly accessed
  2. LFU (Least Frequently Used):
    - Removes least frequently used data.
    - Good for frequently accessed.
  3. Write-back:
    - Data is written to cache first then to DB.
  4. Write-through:
    - Data is written to DB then Updated cache
- **Tools:** Redis, Memcached

#### Database Scaling
Process of increasing the capacity of the server according to the load or other parameters
**Types of Scaling**
- **Vertical Scaling:** 
  * Adding more resources to a single server (like CPU, RAM etc)
- **Horizontal Scaling:** 
  * Add more server (Node) to distribute the load.


#### Microservices vs Monolith
- **Monolith:** Easier development, harder scaling
- **Microservices:** Independent services, better scaling, more complexity

#### Message Queues
- **Brokers:** Kafka, RabbitMQ, SQS
- **Use Case:** Decoupling systems, asynchronous processing


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
