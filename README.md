# System Design Learning Plan

## Day-wise Schedule

### 1. Core Concepts
#### ✅ Day 1
1. What is System Design?	[link](https://www.geeksforgeeks.org/what-is-system-design-learn-system-design/)		
  
##### 2. System Design Strategies [link](https://www.geeksforgeeks.org/software-engineering-system-design-strategy/) 
          Top-Down Design:
          Starts with a high-level view and breaks it down into smaller parts.
          Useful for planning and organizing complex systems.
          Example: Designing a website by first outlining main pages, then detailing each section.
          Bottom-Up Design:
          Begins with individual components and builds up to form the whole system.
          Useful when reusable components are available.
          Example: Building a database by first creating tables, then connecting them into a complete structure.
          Iterative Design:
          Develops the system through repeated cycles, refining with each iteration.
          Involves gathering feedback at each stage.
          Example: Releasing an app version, collecting user feedback, and improving features in each update.
          Incremental Design:
          Adds functionality in small, completed parts over time.
          Focuses on gradual expansion of system capabilities.
          Example: Building a payroll system by implementing salary calculation first, then adding tax and leave management.
          Agile Design:
          
          Flexible and iterative, adapts to changing requirements.
          Emphasizes collaboration, feedback, and quick adjustments.
          Example: Developing a social media app, adjusting features based on continuous user feedback and team input.
##### 3. High Availability vs Fault Tolerance [link](https://www.freecodecamp.org/news/high-availability-fault-tolerance-and-disaster-recovery-explained/)		
     High Availability Systems are online as often as possible, very less downtime. its main purpose to minimize downtime.
     Fault Tolerant system works even there is any failure occurs in a system (by using standby(backup) resource.
   
#### 4. Horizontal and Vertical Scaling [link](https://www.freecodecamp.org/news/horizontal-vs-vertical-scaling-in-database/)		
      Horizontal Scaling means adding more data resources ,easy to upgrade ,implement, limitless scaling , more cost,used when users are more than thousands.
      Vertical Scaling means increasing the capacity of the single resources,cost efficient , easy to use and implement.
5. High Level Design vs Low Level Design [link](https://www.geeksforgeeks.org/difference-between-high-level-design-and-low-level-design/)

### 2. Caching Fundamentals
#### Day 2
1. What is Caching?		[link](https://blog.algomaster.io/p/4d7d6f8a-6803-4c7b-85ca-864c87c2cbf2)		
2. Caching in System Design				
3. Write-Through Caching [link](https://blog.algomaster.io/p/top-5-caching-strategies-explained)			
4. Write-Back Caching
5. Write-Around Caching		

#### Day 3		
6. Cache-Control Directives [link](https://medium.com/@yadav-ajay/cache-control-6676620f31c0)		
7. Cache Eviction Policies [link](https://www.geeksforgeeks.org/cache-eviction-policies-system-design/)

### 3. Performance and Reliability
#### Day 4
1. Bandwidth and Throughput				
2. Latency				
3. Response Time	

#### Day 5
4. Reliability and Redundancy				
5. Trade-offs in High-Level Design

### 4. Architecture Patterns
#### Day 6
1. Monolithic vs Distributed Systems				
2. Characteristics of Microservice Architecture				
3. Benefits of Microservice Architecture	

#### Day 7
4. Challenges of Microservice Architecture				
5. Service Discovery in Microservices				
6. Service Mesh for Microservices	

#### Day 8
7. Service-Oriented Architecture (SOA)				
8. Event-Driven Architecture

### 5. System Design Trade-offs
#### Day 9
1. Strong Consistency vs Eventual Consistency				
2. Caching in System Design				
3. Load Balancing in High-Level Design				
4. Sharding and Partitioning

### 6. Common Caching Solutions
#### Day 10
1. Redis Cache				
2. Memcached				
3. CDN Caching	

#### Day 11
4. Cache Hierarchies				
5. Cache Invalidation in Distributed Systems				
6. Cache Strategies

### 7. Storage and Memory Management
#### Day 12
1. Block Storage vs. Object Storage vs. File Storage				
2. Memory Allocation Techniques				
3. Garbage Collection Algorithms	

#### Day 13
4. Read/Write Optimizations				
5. Data Sharding Techniques				
6. Compression Techniques for Data Storage				
7. Managing Disk I/O for Performance

### 8. Networking Essentials
#### Day 14
1. Understanding Networking				
2. TCP/IP Model Overview				
3. HTTP and HTTPS Protocols				
4. DNS Fundamentals

### 9. Network Topologies and Traffic Management
#### Day 15
1. Client Server Architecture				
2. Peer-to-Peer Architecture				
3. DNS Traffic Management	

#### Day 16
4. Global Traffic Management				
5. Managing Traffic with CDN Caching

### 10. Load Distribution Strategies
#### Day 17
1. Introduction to CDN Caching				
2. Introduction to Edge Networks				
3. Load Balancing Overview	

#### Day 18
4. Load Balancing Algorithms				
5. DNS-based Load Balancing				
6. Software-based Load Balancing

### 11. Message Queues
#### Day 19
1. Pub/Sub Messaging				
2. Publisher Subscriber Pattern				
3. Message Brokers

#### Day 20
4. Kafka Topics				
5. Kafka Partitions and Consumer Groups				
6. Rabbit MQ Message Broker				
7. RabbitMQ Exchange Types	

#### Day 21
8. Queue in RabbitMQ				
9. SQS (Simple Queue Service)				
10. Event Sourcing and CORS

### 12. Inter-Service Communication
#### Day 22
1. gRPC vs REST for Low-Latency Communication				
2. Event-Driven Communication				
3. Circuit Breaker and Retry Mechanisms	

#### Day 23
4. Handling Failures in Distributed Communication				
5. Designing APIs for Scalability				
6. API Rate Limiting and Throttling				
7. Load Balancer vs. API Gateway

### 13. Network Security and Protection
#### Day 24
1. Network Security Fundamentals				
2. SSL/TLS Encryption				
3. Firewalls		

#### Day 25
4. VPN				
5. DoS Attack and Its Prevention				
6. DDoS Attack and Its Prevention

### 14. Authentication & Access Control
#### Day 26
1. Role-Based Access Control				
2. OAuth 2.0 Authorization				
3. JWT for Stateless Authentication	

#### Day 27
4. Session-Based vs Token-Based Authentication				
5. API Key Management for Secure Access				
6. Multi-Factor Authentication				
7. Securing APIs with OAuth and JWT

### 15. Database Design Fundamentals
#### Day 28
1. RDBMS Concepts				
2. ACID Properties				
3. SQL vs NoSQL	

#### Day 29
4. Indexing				
5. B Tree				
6. B+ Tree

### 16. Query Optimization
#### Day 30
1. Introduction to Query Optimization				
2. Query Optimization Techniques				
3. Efficient Data Access Patterns	

#### Day 31
4. Reducing Database Load				
5. Indexing for Performance

### 17. Advanced Systems
#### Day 32
1. CAP Theorem				
2. NoSQL Introduction				
3. NoSQL Types

#### Day 33
4. ACID vs BASE				
5. Bloom Filters				
6. Secure Password Storage

### 18. Data Modeling
#### Day 34
1. What is a Database Model?				
2. Scalable Data Models				
3. Normalization Introduction	

#### Day 35
4. Denormalization in Databases				
5. Normalization vs Denormalization				
6. CAP in Schema Design				
7. Distributed Database Design

### 19. Architecture Patterns
#### Day 36
1. Polyglot Persistence				
2. Event Sourcing and CQRS

#### Day 37
3. Database Federation				
4. Disaster Recovery Strategies

### 20. Real-Time Systems
#### Day 38
1. Kafka Stream Processing for Real-Time Data				
2. Event Sourcing				
3. CQRS for Event-Driven Systems	

#### Day 39
4. Designing for Eventual Consistency				
5. Stream Processing vs Batch Processing

### 21. Security and Performance Optimization
#### Day 40
1. Secure Communication Protocols				
2. Zero Trust Architecture				
3. System Performance Concepts	

#### Day 41
4. Load Testing Tools				
5. Stress Testing to Identify Bottlenecks				
6. Memory Leak Detection and Prevention
