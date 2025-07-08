# Open Datalake Platform

For testing purposes only.
This project is based on the [docker-compose.yaml](https://github.com/lakekeeper/lakekeeper/blob/main/examples/minimal/docker-compose.yaml)  example from the [Lakekeeper](https://docs.lakekeeper.io) project.
Focusing on using Open Source tools to simulate a data platform

## Components

- Data Processing: [Apache Spark](https://spark.apache.org) 
- Data Storage: [MinIO](https://min.io)
- Data Format: [Iceberg](https://iceberg.apache.org)/[Parquet](https://parquet.apache.org)
- Data REST Catalog: [Lakekeeper](https://docs.lakekeeper.io) 
- Metadata Storage: [Postgres](https://www.postgresql.org)


## How to run

```sh 
docker compose --env-file .env.sample up -d
```

## UI

### MinIO

* **URL:** [http://127.0.0.1:9001](http://127.0.0.1:9001)
* **Username:** `root`
* **Password:** `adminadmin`

### Lakekeeper

* **URL:** [http://localhost:8181](http://localhost:8181)

### PySpark (Jupyter Notebook)

* **URL:** [http://localhost:8888/](http://localhost:8888/)
