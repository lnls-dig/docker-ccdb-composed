# Docker Compose for Wildfly (running CCDB Service) + Postgres

## Running instructions

	docker-compose up -d

The REST interface should be available at:

	http://localhost:8446

## Systemd Integration

To integrate this as a systemd service, do:

    make install

To remove the systemd service and its additional files:

    make uninstall
