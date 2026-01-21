# Project Status: Architecture Design & Algorithm Selection

Objective: Developing a hybrid optimization engine to solve multi-objective resource allocation problems in $500M+ industrial portfolios.

##  Proposed Architecture:

Algorithm: Hybrid approach combining Exact Methods (MILP via PuLP) for cost constraints and Metaheuristics (NSGA-II via pymoo) for risk minimization.

Backend: Asynchronous inference API using FastAPI.

Data Layer: PostgreSQL for relational project data storage.
