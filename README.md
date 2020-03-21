# grpc ruby demo

Walkthrough https://medium.com/@BranLiang/build-your-first-grpc-demo-with-ruby-12fba2c90a67

Generate grpc files
```
$ grpc_tools_ruby_protoc --ruby_out=lib --grpc_out=lib ./helloworld.proto
```

Start server
```
$ ruby ./server/server.rb
```
