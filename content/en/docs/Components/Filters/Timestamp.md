---
title: "Timestamp"
weight: 24
date: 2021-03-12
---
{{% pageinfo color="primary" %}}

**Read the [API documentation &raquo;](https://pkg.go.dev/github.com/AdRoll/baker/filter#Timestamp)**
{{% /pageinfo %}}

## Filter *Timestamp*

### Overview
Sets a field to the Unix Epoch timestamp at which the record is processed

### Configuration

Keys available in the `[filter.config]` section:

|Name|Type|Default|Required|Description|
|----|:--:|:-----:|:------:|-----------|
| Field| string| ""| true| field to set to the unix Epoch timestamp|
