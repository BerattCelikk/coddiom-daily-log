# 🚀 Coddiom Daily Engineering Log

---

## 🛠️ Design Patterns: Singleton & Factory (17.02.2026)

Singleton ensures a class has only one instance and provides a global point of access. Factory pattern creates objects without specifying the exact class.

```python
class Singleton:
    _instance = None
    def __new__(cls):
        if not cls._instance:
            cls._instance = super(Singleton, cls).__new__(cls)
        return cls._instance

class Factory:
    @staticmethod
    def create_object(type):
        return Singleton() if type == 'singleton' else None
```

**Tags:** Design Patterns, Software Architecture

---

