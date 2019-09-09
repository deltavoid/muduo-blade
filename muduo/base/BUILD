

cc_library(
    name = "muduo_base",
    srcs = [
        "AsyncLogging.cc",
        "Condition.cc",
        "CountDownLatch.cc",
        "CurrentThread.cc",
        "Date.cc",
        "Exception.cc",
        "FileUtil.cc",
        "LogFile.cc",
        "LogStream.cc",
        "Logging.cc",
        "ProcessInfo.cc",
        "Thread.cc",
        "ThreadPool.cc",
        "TimeZone.cc",
        "Timestamp.cc",
    ],
    deps = [
        "#pthread",
        "#rt",
    ],
    optimize = ["-std=c++11", "-g", "-O2", "-Wall", "-Wextra",],
)