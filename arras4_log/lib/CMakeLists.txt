# Copyright 2023 DreamWorks Animation LLC and Intel Corporation
# SPDX-License-Identifier: Apache-2.0

add_subdirectory(arras4_athena)
add_subdirectory(arras4_log)

# Breakpad dependency
if(Breakpad_FOUND)
    add_subdirectory(arras4_crash)
endif()
