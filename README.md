# Oracle SQL Logistics & Delivery System

## Executive Summary
This project involves the end-to-end architecture and implementation of a **relational database system** designed to support the operations of a logistics and courier company ("FastDelivery").

The primary objective was to design a **scalable and normalized data schema** capable of handling complex relationships between distribution hubs, fleet logistics, and customer orders. The solution progresses from high-level conceptual modeling to a fully implemented physical schema in **Oracle Database**.

## Domain Modeling & Scope
The database models the complete lifecycle of a package delivery process, enforcing strict **Data Integrity** and **Business Rules**:

* **Logistics Management:** Tracks the flow of goods between **Distribution Centers** and final destinations.
* **Fleet & Personnel:** Manages driver assignments, vehicle availability, and shift scheduling.
* **Routing Logic:** Associates packages with specific delivery routes and tracking checkpoints.
* **CRM (Customer Relationship Management):** Handles sender/receiver data and order history.

## Technical Methodology

### 1. Database Design Strategy
The project followed a rigorous design lifecycle:
* **Conceptual Design:** Utilization of **SAP PowerDesigner** to create Entity-Relationship (ER) models, defining cardinality and business constraints.
* **Logical Design:** Translation into a relational schema, strictly adhering to the **Third Normal Form (3NF)** to eliminate data redundancy and anomalies.
* **Physical Implementation:** Writing optimized **DDL (Data Definition Language)** scripts for Oracle SQL, including primary/foreign keys, constraints, and indexes.

### 2. Technology Stack
* **RDBMS:** Oracle Database (PL/SQL environment).
* **IDE:** Oracle SQL Developer.
* **Modeling Tools:** SAP PowerDesigner (for ER diagrams).

## System Artifacts

### Conceptual Data Model
*Visual representation of entities and relationships before normalization.*
[Inserir Imagem do Modelo Conceitual aqui]

### Physical Database Schema
*The final implementation schema illustrating tables, columns, and foreign key constraints.*
[Inserir Imagem do Modelo Físico aqui]

---

## Academic Context
This project was engineered as part of the **"Databases"** course curriculum (2024/2025).

**Team Size:** 4 Members
**Final Evaluation:** 9.2 / 10
