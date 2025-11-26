# Troubleshooting

## Common Issues

### Cluster Yellow/Red
- Check disk space on nodes
- Review shard allocation
- Add nodes if needed

### Slow Queries
- Add date range filters
- Optimize index mappings
- Scale cluster horizontally

### Ingestion Lag
- Check Firehose buffer settings
- Review Lambda processing
- Increase shard count

### High Storage Costs
- Enable index lifecycle management
- Move old data to S3
- Implement log sampling
