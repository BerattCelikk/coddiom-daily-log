# 🚀 Coddiom Daily Engineering Log

---

## 🛠️ Understanding Singleton & Factory Design Patterns (17.02.2026)

Singleton ensures a class has only one instance and provides a global point of access to it. Factory provides an interface for creating objects in a superclass but allows subclasses to alter the type of created objects.

```python
class Singleton:
    _instance = None

    def __new__(cls):
        if cls._instance is None:
            cls._instance = super(Singleton, cls).__new__(cls)
        return cls._instance
```

**Tags:** design patterns, software architecture

---

