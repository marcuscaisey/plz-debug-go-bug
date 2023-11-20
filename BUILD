subinclude("///go//build_defs:go")

export_file(
    name = "gomod",
    src = "go.mod",
    visibility = ["PUBLIC"],
)

go_library(
    name = "tools",
    srcs = ["tools.go"],
    labels = ["manual"],
    deps = ["///third_party/go/github.com_go-delve_delve//cmd/dlv"],
)
