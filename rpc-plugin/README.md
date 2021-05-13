go build -o protoc-gen-go-netrpc
mv protoc-gen-go-netrpc /Users/firaga/go/bin/
protoc --go-netrpc_out=plugins=netrpc:. hello.proto