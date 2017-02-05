# NATS Evaluation

A docker environment to run a nats server and some clients

## Compliance Checklist

[NATS Features](http://nats.io/documentation/#nats-features)

- [x] <= 250 ms latency
- [x] Pub/Sub
- [x] "at-least-once" (via NATS Streaming)
- [x] "at-most-once"

## NATS Performance

This article give some insigts to NATS performance with a comparison to REDIS:

[Benchmarking Message Queue Latency](http://bravenewgeek.com/benchmarking-message-queue-latency)


![alt tag](assets/Redis_latency.png)
