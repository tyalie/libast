# Copyright (c) 2023 Sophie Tyalie
# SPDX-License-Identifier: Apache-2.0

if(CONFIG_LIBAST)
  set(LIBAST_DIR ${ZEPHYR_CURRENT_MODULE_DIR})

  zephyr_library()
  zephyr_include_directories(${LIBAST_DIR})

  zephyr_library_sources(libast.c)
endif()
