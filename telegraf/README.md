# Telegraf Plugin for Hassio

This is a very simple hassio plugin that ebnables you to run telegraf on your hassio system, I am still working on this so please bear with me, I am happy to accept PR's

# Config

The config is simple but there are some things to consider,

You must have a running influxDB instance (the hassio plugin works)

```bash
influxDB
```

This allows you to specify the location and port for your influxDB instance (the port must be specified)

```bash
influx_db
```

This is the database within influxDB to use (you may need to create this)

```bash
influx_user
```

This is the username telegraf will use to communicate with InfluxDB

```bash
influx_pw
```

This is the password to coinside with the username

```bash
retentiomn_policy
```

This is the retention policy to use (again you may need to specify this when setting up the db)


# Known issues

For some reason at the moment i have figured out how to communicate with the docker.sock therefore i cannot get the process' for docker contaisners. I will look into this and fix it when i can, if you have any idea please submit a PR

