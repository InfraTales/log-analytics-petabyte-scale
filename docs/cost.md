# Cost Analysis (₹)

Cost estimates for **Petabyte Log Analytics** in **Indian Rupees (₹)**.

## Production Environment

| Service | Monthly Cost (₹) | Notes |
|---------|------------------|-------|
| **OpenSearch** | ₹150,000–300,000 | Multi-node cluster |
| **S3 Data Lake** | ₹40,000–80,000 | Long-term storage |
| **Kinesis Firehose** | ₹20,000–40,000 | Log ingestion |
| **Glue ETL** | ₹15,000–30,000 | Data transformation |
| **Athena** | ₹10,000–25,000 | Ad-hoc queries |
| **Total** | **₹235,000–475,000** | ~$2,940–5,940/month |

## Storage Tiers

| Tier | Cost per TB/month (₹) | Retention |
|------|----------------------|-----------|
| Hot (OpenSearch) | ₹8,000 | 7-30 days |
| Warm (S3 Standard) | ₹2,000 | 30-90 days |
| Cold (S3 Glacier) | ₹400 | 1+ years |

## Cost Optimization

- **Tiered storage** – Move old logs to cheaper tiers
- **Index lifecycle** – Auto-delete old indices
- **Sampling** – Sample verbose logs
- **Reserved instances** – For OpenSearch nodes
