Forked from https://github.com/helm/charts/tree/master/stable/presto

# Presto-Pulsar Chart

[Presto](http://prestodb.io/) is an open source distributed SQL query engine for running interactive analytic queries against data sources of all sizes ranging from gigabytes to petabytes.

## Chart Details

This chart will do the following:

* Install a single server which acts both as coordinator and worker
* Install a configmap for it
* Install a service

## Installing the Chart

To install the chart with the release name `my-release`:

```bash
$ helm install my-release -n pulsar E:\Devs\charts-master\stable\presto --values values.yaml
```

## Configuration

Configurable values are documented in the `values.yaml`.

Specify each parameter using the `--set key=value[,key=value]` argument to `helm install`.

Alternatively, a YAML file that specifies the values for the parameters can be provided while installing the chart. For example,

```bash
$ helm install my-release -n pulsar E:\Devs\charts-master\stable\presto --values values.yaml
```

> **Tip**: You can use the default [values.yaml](values.yaml)
