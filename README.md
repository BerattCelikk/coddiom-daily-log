# 🚀 Coddiom Daily Engineering Log

---

## 🛠️ Understanding Singleton and Factory Design Patterns (14.02.2026)

Singleton ensures a class has only one instance, while Factory provides a way to create objects without specifying the exact class.

```python
class Singleton:
    _instance = None
    def __new__(cls):
        if not cls._instance:
            cls._instance = super(Singleton, cls).__new__(cls)
        return cls._instance
```

**Tags:** design patterns, singleton, factory

---

