# Description:
# JPEG test data packages.

load("//tensorflow:tensorflow.bzl", "filegroup")

package(
    licenses = ["notice"],  # Apache 2.0
)

filegroup(
    name = "testdata",
    srcs = glob(["*.jpg"]),
    visibility = [
        "//tensorflow/core:__pkg__",
        "//tensorflow/core/lib/jpeg:__pkg__",
    ],
)
