load("//tools:defs.bzl", "go_library")

package(licenses = ["notice"])

go_library(
    name = "fifo",
    srcs = [
        "endpoint.go",
        "packet_buffer_queue.go",
    ],
    visibility = ["//visibility:public"],
    deps = [
        "//pkg/sleep",
        "//pkg/sync",
        "//pkg/tcpip",
        "//pkg/tcpip/header",
        "//pkg/tcpip/stack",
    ],
)
