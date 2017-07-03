# Description:
# TensorBoard plugin for tensors and tensor variance for an entire graph.

package(default_visibility = ["//tensorboard:internal"])

licenses(["notice"])  # Apache 2.0

exports_files(["LICENSE"])

py_library(
  name = "beholder_plugin",
  srcs = ["beholder_plugin.py"],
  srcs_version = "PY2AND3",
  deps = [
    "//tensorboard/backend:http_util",
    "//tensorboard/plugins:base_plugin",
  ],
)

py_library(
  name = "beholder",
  srcs = ["beholder.py"],
  deps = [
    "//tensorboard/backend/event_processing:plugin_asset_util",
  ],
)