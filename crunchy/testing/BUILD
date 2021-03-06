# Copyright 2017 The CrunchyCrypt Authors.
#
# Licensed under the Apache License, Version 2.0 (the "License");
# you may not use this file except in compliance with the License.
# You may obtain a copy of the License at
#
#      http://www.apache.org/licenses/LICENSE-2.0
#
# Unless required by applicable law or agreed to in writing, software
# distributed under the License is distributed on an "AS IS" BASIS,
# WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
# See the License for the specific language governing permissions and
# limitations under the License.

package(default_visibility = ["//visibility:private"])

licenses(["notice"])  # Apache 2.0

cc_test(
    name = "basic_aead_test",
    srcs = [
        "basic_aead_test.cc",
    ],
    deps = [
        "//crunchy:crunchy_crypter",
        "//crunchy/internal/common:status_matchers",
        "//crunchy/key_management:algorithms",
        "//crunchy/key_management:crunchy_factory",
        "//crunchy/key_management:keyset_handle",
        "//crunchy/key_management:keyset_manager",
        "//crunchy/util:status",
        "@com_google_absl//absl/memory",
        "@com_google_googletest//:gtest_main",
    ],
)

cc_test(
    name = "basic_hybrid_test",
    srcs = [
        "basic_hybrid_test.cc",
    ],
    deps = [
        "//crunchy:crunchy_hybrid_crypter",
        "//crunchy/internal/common:status_matchers",
        "//crunchy/key_management:algorithms",
        "//crunchy/key_management:crunchy_factory",
        "//crunchy/key_management:keyset_handle",
        "//crunchy/key_management:keyset_manager",
        "//crunchy/util:status",
        "@com_google_absl//absl/memory",
        "@com_google_googletest//:gtest_main",
    ],
)

cc_test(
    name = "basic_macing_test",
    srcs = [
        "basic_macing_test.cc",
    ],
    deps = [
        "//crunchy:crunchy_macer",
        "//crunchy/internal/common:status_matchers",
        "//crunchy/key_management:algorithms",
        "//crunchy/key_management:crunchy_factory",
        "//crunchy/key_management:keyset_handle",
        "//crunchy/key_management:keyset_manager",
        "//crunchy/util:status",
        "@com_google_absl//absl/memory",
        "@com_google_googletest//:gtest_main",
    ],
)

cc_test(
    name = "basic_signing_test",
    srcs = [
        "basic_signing_test.cc",
    ],
    deps = [
        "//crunchy:crunchy_signer",
        "//crunchy/internal/common:status_matchers",
        "//crunchy/key_management:algorithms",
        "//crunchy/key_management:crunchy_factory",
        "//crunchy/key_management:keyset_handle",
        "//crunchy/key_management:keyset_manager",
        "//crunchy/util:status",
        "@com_google_absl//absl/memory",
        "@com_google_googletest//:gtest_main",
    ],
)
