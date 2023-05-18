# docker-notes

### basic commands

`<name> <dir where the Dockerfile is>`
docker build -t test_duckdb .

`<memory requires global setting to be larger>`
docker run --rm -it --memory=50g test_duckdb
