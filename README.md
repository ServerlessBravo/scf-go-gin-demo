# scf-go-gin-demo
gin demo for scf


## Build

```bash
go get -u github.com/gin-gonic/gin
go build

## create zip
zip -r webfunc_test.zip scf_bootstrap webfunc_test resources/*
```


## Deploy

deploy from zip:

```
函数名称	gin-webfunc-demo
函数类型	Web函数
运行环境	Go 1
···
