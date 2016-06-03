## telegraf-docker-custom

Templated telegraf container based on alpine and dockerize

#### Default template values

    DOCKERIZE_VERSION v0.2.0
    INFLUXDB_HOST influxdb
    TELEGRAF_DB metrics
    TELEGRAF_USER metrics
    TELEGRAF_PASSWORD metrics
    TELEGRAF_INTERVAL 30s
    TELEGRAF_INTERVAL_FLUSH 25s
    TELEGRAF_INTERVAL_JITTER 5s
