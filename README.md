# Example



# Prerequisite

- [Docker Desktop](https://www.docker.com/products/docker-desktop)

# Run it

```shell
docker-compose up
```

You will see the result of the following image.

![]()

- Access Grafana `https://localhost:3000`
- Set up Prometheus by Grafana **data source**

![]()

- Input `http://prometheus:9090` in the URL column.(It would be automatically mapped by docker-compose setting)

![]()

- Import `Prometheus 2.0 stats` dashboard.

![]()

- Watch results.

![]()


# License

[MIT]()