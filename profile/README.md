## Karakoram

Self-hosted database and stateful-service orchestration on infrastructure you run: Zerops, Dokploy or Nomad. No Kubernetes and no hosted coordinator.

One control plane creates, heals, scales, backs up and upgrades PostgreSQL (including Supabase, PostGIS, pgvector, TimescaleDB and Citus), MySQL and Percona XtraDB Cluster, MongoDB, Elasticsearch, RabbitMQ, Neo4j, Weaviate, OpenBao, Temporal and Keycloak. You drive it through a REST API, a CLI, a web UI or an MCP server, which is read-only by default.

Every release is tested live on the providers it supports, and the known issues go into the release notes and the docs rather than a footnote. Engines that haven't been verified on every provider stay marked experimental.

- [Karakoram](https://github.com/KarakoramDev/Karakoram): the orchestrator (Apache-2.0)
- [karakoram.dev](https://karakoram.dev): documentation and getting started
- [Releases](https://github.com/KarakoramDev/Karakoram/releases) and [known limitations](https://karakoram.dev/docs/limitations/)

Contributions and bug reports are welcome; start with [CONTRIBUTING.md](https://github.com/KarakoramDev/Karakoram/blob/main/CONTRIBUTING.md).
