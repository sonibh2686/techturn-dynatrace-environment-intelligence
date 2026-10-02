# Architecture

High-level public architecture:

```text
Dynatrace APIs
    │
    ▼
Read-only Connector
    │
    ▼
Discovery Engine
    │
    ├── Entities
    ├── Tags
    ├── Properties
    ├── Management Zones
    └── Relationships
    │
    ▼
Normalized Evidence Store
    │
    ▼
Classification & Layer Model
    │
    ▼
Assessment Engine
    │
    ▼
Report Generator
    │
    ├── Executive Reports
    ├── Inventory Reports
    ├── Evidence Reports
    ├── Remediation Reports
    └── Environment Layer Report
```

Public examples use synthetic TechTurn data only.
