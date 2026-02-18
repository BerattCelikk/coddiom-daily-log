# 🚀 Coddiom Daily Engineering Log

---

## 🛠️ Understanding Node.js Event Loop Phases (18.02.2026)

The Node.js event loop allows JavaScript to perform non-blocking I/O operations by offloading operations to the system kernel whenever possible. It has multiple phases, including timers, I/O callbacks, idle, poll, check, and close callbacks.

```javascript
setTimeout(() => {
  console.log('Timer executed');
}, 0);

console.log('Immediate log');
```

**Tags:** Node.js, Event Loop, Asynchronous

---

