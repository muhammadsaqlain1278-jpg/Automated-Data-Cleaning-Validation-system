# Automated-Data-Cleaning-Validation-system                 ┌──────────────────┐
Raw Dataset ────►│  Data Ingestion  │
                 └────────┬─────────┘
                          ▼
                 ┌──────────────────┐
                 │ Data Profiling   │
                 │ • Schema         │
                 │ • Types          │
                 │ • Missingness    │
                 │ • Statistics     │
                 └────────┬─────────┘
                          ▼
                 ┌──────────────────┐
                 │ Data Cleaning    │
                 │ • Missing values │
                 │ • Duplicates     │
                 │ • Formatting     │
                 │ • Type fixes     │
                 └────────┬─────────┘
                          ▼
                 ┌──────────────────┐
                 │ Validation       │
                 │ • Rules          │
                 │ • Constraints    │
                 │ • Consistency    │
                 └────────┬─────────┘
                          ▼
                 ┌──────────────────┐
                 │ Anomaly Detection│
                 │ • Statistical    │
                 │ • ML-based       │
                 └────────┬─────────┘
                          ▼
                 ┌──────────────────┐
                 │ Quality Scoring  │
                 │ + Error Report   │
                 └────────┬─────────┘
                          ▼
                 ┌──────────────────┐
                 │ Clean Dataset    │
                 │ / Reject Dataset │
                 └──────────────────┘