# Uber — public reconstruction

Engineering blog is unusually thick. Marketplace internals beyond named platforms stay empty.

## Public

- **Marketplace** — rider / driver / courier matching and pricing (the product). Uber, Uber Eats, Freight are public lines.
- **Michelangelo** — internal ML-as-a-service; Uber Engineering, 2017 onward. ~5k production models, real-time serving (their numbers).
- **Michelangelo 2.0** — Kubernetes + Ray; Job Controller federation; MA Studio / Canvas (2024–26 blog).
- **Palette** — feature store inside Michelangelo (Hive/Spark offline, Cassandra online — as they published).
- **Cadence** — workflow engine they open-sourced (now a public project; whether Uber still runs the original internally is **not** re-sourced here).

## Unknown
- Exact CRM / ITSM for riders, drivers, or Uber employees.
- Payments ledger / risk system names beyond “payments exist.”
- Current on-prem vs GCP/AWS/Azure split (they say multi-cloud; boxes unnamed).
