# Experimenting with Spin and Big Go

```
❯ spin build
Building component spin-biggo with `GOOS=wasip1 GOARCH=wasm go build -o main.wasm .`
# github.com/ydnar/wasi-http-go/internal/wasi/io/error
../../../../pkg/mod/github.com/ydnar/wasi-http-go@v0.0.0-20250324053847-ca78b3198aeb/internal/wasi/io/error/ioerror.wasm.go:13:6: go:wasmimport: unsupported parameter type *string
# github.com/ydnar/wasi-http-go/internal/wasi/io/poll
../../../../pkg/mod/github.com/ydnar/wasi-http-go@v0.0.0-20250324053847-ca78b3198aeb/internal/wasi/io/poll/poll.wasm.go:25:6: go:wasmimport: unsupported parameter type *cm.List[uint32]
Error: Build command for component spin-biggo failed with status Exited(1)
```
