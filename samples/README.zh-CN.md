# Micronaut Validation 示例

[English](README.md) | [简体中文](README.zh-CN.md)

[hello.norm](hello.norm) 使用 `@Validated` 与 `@Size(min: 3)` 校验控制器参数。在仓库根目录运行：

```sh
norm run samples/hello.norm
```

在另一个终端比较有效与无效输入：

```sh
curl -i 'http://127.0.0.1:18769/registration/name?name=Norm'
curl -i 'http://127.0.0.1:18769/registration/name?name=Al'
```

第一个请求返回 HTTP 200 与 `Accepted: Norm`；第二个返回 HTTP 400 和长度校验错误。按 Ctrl+C 停止服务。
