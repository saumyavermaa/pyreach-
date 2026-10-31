| Name             |                        Role                  | GitHub         |
|------------------|----------------------------------------------|----------------|
| Saumya Verma     | Team Lead(Integration, CLI, reporting, repo) |saumyavermaa    |
| Devanshi Kumari  | Data and API                                 |Devanshiheree   |
| Shreyansh Rathaur| Code Analysis and Tests                      |shreyanshrathaur|

## Problem Statement
Problem 03: Python Vulnerability Reachability Analyzer**
Build a tool that determines whether known vulnerable dependency code
can be reached from a project's own application code, classifying
findings as reachable, not reachable, or uncertain.

## Selected Models and Justification
This project does not use any AI/LLM models. Reachability analysis is
done with deterministic static analysis (Python `ast`), so results are
reproducible and every verdict can be traced to concrete evidence.
Determinism also supports our core goal of never falsely declaring a
project safe.
