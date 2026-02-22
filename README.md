# Platform Maturity Scoreboard

Track platform readiness and engineering velocity risk metrics.

## Priority Metadata

- ID: 140
- Domain: infrastructure
- TTE (days): 2
- Exposure score: 8/10
- Wave: 1
- Priority score: 8.00

## Phase-1 Build

1. Risk/exposure assessment API.
2. Deterministic launch planning endpoint.
3. Domain-tailored threat and rollout docs.
4. CI test gate and local runnable service.
5. Spatial 3D starter (for spatial projects).

## Run

```bash
python3 -m venv .venv
source .venv/bin/activate
pip install -e .[dev]
make test
make run
```
