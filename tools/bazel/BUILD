load("@rules_cc//cc:defs.bzl", "cc_library")

cc_library(
    name = "catch2",
    # TODO(sokolik): this macros disables all exceptions, maybe we want to conpile slow, and get
    # more functionality
    # defines = ["CATCH_CONFIG_FAST_COMPILE"],
    visibility = ["//visibility:public"],
    deps = ["@catch2//:catch2_main"],
)
