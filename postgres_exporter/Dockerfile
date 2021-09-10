FROM quay.io/prometheuscommunity/postgres-exporter

ENV DATA_SOURCE_NAME="postgresql://postgres:postgres@localhost:5432/ops_manager_db?sslmode=disable"
ENV PG_EXPORTER_EXTEND_QUERY_PATH=queries/queries.yaml
ADD queries.yaml /queries/

EXPOSE 9187
EXPOSE 5432
