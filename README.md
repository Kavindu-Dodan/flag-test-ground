## Flagd GRPC sync provider

A simple POC for [flagd](https://github.com/open-feature/flagd) which provides GRPC flag configuration syncs.

Utilize buf definitions at https://buf.build/kavindudodan/flagd 

### How to run ?

```shell
go run main.go
```

Then start your GRPC sync enabled flagd.

Related to - https://github.com/open-feature/flagd/pull/297