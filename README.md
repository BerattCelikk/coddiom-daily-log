# 🚀 Coddiom Daily Engineering Log

---

## 🛠️ Understanding Memory Leaks in Web Applications (17.02.2026)

Memory leaks occur when web applications retain references to objects that are no longer needed, preventing garbage collection and leading to increased memory usage over time.

```javascript
function createLeak() {
  const leakyArray = [];
  setInterval(() => {
    leakyArray.push(new Array(1000000).fill('leak'));
  }, 1000);
}
```

**Tags:** memory-leak, web-apps, performance

---

