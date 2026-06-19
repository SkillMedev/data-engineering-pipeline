# Data Engineering Pipeline

**Streams, batch, and storage — production data pipelines, encoded.** — built in-house by [Skill&nbsp;Me](https://skillme.dev).

Build and run production data pipelines. Kafka streaming, Spark batch jobs, ClickHouse analytics, data quality checks, time-series modeling, ML feature engineering, and query optimization.

⭐ **If this is useful, star the repo** — it's how we gauge what to build next.

## Install

- **From the catalog:** [skillme.dev/pack/data-engineering-pipeline](https://skillme.dev/pack/data-engineering-pipeline) — install the whole pack into Claude in one step.
- **With the skills CLI:** `npx skills add aouellets/data-engineering-pipeline`
- **Manually:** copy any `skills/<slug>/SKILL.md` into your Claude skills directory.

## Skills in this pack

- **[Kafka Pipelines](skills/kafka-pipelines/SKILL.md)** — Designs Kafka topics, consumer groups, offset management, and dead-letter queues.
- **[Spark & PySpark](skills/spark-jobs/SKILL.md)** — Writes optimized PySpark jobs with partitioning, caching, and UDF strategies.
- **[ClickHouse Analytics](skills/clickhouse-analytics/SKILL.md)** — Writes ClickHouse queries with proper table engines, materialized views, and projections.
- **[Data Quality Framework](skills/data-quality/SKILL.md)** — Designs data quality checks — completeness, validity, consistency, timeliness — with monitoring.
- **[Time Series Analysis](skills/time-series/SKILL.md)** — Applies ARIMA, Prophet, and decomposition to forecast and analyze time-series data.
- **[Feature Engineering](skills/ml-feature-engineering/SKILL.md)** — Designs ML features: encoding, scaling, interaction terms, and leakage prevention.
- **[SQL Query Optimizer](skills/sql-query-optimizer/SKILL.md)** — Explains and rewrites slow queries with index recommendations and execution-plan reasoning.
- **[MongoDB Expert](skills/mongodb-expert/SKILL.md)** — Designs MongoDB schemas, indexes, aggregation pipelines, and change streams.

## License

MIT — see [LICENSE](LICENSE). Skills are portable `SKILL.md` files; the canonical
copies live in the [Skill&nbsp;Me catalog](https://skillme.dev).
