# Prometheus
Using the client libraries, custom metrics to an application can be exposed.

Metric type:

Counter: Can be used to represent a numeric value that only increase or can be reset/restart. eg: number of requests served,task completed etc.

Gauge: a numberical value that either goes up and down.

Summary: it is used to represent how long the application took to respond, latency and request sizes.

Histogram: Same as summary metric type but counts the time series in a configurable buckets for the calculation of quantiles.
