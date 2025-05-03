load("@rules_proto_grpc//python:defs.bzl", "python_grpc_library")
load("@rules_proto//proto:defs.bzl", "proto_library")

proto_library(
    name = "hello_proto",
    srcs = ["hello.proto"],
    visibility = ["//visibility:public"],
)

python_grpc_library(
    name = "hello_python_grpc",
    protos = [":hello_proto"],
    visibility = ["//visibility:public"],
) 