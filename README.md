

## Simple Chat application written in Go and gorilla WebSocket

#### Requirements
:warning: 

Go installed 

### Prepare development environment

```bash
go mod download
# buid the source code with Make command
make build_all
```
Or you can with go command
```bash 
go build -o dist/server cmd/web/*.go
```

### Start working with the script 

Create a new topic 
```bash
./dist/server 

# Then you should see the message
2022/11/14 18:57:37 Starting channel listener
```
