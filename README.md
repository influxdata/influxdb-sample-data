# Influxdb Sample Datasets

This repository contains sample time series data used to test InfluxDB.

## Why sample data

Running benchmarks with synthetic tests often does not reflect real-world use. This repo is meant to be a collection of "real-world" time series datasets so testing can model more usage scenarios.

## Data format

All datasets should be a file containing newline separated, InfluxDB formatted JSON blobs. Each line should be able to be directly written to InfluxDB, e.g. via a `curl -XPOST '...'`.
