cc_library(
    name = "external-file-loader",
    srcs = glob([
        "src/**/*.cc",
    ]) + glob([
        "src/**/*.h",
    ]),
    hdrs =  glob(["include/**/*.h"]),
    includes = ["include"],
    visibility = ["//visibility:public"],
    deps = [
        "//libs/anno-api",
        "//libs/xml-operations",
        "//libs/python35:loader_interface",
        "//third_party:ksignals",
        "//third_party:spdlog",
        "//third_party:json",
        "@boringssl//:crypto",
        "@com_google_absl//absl/strings",
        "@com_github_facebook_zstd//:libzstd",
        "@meow_hook//:meow-hook",
        "@pugixml",
    ],
)
