# Service Atlas 🧭  
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![Go Version](https://img.shields.io/badge/Backend_Go-1.25-blue?logo=go)](#)
[![Python Version](https://img.shields.io/badge/MCP_Python-3.11+-blue?logo=python)](#)
![Status: Active](https://img.shields.io/badge/Status-Active-brightgreen)
![Services: Graph](https://img.shields.io/badge/Model-Service_Graph-orange)

---

**Service Atlas** is the central place for building, exploring, and understanding the dependency graph of your service-oriented system — from microservices and databases to teams, ownership, and release metadata.  
Our mission is to give you a clear, queryable map of your system so teams can move faster with confidence.

---

## 🚀 Why Service Atlas  

As systems grow, it becomes harder to answer seemingly simple questions:

- *What services do we have?*  
- *How are they connected?*  
- *Who owns this service now?*  
- *What databases or other services does it depend on?*  
- *Where is our technical debt building up?*

Service Atlas provides a **living source of truth**, enabling:

- Better architectural decisions  
- Clear ownership  
- Easier onboarding  
- Reduced operational risk  
- Accurate impact analysis before changes  
- A foundation for developer experience tooling  

---

## 🔧 Core Capabilities  

### 📘 Model Your Services  
Create and manage services with detailed metadata:  
- Descriptions  
- Repository links  
- Ownership  
- Releases  
- Databases and other resources  

### 🔗 Map Dependencies  
Visualize and understand dependency relationships between services and subsystems.

### 🧭 Track Ownership  
A clean, queryable team → service ownership model.

### 🧹 Capture Technical Debt  
Assign service-level debt with categories like tests, documentation, libraries, architecture, or infrastructure.

### 🧵 Query from Tools, CLIs, or AI Assistants  
Use the **MCP server** for safe read-only access.  
Expose your catalog to automation without risking unintended writes.

---

## 📦 Core Projects  

| Repository | Description |
|-----------|-------------|
| **Service Atlas Backend** | The primary API service backing the catalog. Built in Go **1.25**, powered by Neo4j. Handles services, dependencies, releases, and technical debt. |
| **Service Atlas MCP Server** | A read-only MCP server exposing service & team data to external tools and assistants. Ideal for AI-driven exploration and workflow tooling. |

---

## 🛠️ Quick Start Overview  

### Backend  
- Go **1.25**  
- Neo4j database  
- Full CRUD for services, releases, dependencies, owners, and debt  
- Run locally or via Docker/Compose  
- Suitable for internal platforms & service catalog tooling

### MCP Server  
- Python 3.11+  
- Read-only safe interface  
- Provides tools like:  
  - `get_all_teams()`  
  - `get_services_by_team()`  
  - `find_service_by_name()`  
  - `get_teams_by_service()`  

---

## 📄 License  

All repositories within the **Service Atlas** organization are licensed under the **MIT License**, unless otherwise specified by a project.
