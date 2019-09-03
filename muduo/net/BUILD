

cc_library(
    name = "muduo_net",
    srcs = [
        "Acceptor.cc",
        "Buffer.cc",
        "Channel.cc",
        "Connector.cc",
        "EventLoop.cc",
        "EventLoopThread.cc",
        "EventLoopThreadPool.cc",
        "InetAddress.cc",
        "Poller.cc",
        "Socket.cc",
        "SocketsOps.cc",
        "TcpClient.cc",
        "TcpConnection.cc",
        "TcpServer.cc",
        "Timer.cc",
        "TimerQueue.cc",
        "poller/DefaultPoller.cc",
        "poller/EPollPoller.cc",
        "poller/PollPoller.cc",
    ],
    deps = [
        "//muduo/base:muduo_base",
    ],
    optimize = ["-std=c++11", "-g", "-O2", "-Wall", "-Wextra",],
)



cc_library(
    name = "muduo_http",
    srcs = [
        "http/*.cc",
    ],
    deps = [
        ":muduo_net",
    ],
    optimize = ["-std=c++11", "-g", "-O2", "-Wall", "-Wextra",],
)



cc_library(
    name = "muduo_inspect",
    srcs = [
        "inspect/*.cc",
    ],
    deps = [
        ":muduo_net",
    ],
    optimize = ["-std=c++11", "-g", "-O2", "-Wall", "-Wextra",],
)



cc_binary(
    name = "inspector_test",
    srcs = "inspect/tests/Inspector_test.cc",
    deps = [
        ":muduo_inspect",
        ":muduo_http",
    ],
    optimize = ["-std=c++11", "-g", "-O2", "-Wall", "-Wextra",],
)