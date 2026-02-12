# 🚀 Coddiom Daily Engineering Log

---

## 🛠️ Design Patterns: Singleton & Factory (12.02.2026)

Singleton ensures a class has only one instance, while Factory provides a way to create objects without specifying the exact class.

```python
class Singleton:
    _instance = None

    def __new__(cls):
        if cls._instance is None:
            cls._instance = super().__new__(cls)
        return cls._instance
```

**Tags:** singleton, factory, design-patterns

---

