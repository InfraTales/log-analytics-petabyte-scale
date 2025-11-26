# Runbook

## Deployment

```bash
npm install && cdk deploy --context environment=prod
```

## Adding Log Source

1. Create Kinesis Firehose delivery stream
2. Configure log format/parsing
3. Set destination (OpenSearch/S3)
4. Enable source logging

## Index Management

```bash
# Create index template
curl -X PUT "https://opensearch:443/_index_template/logs"

# Check cluster health
curl "https://opensearch:443/_cluster/health"
```

## Maintenance

- Monitor cluster health daily
- Review index sizes weekly
- Run index lifecycle policies
- Archive old indices monthly
