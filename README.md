# Air Quality Prediction
This project predicts Air Quality Index (AQI) using machine learning algorithms in **Python**.

**Status:** In Progress

## Features:
- Predict AQI from environmental parameters
- Built using scikit-learn and pandas

## Tech Stack:
- Python
- Pandas
- Scikit-learn

```mermaid
flowchart TB

User --> UI

subgraph Presentation
UI[React / Next.js]
end

subgraph Business Logic
API[FastAPI]
Services[Service Layer]
end

subgraph Data Layer
DB[(PostgreSQL)]
Redis[(Redis)]
end

UI --> API
API --> Services
Services --> DB
Services --> Redis
```
