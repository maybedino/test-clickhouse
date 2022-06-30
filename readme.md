Start
```
docker compose up -p "ch-test"
```

Connect to the server with user "default", not password, localhost:8123

Remove everything
```
docker composes down
docker volume rm ch-test_clickhouse-test-1-data
docker volume rm ch-test_clickhouse-test-2-data
docker volume rm ch-test_clickhouse-test-3-data
```