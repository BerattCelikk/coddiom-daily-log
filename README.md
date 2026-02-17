# 🚀 Coddiom Daily Engineering Log

---

## 🛠️ Go Concurrency with Goroutines and Channels (17.02.2026)

Goroutines are lightweight threads managed by the Go runtime, enabling concurrent execution. Channels are used for communication between goroutines, making it easy to share data safely.

```go
package main
import "fmt"

func main() {
	ch := make(chan string)
	go func() { ch <- "Hello, Go!" }()
	fmt.Println(<-ch)
}
```

**Tags:** Go, Concurrency, Goroutines, Channels

---

