load("//tools/buck/rules:buck_rule_macros.bzl", "dbx_apple_third_party_library")

dbx_apple_third_party_library(
    name = "PINCache",
    header_path_prefix = "PINCache",
    module_name = "PINCache",
    modular = True,
    exported_headers = glob(['Source/*.h']),
    srcs = glob(['Source/*.m']),
    frameworks = [ "Foundation", ],
    deps = [
      "//dbx/external/PINCache/PINCache/PINOperation:PINOperation"
    ]
)