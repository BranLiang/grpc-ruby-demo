# grpc ruby demo

Generate grpc files
```
$ grpc_tools_ruby_protoc --ruby_out=lib --grpc_out=lib ./helloworld.proto
```

Start server
```
$ ruby ./server/server.rb
```