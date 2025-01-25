# Issue: Connection Failed - PostgreSQL Root User Access

## Problem Description
When attempting to connect to PostgreSQL database using root user credentials after running a Docker container, the following error was encountered:
```connection failed: role "root" does not exist```

### Initial Docker Setup Command
```bash
docker run -it \
      --network=pg-network\
      -e POSTGRES_USER="root" \
      -e POSTGRES_PASSWORD="root" \
      -e POSTGRES_DB="ny_taxi" \
      -v $(pwd)/ny_taxi_postgres_data:/var/lib/postgresql/data \
      -p 5432:5432 \
    postgres:13

