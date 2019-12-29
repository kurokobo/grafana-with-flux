# Grafana with Flux plugin on PWS

This repository includes `manifest.yml` to run Grafana on PWS with Flux plugin.

Flux plugin is needed to use InfluxDB Cloud as a data source.

```sh
$ cf push --vars-file vars.yml 
```

Please note any of your modification through Web GUI is not permanent.