
## Databases (MySQL & MongoDB)

### MySQL

#### ACID Transactions
- **Atomicity:** Ensures complete success or failure
- **Consistency:** Ensures DB remains valid after transaction
- **Isolation:** Controls concurrent execution
- **Durability:** Ensures transaction permanence

#### Indexing & Query Optimization
- **Index Types:** Primary, Secondary, Composite
- **EXPLAIN:** Analyzing query plans for optimization

#### Normalization vs Denormalization
- **Normalization:** Avoids redundancy (1NF, 2NF, 3NF)
- **Denormalization:** Increases redundancy for performance

#### Partitioning
- **Types:** Range, List, Hash Partitioning
- **Use Case:** Large dataset performance optimization

#### Replication & Failover
- **Types:** Master-Slave, Master-Master
- **Use Case:** High Availability (HA)

---

### MongoDB

#### CRUD Operations
- **Create:** `db.collection.insertOne()`
- **Read:** `db.collection.find()`
- **Update:** `db.collection.updateOne()`
- **Delete:** `db.collection.deleteOne()`

#### Schema Design
- **Embedding:** Stores related data together (fast reads)
- **Referencing:** Stores related data separately (normalized, flexible)

#### Aggregation Framework
- **Stages:** `$match`, `$group`, `$sort`, `$project`
- **Use Case:** Data analytics, reporting

#### Sharding & Replication
- **Sharding:** Splits data across multiple servers
- **Replication:** Ensures redundancy for failover

#### Performance Optimization
- **Indexes:** Improves query performance
- **Profiling:** `db.setProfilingLevel(2)` to analyze slow queries

#### Change Streams
- **Use Case:** Real-time updates in event-driven architectures

---
