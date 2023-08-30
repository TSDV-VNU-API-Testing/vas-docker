# Vas - Validator for Schemathesis

**NOTE**:

- Services run on 3 port `4173`, `4174`, `4175`
- `4173` for client, `4174` for server, `4175` for documentation website
- File `volume/log/run.log` contains all log of server
- Folder `volume/result` contains results of test execution.
- Folder `volume/apache` contains Apache Web Server log.
- Example: `volume/result/0a1cd7bc-adea-492b-bdbb-d19a7e88fdb3/result.json` contains result as JSON of test ID `0a1cd7bc-adea-492b-bdbb-d19a7e88fdb3`

## Installation

```bash
cd vas-docker/
sudo chmod -R 777 volume
docker compose up
```
