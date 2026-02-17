# 🚀 Coddiom Daily Engineering Log

---

## 🛠️ gRPC vs REST vs GraphQL (17.02.2026)

A comparison of gRPC, REST, and GraphQL highlighting their use cases, performance, and flexibility.

```python
import grpc

# gRPC client example
with grpc.insecure_channel('localhost:50051') as channel:
    stub = MyServiceStub(channel)
    response = stub.MyMethod(MyRequest())
```

**Tags:** gRPC, REST, GraphQL, API

---

