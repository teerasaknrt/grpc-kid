# grpc-kid
Basic gRPC


protoc -I. -I $GOPATH/src/github.com/grpc-ecosystem/grpc-gateway/third_party/googleapis/ --go_out=plugins=grpc:. --grpc-gateway_out=logtostderr=true:. reminder.proto

protoc  --go_out=pluging=grpc:. service.proto