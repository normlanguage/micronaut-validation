# Micronaut Validation sample

[English](README.md) | [简体中文](README.zh-CN.md)

[hello.norm](hello.norm) validates a controller argument with `@Validated` and `@Size(min: 3)`. From the repository root, run:

```sh
norm run samples/hello.norm
```

In another terminal, compare valid and invalid input:

```sh
curl -i 'http://127.0.0.1:18769/registration/name?name=Norm'
curl -i 'http://127.0.0.1:18769/registration/name?name=Al'
```

The first request returns HTTP 200 and `Accepted: Norm`; the second returns HTTP 400 with a size validation error. Stop the server with Ctrl+C.
