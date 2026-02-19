# 🚀 Coddiom Daily Engineering Log

---

## 🛠️ Understanding Memory Leaks in Web Apps (19.02.2026)

Memory leaks occur when a web application fails to release memory that is no longer needed, leading to increased resource consumption and potential crashes.

```javascript
const leakedArray = [];
function createLeak() {
  leakedArray.push(new Array(1000000).fill('leak'));
}
setInterval(createLeak, 1000);
```

**Tags:** memory management, web development, performance

---

