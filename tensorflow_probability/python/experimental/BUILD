# Copyright 2018 The TensorFlow Probability Authors.
#
# Licensed under the Apache License, Version 2.0 (the "License");
# you may not use this file except in compliance with the License.
# You may obtain a copy of the License at
#
#     http://www.apache.org/licenses/LICENSE-2.0
#
# Unless required by applicable law or agreed to in writing, software
# distributed under the License is distributed on an "AS IS" BASIS,
# WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
# See the License for the specific language governing permissions and
# limitations under the License.
# ============================================================================
# Description:
#   API-unstable code that is part of the TFP package.

package(
    default_visibility = [
        "//tensorflow_probability:__subpackages__",
    ],
)

licenses(["notice"])  # Apache 2.0

exports_files(["LICENSE"])

py_library(
    name = "experimental",
    srcs = ["__init__.py"],
    srcs_version = "PY2AND3",
    deps = [
        ":auto_batching",
        "//tensorflow_probability/python/experimental/mcmc",
        "//tensorflow_probability/python/internal/auto_batching",
    ],
)

# This module is a redirect to python/internal
py_library(
    name = "auto_batching",
    srcs = ["auto_batching.py"],
    srcs_version = "PY2AND3",
    deps = [
        "//tensorflow_probability/python/internal/auto_batching",
    ],
)