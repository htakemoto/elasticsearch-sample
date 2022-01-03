# Elasticsaerch Sample

Elasticsearch and Kibana sample project

## Requirements

* [Docker](https://www.docker.com/)

## Quick Start

```bash
docker-compose up
```

Access to http://localhost:5601/

## Clean up Database

```bash
docker-compose down --volume
```

## Tutorial

Get info about cluster health

```bash
GET _cluster/health
```

