# Copyright (c) Facebook, Inc. and its affiliates.
#
# This source code is licensed under the MIT license found in the
# LICENSE file in the root directory of this source tree.

TESTS_DIR = ../../..

INFER_OPTIONS = \
  --annotation-reachability-only --debug-exceptions \
  --project-root $(TESTS_DIR) --print-types

INFERPRINT_OPTIONS = --issues-tests

SOURCES = $(wildcard *.erl)

include $(TESTS_DIR)/erlc.make

infer-out/report.json: $(MAKEFILE_LIST)
