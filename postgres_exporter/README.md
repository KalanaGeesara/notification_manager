<!-- PROJECT LOGO -->
<br />
<p align="center">

  <h3 align="center">Prometheus based alert system</h3>

  <p align="center">
    Implementing prometheus based alert mechanism to generate alerts for the user specified database changes.
  </p>
</p>


<!-- GETTING STARTED -->
## Getting Started

There are 2 methods you can follow.

### Methos 1

1. docker run  --net=host --name=postgres_exporter -v <path_to_queries.yaml>:/queries/queries.yaml -e DATA_SOURCE_NAME="postgresql://postgres:postgres@localhost:5432/ops_manager_db?sslmode=disable" -e PG_EXPORTER_EXTEND_QUERY_PATH="queries/queries.yaml"  quay.io/prometheuscommunity/postgres-exporter 

### Methos 2

1. docker build . -t postgres_exporter 
2. docker run --net=host --name=postgres_exporter -p 9187:9187 postgres_exporter





   

