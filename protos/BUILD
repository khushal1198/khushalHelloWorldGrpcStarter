load("@rules_proto//proto:defs.bzl", "proto_library", "py_proto_library", "py_grpc_library")

proto_library(
    name = "hello_proto",
    srcs = ["hello.proto"],
    visibility = ["//visibility:public"],
)

py_proto_library(
    name = "hello_python_proto",
    deps = [":hello_proto"],
    visibility = ["//visibility:public"],
)

py_grpc_library(
    name = "hello_grpc",
    deps = [":hello_proto"],
    visibility = ["//visibility:public"],
) 