# OCEL Research Reproduction Project

This repository contains my work related to reproducing experiments and techniques presented in the [OCEL](https://ocel-standard.org/) (Object-Centric Event Logs) framework, based on a previously published GitHub implementation.

## 🔍 Goal

To understand and replicate key aspects of OCEL event modeling, log transformation, and analysis as introduced in the original OCEL paper:

> *Shahrzad Khayatbashi, Olaf Hartig, and Amin Jalali. (2024). Transforming Object-Centric Event Logs to Temporal Event Knowledge Graphs. Information Systems.*

---

## 🔗 Based on External Repository

This work builds upon code from the following repository:

> [BPM2024]([https://github.com/username/repo-name](https://github.com/shahrzadkhayatbashi/BPM2024))  
> Author: @shahrzadkhayatbashi  
> License: ???

## 🎯 Objective

To implement and understand the transformation of Object-Centric Event Logs (OCEL) into Temporal Event Knowledge Graphs (TEKGs), as proposed in the referenced paper. This includes:

- Parsing OCEL logs (in JSONOCEL format)
- Mapping event-object relations into temporal graphs
- Exploring knowledge graph representation of object-centric process data
---

## 📦 Data Source

The dataset used in this project is:

> **Logistics** OCEL log  
> Available from the official OCEL website: [https://ocel-standard.org/data/](https://ocel-standard.org/data/)  
> Format: `logistics.jsonocel`

This dataset represents an order fulfillment process involving multiple object types such as `Order`, `Package`, and `Item`.

---
### 🔄 What I do in this Project:
- Adapted the code to work with the official OCEL `logistics.jsonocel` dataset
- Cleaned and preprocessed OCEL logs using Python scripts
- Implemented object-event tEKG based on the paper’s transformation rules
- Exported final graph as a Neo4j-compatible format
