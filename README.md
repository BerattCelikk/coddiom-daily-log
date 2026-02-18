# 🚀 Coddiom Daily Engineering Log

---

## 🛠️ Design Patterns: Singleton & Factory (19.02.2026)

Singleton restricts a class to a single instance. Factory provides a way to create objects without specifying the exact class.

```python
class Singleton:
    _instance = None

    def __new__(cls):
        if cls._instance is None:
            cls._instance = super().__new__(cls)
        return cls._instance

class Factory:
    @staticmethod
    def create_object(type):
        return Singleton() if type == 'singleton' else None
```

**Tags:** design patterns, singleton, factory

---

