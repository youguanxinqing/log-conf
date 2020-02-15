# 说明

[logrus](https://github.com/sirupsen/logrus) 的配置包。

# 用法

可以选择在 main.go 文件中导入此包:
```go
import (
    _ "github.com/youguanxinqing/log-conf"
)
```

或者将代码拷贝下来，放在本地项目中，进行扩展或裁剪。

当你希望日志信息写入磁盘时，你可以：
```go
if f, err := isDisk(true, "test.log"); err == nil { 
    ...
}
```

## 参考
- 感谢 [How to configure a golang logger (logrus) for production](https://medium.com/@trierra.dev/how-to-configure-a-golang-logger-logrus-for-production-6389e5042367)
