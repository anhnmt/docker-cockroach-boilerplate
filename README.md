# docker-cockroach-boilerplate

- https://www.cockroachlabs.com/docs/v23.1/start-a-local-cluster-in-docker-windows
- https://www.cockroachlabs.com/docs/v22.2/secure-a-cluster


```bash
        start \
      --advertise-addr=roach1:26357 \
      --listen-addr=roach1:26357 \
      --http-addr=roach1:8080 \
      --sql-addr=roach1:26257 \
      --join=roach1:26357,roach2:26357 \
      --insecure
```