# Elasticsearch Kibana Starter Project

A starter project for bringing up local instances of Elasticsearch and Kibana.

## Bringing up Elasticsearch and Kibana instances:

```bash
docker-compose up -d
```

Access Elasticsearch:  
http://localhost:9200

Accessing Kibana:  
http://localhost:5601

**Note:** Instances might take a minute or so to fully be accessible.

## Viewing Logs

Elasticsearch:  
```bash
docker-compose logs -f elasticsearch
```

Kibana:  
```bash
docker-compose logs -f kibana
```

## Resources

[ElasticSearch Documentation](https://www.elastic.co/guide/en/elasticsearch/reference/7.0/index.html)

[Kibana Documentation](https://www.elastic.co/guide/en/kibana/7.0/index.html)
