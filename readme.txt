//https://segmentfault.com/a/1190000009277748

问题1 
protoc --gogo_out=. *.proto
protoc-gen-gogo: program not found or is not executable
Please specify a program using absolute path or make sure the program is available in your PATH system variable
--gogo_out: protoc-gen-gogo: Plugin failed with status code 1.

//https://github.com/golang/protobuf/issues/795
在将GOPATH和GOBIN添加到路径时，我的问题已解决
