Intelligence-platform/
│
├── apps/
│   ├── dashboard-web/              # React dashboard
│   ├── admin-console/              # Governance, access, model audit
│   └── funder-portal/              # Optional external-facing funder reporting
│
├── services/
│   ├── api-gateway/                # FastAPI REST/GraphQL gateway
│   ├── ingestion-service/          # Connectors and ETL jobs
│   ├── nlp-service/                # Sentiment, topic, entity, narrative analysis
│   ├── churn-service/              # Member, donor, supporter churn models
│   ├── confounder-service/         # Causal inference and adjustment engine
│   ├── funder-service/             # 990 parsing, alignment, revenue risk
│   ├── campaign-service/           # Campaign analytics and supporter engagement
│   ├── policy-service/             # Bill, legislator, public sentiment analysis
│   ├── alert-service/              # Alerts, notifications, recommended actions
│   └── report-service/             # Impact reports, grant summaries, exports
│
├── data/
│   ├── migrations/
│   ├── seeds/
│   ├── dbt/
│   └── synthetic-data/
│
├── ml/
│   ├── feature_store/
│   ├── model_training/
│   ├── model_registry/
│   ├── evaluation/
│   └── fairness_audits/
│
├── infrastructure/
│   ├── terraform/
│   ├── kubernetes/
│   ├── helm/
│   └── observability/
│
└── docs/
    ├── architecture/
    ├── data-governance/
    ├── threat-model/
    ├── model-cards/
    └── api/
