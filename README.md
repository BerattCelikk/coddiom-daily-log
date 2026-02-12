# 🚀 Coddiom Daily Engineering Log

---

## 🛠️ Understanding Memory Leaks in Web Applications (12.02.2026)

Memory leaks occur when a web app retains references to unused objects, preventing garbage collection and increasing memory consumption.

```javascript
function createLeak() {
  let leakyArray = [];
  setInterval(() => {
    leakyArray.push(new Array(1000000)); // Allocating memory
  }, 1000);
}
```

**Tags:** memory, performance, web

---

