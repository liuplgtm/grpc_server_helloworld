# grpc_server_helloworld
helloworld grpc server 

first,
```
$ protoc -I helloworld/ helloworld/helloworld.proto --go_out=plugins=grpc:helloworld
```

terminal 1:
```
$ go run greeter_server/main.go
```

terminal 2:
```
$ go run greeter_client/main.go
```
