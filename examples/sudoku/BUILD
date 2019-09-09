


cc_binary(
    name = "sudoku_loadtest",
    srcs = [
        "loadtest.cc",
        "sudoku.cc",
    ],
    deps = [
        "//muduo/net:muduo_net",
        
    ],
    optimize = ["-std=c++11", "-g", "-O2", "-Wall", "-Wextra",],
)


cc_binary(
    name = "sudoku_client_pipeline",
    srcs = [
        "pipeline.cc",
        "sudoku.cc",
    ],
    deps = [
        "//muduo/net:muduo_net",
        
    ],
    optimize = ["-std=c++11", "-g", "-O2", "-Wall", "-Wextra",],
)


cc_binary(
    name = "sudoku_solver_basic",
    srcs = [
        "server_basic.cc",
        "sudoku.cc",
    ],
    deps = [
        "//muduo/net:muduo_net",
        
    ],
    optimize = ["-std=c++11", "-g", "-O2", "-Wall", "-Wextra",],
)


cc_binary(
    name = "sudoku_client_batch",
    srcs = [
        "batch.cc",
        "sudoku.cc",
    ],
    deps = [
        "//muduo/net:muduo_net",
        
    ],
    optimize = ["-std=c++11", "-g", "-O2", "-Wall", "-Wextra",],
)

cc_binary(
    name = "sudoku_solver_multiloop",
    srcs = [
        "server_multiloop.cc",
        "sudoku.cc",
    ],
    deps = [
        "//muduo/net:muduo_net",
        
    ],
    optimize = ["-std=c++11", "-g", "-O2", "-Wall", "-Wextra",],
)


cc_binary(
    name = "sudoku_solver_threadpool",
    srcs = [
        "server_threadpool.cc",
        "sudoku.cc",
    ],
    deps = [
        "//muduo/net:muduo_net",
        
    ],
    optimize = ["-std=c++11", "-g", "-O2", "-Wall", "-Wextra",],
)


cc_binary(
    name = "sudoku_solver_prod",
    srcs = [
        "server_prod.cc",
        "sudoku.cc",
    ],
    deps = [
        "//muduo/net:muduo_inspect",
    ],
    optimize = ["-std=c++11", "-g", "-O2", "-Wall", "-Wextra",],
)


cc_binary(
    name = "sudoku_solver_hybrid",
    srcs = [
        "server_hybrid.cc",
        "sudoku.cc",
    ],
    deps = [
        "//muduo/net:muduo_inspect",
    ],
    optimize = ["-std=c++11", "-g", "-O2", "-Wall", "-Wextra",],
)