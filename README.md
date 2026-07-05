# Data Engineering Pipeline

**Data engineers shipping production pipelines: ingest, transform, serve & trust the data.** — built in-house by [Skill&nbsp;Me](https://skillme.dev).

Stand up data pipelines you can run in production and trust. Reach for this when you're moving data end to end - streaming ingestion off Kafka, batch transforms in Spark, an analytics store in ClickHouse - and need quality checks and query tuning so the numbers downstream are correct and fast. Built for the engineer who owns the pipeline, not the analyst querying its output.

⭐ **If this is useful, star the repo** — it's how we gauge what to build next.

## Install

- **From the catalog:** [skillme.dev/pack/data-engineering-pipeline](https://skillme.dev/pack/data-engineering-pipeline) — install the whole pack into Claude in one step.
- **With the skills CLI:** `npx skills add SkillMedev/data-engineering-pipeline`
- **Manually:** copy any `skills/<slug>/SKILL.md` into your Claude skills directory.

## Skills in this pack

- **[Kafka Pipelines](skills/kafka-pipelines/SKILL.md)** — Designs Kafka streaming pipelines end to end - partition-count sizing math, key choice, consumer-group sizing, offset strategy, delivery semantics, poll tuning, and dead-letter handling - with production configs.
- **[Spark & PySpark](skills/spark-jobs/SKILL.md)** — Writes and tunes PySpark jobs - join strategy and broadcast size limits, shuffle-partition sizing, skew diagnosis and salting, UDF avoidance, caching, and output file layout - with concrete size and skew thresholds.
- **[ClickHouse Analytics](skills/clickhouse-analytics/SKILL.md)** — Designs ClickHouse schemas and queries for fast analytics - MergeTree engine selection, ORDER BY key design, partitioning, materialized views, and projections.
- **[Data Quality Framework](skills/data-quality/SKILL.md)** — Designs layered data quality checks across completeness, validity, consistency, uniqueness, timeliness, and accuracy, with severity tiers, freshness SLAs, and anomaly baselines wired into dbt and CI.
- **[Time Series Analysis](skills/time-series/SKILL.md)** — Decomposes and forecasts time-indexed data with STL, ARIMA/SARIMA, and Prophet, validated by time-ordered backtests against a seasonal-naive baseline.
- **[Feature Engineering](skills/ml-feature-engineering/SKILL.md)** — Designs ML features with leakage-safe pipelines, correct categorical encoding by cardinality, numeric transforms, and validation that a feature earns its place.
- **[SQL Query Optimizer](skills/sql-query-optimizer/SKILL.md)** — Diagnoses slow SQL from the execution plan, names the cost driver, and delivers the rewritten query plus index DDL with the expected plan change and write-side cost stated.
- **[MongoDB Expert](skills/mongodb-expert/SKILL.md)** — Designs MongoDB schemas, indexes, and aggregation pipelines that perform - embed-vs-reference decision rules, the 16MB document limit, ESR compound-index ordering, explain-plan verification, and operational settings for replica sets and sharding.

## License

MIT — see [LICENSE](LICENSE). Skills are portable `SKILL.md` files; the canonical
copies live in the [Skill&nbsp;Me catalog](https://skillme.dev).
