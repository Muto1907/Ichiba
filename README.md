# Ichiba

## Repository layout
- `cmd/` – one folder per micro-service (only `main.go` lives here)
- `internal/` – shared helpers that are **private** to Ichiba
- `proto/` – gRPC contracts, linted by buf
- `schema/` – event payload definitions (JSON-Schema/Avro)
- `.github/workflows/` – CI/CD pipelines

## Reason to use a Monorepo
Since this is a portfolio project that I will be solely working on I decided to use a Mono-Repo for the whole project.
This allows me to have a single source of truth, centralised CI/CD pipelines and a simpler local dev experience.