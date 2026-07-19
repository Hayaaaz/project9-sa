# Project 9 — Ask Your Logs

This project sets up an observability pipeline using Prometheus, Grafana, OpenSearch, and OpenSearch Dashboards. The stack is launched with `docker-compose.observability.yml`, and sample logs are loaded into OpenSearch.

## Included in this repository

- **Grafana dashboard** with:
  - p95 latency panel  
  - error-ratio panel  
  (PromQL queries shown in REPORT.txt)

- **Manual incident analysis** for the 14:05 checkout failure  
  (root cause, affected users, symptom vs. cause)

- **AI-assisted log queries** using `ask_logs.py`  
  (AI-generated filters and outputs stored in `agent-log.txt`)

- **Human vs. AI comparison**  
  (verdicts stored in `keeping-watch.txt`)

- **All required screenshots**  
  located in the `screenshots/` folder

- **Full project summary**  
  provided in `REPORT.txt`

