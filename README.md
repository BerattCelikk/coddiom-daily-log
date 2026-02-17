# 🚀 Coddiom Daily Engineering Log

---

## 🛠️ Understanding PostgreSQL Index Types (17.02.2026)

PostgreSQL offers various index types to optimize query performance. B-Tree is the default and efficient for equality and range queries. GIN is great for full-text search and array operations, while GiST supports complex data types like geometries.

```sql
CREATE INDEX idx_example ON table_name USING GIN (column_name);
```

**Tags:** PostgreSQL, Database, Indexing

---

