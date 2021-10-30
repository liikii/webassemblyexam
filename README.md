

```shell
go env GOROOT
cp /usr/local/go/misc/wasm/wasm_exec.js zitijiazai.js
go mod init example.com/greetings
go mod tidy
GOOS=js GOARCH=wasm go build -o main.wasm
```
