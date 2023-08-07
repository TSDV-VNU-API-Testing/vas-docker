# Vas - Validator for Schemathesis

**NOTE**:

- Services run on 2 port `4173`, `4175`
- `4173` for client and server (server use `/api`) and `4175` for documentation website
- File `volume/log/run.log` contains all log of server
- Folder `volume/result` contains results of test execution.
- Folder `volume/apache` contains Apache Web Server log.
- Example: `volume/result/0a1cd7bc-adea-492b-bdbb-d19a7e88fdb3/result.json` contains result as JSON of test ID `0a1cd7bc-adea-492b-bdbb-d19a7e88fdb3`

## Installation

```bash
cd vas-docker/
docker compose up
```
