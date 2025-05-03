
## System Design

### Load Balancing
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

### Caching
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

### Database Scaling
Process of increasing the capacity of the server according to the load or other parameters
**Types of Scaling**
- **Vertical Scaling:** 
  * Adding more resources to a single server (like CPU, RAM etc)
- **Horizontal Scaling:** 
  * Add more server (Node) to distribute the load.


### Microservices vs Monolith
- **Monolith:** Easier development, harder scaling
- **Microservices:** Independent services, better scaling, more complexity

### Message Queues
A Message Queue is a communication system that allows different parts of a system to communicate asynchronously by passing messages via a queue.
* Producers: Sends the message to the queue
* Subscribers: Receives the message from the queue

#### When to use Queue?
  1. **Decoupling**: When services are not tightly interlinked with each other.
  2. **Asynchronous processing**: When services needs to run independently.
  3. **Load leveling**: Optimize the load on the server.
  4. **Resilience**: Holds the data even when service is down and can consume the message when system is back.

#### **Brokers:** 
  1. Apache Kafka
  2. RabbitMQ 
  3. AWS SQS

#### Core concepts
1. Queue: 
  * FIFO (First In First Out)
  * Holds message until consumed
  Used By: RabbitMQ and AWS SQS
2. Topic: 
  * Similar to PUB/SUB. One Producer and Many Subscribers.
  Used By: Apache Kafka, RabbitMQ.
3. Exchange: 
  * Depending on the Rules data is directs to different queues
  Used By: RabbitMQ
4. Partition:
  * Splits messages across the partitions for parallel processing
  Used By: Apache Kafka.
