# Example

# Prerequisite

- [Docker Desktop](https://www.docker.com/products/docker-desktop)

# Run it

```shell
docker-compose up
```

You will see the command result of the following image.

![command](https://raw.githubusercontent.com/louis70109/prometheus-grafana-py/master/public/docker-command.png)

# Steps

- Access Grafana `https://localhost:3000`
- Set up Prometheus by Grafana **data source**

![data1](https://raw.githubusercontent.com/louis70109/prometheus-grafana-py/master/public/data1.png)

- Input `http://prometheus:9090` in the URL column.(It would be automatically mapped by docker-compose setting)

![setting](https://raw.githubusercontent.com/louis70109/prometheus-grafana-py/master/public/setting.png)

- Import `Prometheus 2.0 stats` dashboard.

![dashboard](https://raw.githubusercontent.com/louis70109/prometheus-grafana-py/master/public/dashboard.png)

- Watch results.

![result](https://raw.githubusercontent.com/louis70109/prometheus-grafana-py/master/public/result.png)

# License

[MIT](https://github.com/louis70109/prometheus-grafana-py/blob/master/LICENSE)