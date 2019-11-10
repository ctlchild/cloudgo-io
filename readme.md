## cloudgo-io

1. 支持静态文件服务
2. 支持简单 js 访问
3. 提交表单，并输出一个表格
4. 对 `/unknown` 给出开发中的提示，返回码 `5xx`

#### 使用方法

​	终端输入

```
go get -u github.com/urfave/negroni
go get -u github.com/gorilla/mux
go get -u github.com/unrolled/render
go get -u github.com/spf13/pflag
go run main.go
```

就可以安装依赖并运行`cloudgo-io`了

#### 运行效果

- 静态文件服务：

​		运行程序后在浏览器中输入`127.0.0.1:8080/static`

![](./image/捕获2.PNG)

![](./image/捕获.PNG)

- 简单js访问：

![](./image/捕获3.PNG)

- 提交表单，并输出一个表格

![](./image/捕获5.PNG)

![](./image/捕获4.PNG)

- 对 `/unknown` 给出开发中的提示，返回码 `5xx`

![](./image/捕获6.PNG)