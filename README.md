# 🚀 Coddiom Daily Engineering Log

---

## 🛠️ Understanding Node.js Event Loop Phases (15.02.2026)

The Node.js event loop allows for non-blocking I/O operations by managing multiple phases where different types of operations are processed.

```javascript
setTimeout(() => {
  console.log('Timeout');
}, 0);

Promise.resolve().then(() => {
  console.log('Promise');
});
```

**Tags:** Node.js, Event Loop, Asynchronous

---

