# DRL — Detection & Response Lab

A small, local security lab: a fake SSH server and a web app produce logs,
those logs flow into a search and alerting system, and one person attacks
the lab while the other detects and responds.

Everything runs on our own laptops. Nothing is exposed to the internet,
and no cloud account is used.

## Who's building what

- **DevOps (Shri Hari):** the lab's infrastructure — Docker Compose, the
  log pipeline (Promtail → Loki), Grafana dashboards, and a GitHub Actions
  CI pipeline.
- **Security (Tejaswini):** attack scenarios, MITRE ATT&CK mapping,
  detection rules, tuning, and incident response playbooks.

## Status

🚧 In progress — setup phase.

## Documentation

Full project report and prerequisites are tracked separately and linked
here once the lab is running.
