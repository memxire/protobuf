# Protos

Project to generate Go code from proto files.

## How to generate Go files

Generated files will be in `gen/go/`

The command described in `Taskfile.yaml`

You can also change proto conditions in `proto/sso/sso.proto`

Delete existing files `sso.pb.go` and `sso_grpc.pb.go` in `gen/go/`
then run in the project root

```bash
task generate
```
