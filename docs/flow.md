---
title: Flæði og ferlar
---

# Flæði og ferlar (Mermaid)

## PR-jafningjarýni og samþætting

```mermaid
flowchart LR
  A[Grein (branch)] --> B[Pull Request]
  B --> C{Jafningjarýni}
  C -->|Athugasemdir| D[Endurbætur]
  D --> B
  C -->|Samþykkt| E[Merge]
  E --> F[Handover + Uppfært README]
  E --> G[Ólokin atriði -> Issue]
```