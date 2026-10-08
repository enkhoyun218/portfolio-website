---
date: '1'
title: 'AML Graph'
cover: './demo.png'
github: 'https://github.com/enkhoyun218/aml-graph'
tech:
  - Python
  - Neo4j
  - Cypher
  - XGBoost
  - networkx
---

Money-laundering detection on the IBM AML bank-transaction dataset. I modeled about 5M transactions as a directed graph of 422,726 accounts in Neo4j, wrote Cypher queries for four laundering typologies (fan-out, fan-in, cycles, gather-scatter), and added graph features like PageRank and degree to an XGBoost model. On a clean temporal split, those graph features raised detection PR-AUC from 0.06 to 0.28, about a 5x improvement.
