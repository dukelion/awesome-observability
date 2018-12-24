# awesome-observability

Curated list of articles and software related to observability


Articles on metrics:

- http://www.brendangregg.com/usemethod.html
- https://www.weave.works/blog/the-red-method-key-metrics-for-microservices-architecture/
- https://landing.google.com/sre/sre-book/chapters/monitoring-distributed-systems/


Instrumenting libraries:

- https://metrics.dropwizard.io/3.1.0/getting-started/ - definitions and patterns
- https://github.com/armon/go-metrics - Backend agnostic library for golang, good labels support for easy Prometheus integration
- https://github.com/rcrowley/go-metrics - Another backend agnostic library, more features, but no labels support
- https://github.com/prometheus/client_golang - Prometheus client, exporting gathered metrics to prometheus.


Graphing:

- https://grafana.com/dashboards - A collection of dashboard examples
- https://grafana.com/plugins - Plugins for grafana

Metrics storage:

- https://prometheus.io/
- https://github.com/improbable-eng/thanos
- https://github.com/Percona-Lab/PromHouse
- https://www.influxdata.com/

Useful guides:
- https://timber.io/blog/promql-for-humans/
