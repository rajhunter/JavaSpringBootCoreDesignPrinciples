# 📘 Software Architecture & Design Principles

This document summarizes **core principles, patterns, and practices** that every architect and senior engineer should know.

---

## 🔹 Core Design Principles

These are the foundation of any architectural decision:

- **SOLID**
  - Single Responsibility Principle (SRP)  
  - Open/Closed Principle (OCP)  
  - Liskov Substitution Principle (LSP)  
  - Interface Segregation Principle (ISP)  
  - Dependency Inversion Principle (DIP)  

- **KISS** (Keep It Simple, Stupid)  
- **DRY** (Don’t Repeat Yourself)  
- **YAGNI** (You Aren’t Gonna Need It)  
- **Separation of Concerns**  
- **High Cohesion, Low Coupling**  
- **Encapsulation**  
- **Composition over Inheritance**  
- **Fail Fast**  
- **12-Factor App principles** (for cloud-native apps)  

---

## 🔹 Architectural Patterns

High-level patterns architects often apply:

- Layered Architecture (N-tier)  
- Hexagonal Architecture (Ports & Adapters)  
- Onion Architecture  
- Clean Architecture  
- Event-Driven Architecture (EDA)  
- Microservices Architecture  
- Service-Oriented Architecture (SOA)  
- Monolithic Architecture (with modularity)  
- Serverless Architecture  
- Event Sourcing  
- CQRS  
- Saga Pattern (Orchestration vs Choreography)  
- Strangler Fig Pattern (legacy migration)  
- Sidecar Pattern (service mesh, proxies)  

---

## 🔹 Integration / Communication Patterns

For inter-service communication & system design:

- API Gateway Pattern  
- Backend for Frontend (BFF)  
- Circuit Breaker Pattern  
- Retry & Backoff  
- Bulkhead Pattern  
- Message Broker / Pub-Sub  
- Aggregator / Composite Pattern  
- Choreography vs Orchestration (workflow handling)  
- Service Registry & Discovery (Eureka, Consul, etc.)  
- Command Pattern (used in CQRS commands)  
- Observer Pattern (events, pub-sub)  

---

## 🔹 Enterprise Integration Patterns (EIP)  

Based on *Gregor Hohpe’s book* — essential when systems talk via messaging:

- Message Channel  
- Message Broker / Queue  
- Content Enricher / Content Filter  
- Message Router / Splitter  
- Aggregator  
- Event Bus  
- Saga (long-running transactions)  

---

## 🔹 Cloud / Distributed System Principles

Architects must ensure scalability, reliability, and resilience:

- **CAP Theorem** (Consistency, Availability, Partition Tolerance)  
- **BASE vs ACID** (transactional vs eventual consistency)  
- **Idempotency** (safe retries)  
- **Sharding & Partitioning**  
- **Caching** (Cache Aside, Write-through, Write-behind)  
- **Eventual Consistency**  
- **Data Locality Principle**  
- **Resiliency Patterns** (Retry, Circuit Breaker, Fallback, Timeout)  
- **Observability Patterns** (Logging, Metrics, Tracing)  

---

## 🔹 Security Principles

Must-have for all architects:

- **Least Privilege Principle**  
- **Defense in Depth**  
- **Zero Trust Architecture**  
- **Authentication vs Authorization** (AuthN vs AuthZ)  
- **Data Encryption** (in-transit, at-rest)  
- **Secrets Management**  
- **OWASP Top 10 awareness**  

---

## 🔹 Documentation & Modeling

For clarity and communication:

- **C4 Model** (Context, Container, Component, Code)  
- **ADR** (Architecture Decision Records)  
- **UML** (Class, Sequence, Component, Deployment)  
- **Domain-Driven Design (DDD)** concepts:  
  - Entity  
  - Value Object  
  - Aggregate  
  - Repository  
  - Service  
  - Bounded Context  
  - Anti-Corruption Layer  

---

## 🔹 DevOps / Deployment Patterns

Architects must align design with delivery:

- Blue-Green Deployment  
- Canary Release  
- Rolling Updates  
- Immutable Infrastructure  
- Infrastructure as Code (IaC)  
- Service Mesh (Istio, Linkerd)  
- Sidecar / Ambassador / Adapter patterns  

---

## ✅ Summary

This guide provides a structured reference for **software architecture principles, patterns, and best practices**.  
It’s designed for **architects, senior engineers, and DevOps practitioners** to build scalable, resilient, and secure systems.

---
