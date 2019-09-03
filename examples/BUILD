

cc_binary(
    name = "pingpong_bench",
    srcs = "pingpong/bench.cc",
    deps = "//muduo/net:muduo_net",
    optimize = ["-std=c++11", "-g", "-O2", "-Wall", "-Wextra",],
)

cc_binary(
    name = "pingpong_server",
    srcs = "pingpong/server.cc",
    deps = "//muduo/net:muduo_net",
    optimize = ["-std=c++11", "-g", "-O2", "-Wall", "-Wextra",],
)

cc_binary(
    name = "pingpong_client",
    srcs = "pingpong/client.cc",
    deps = "//muduo/net:muduo_net",
    optimize = ["-std=c++11", "-g", "-O2", "-Wall", "-Wextra",],
)



cc_binary(
    name = "echo",
    srcs = "simple/echo/*.cc",
    deps = "//muduo/net:muduo_net",
    optimize = ["-std=c++11", "-g", "-O2", "-Wall", "-Wextra",],
)