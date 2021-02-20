# Simple_redrict_go_server

## 简介

### 使用golang进行编写的服务器。功能：支持将长Url转换为短Url，且在请求短Url时，通过映射重定向到长Url。通过gob包使用本地存储，且在v2版本中通过rpc使得slave服务器缓解master的redirect请求压力。

## 运行与调试

### Windows

Shell：进入到目录使用命令go run ./ 

IDEA：例如goland，默认run模式为file，会报错，切换为package模式，即可

## Linux

Bash：进入目录后，使用命令go run *.go

