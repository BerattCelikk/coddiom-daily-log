# 🚀 Coddiom Daily Engineering Log

---

## 🛠️ Database Sharding vs Partitioning (18.02.2026)

Sharding distributes data across multiple databases, while partitioning divides data within a single database. Sharding improves scalability, while partitioning enhances performance by reducing the size of datasets.

```python
def shard_data(data, shards):
    return [data[i::shards] for i in range(shards)]
```

**Tags:** database, scalability, performance, sharding, partitioning

---

