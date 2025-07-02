workspace(name = "ddprof")

# Example dependencies - absl and googletest for tests
load("@bazel_tools//tools/build_defs/repo:http.bzl", "http_archive")

http_archive(
    name = "com_google_absl",
    sha256 = "9db34dc7cd135e8af94bdcecbadc177a64e124593d5e6f27bb1e6930f33d35f9",
    strip_prefix = "abseil-cpp-20230125.0",
    url = "https://github.com/abseil/abseil-cpp/archive/refs/tags/20230125.0.tar.gz",
)

http_archive(
    name = "com_google_googletest",
    sha256 = "2e6fbeb96e5bc0cce2fc93c857a32d090d824197a9f7faa45d6387cf1ab85045",
    strip_prefix = "googletest-1.14.0",
    url = "https://github.com/google/googletest/archive/refs/tags/v1.14.0.tar.gz",
)
