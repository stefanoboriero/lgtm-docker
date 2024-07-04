# lgtm-docker
Docker-compose configuration for the LGTM observability stack, all interfaced via the OTel collector

## Running

You can run this project using `docker-compose build` and `docker-compose up` (newer docker compose versions commands do not use the hyphen between docker and compose words). You can then send data to the local opentelemetry collector that opens the standars `4317` and `4318` ports.
