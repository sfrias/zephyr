# Copyright (c) 2017, NXP
#
# SPDX-License-Identifier: Apache-2.0
#
set(BOARD lpcxpresso54114_m0)

include($ENV{ZEPHYR_BASE}/cmake/app/boilerplate.cmake NO_POLICY_SCOPE)
project(NONE)

target_sources(app PRIVATE src/main_remote.c)
