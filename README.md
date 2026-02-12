# 🚀 Coddiom Daily Engineering Log

---

## 🛠️ PostgreSQL Advanced Indexing Techniques (12.02.2026)

Explore how advanced indexing strategies like partial indexes and expression indexes can optimize query performance in PostgreSQL.

```sql
CREATE INDEX idx_partial ON users (email) WHERE active = true;
CREATE INDEX idx_expression ON orders ((lower(product_name));
```

**Tags:** PostgreSQL, Indexing, Performance

---

