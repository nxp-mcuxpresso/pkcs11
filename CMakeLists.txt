#
# Copyright 2024 NXP
#
# SPDX-License-Identifier: BSD-3-Clause
#

if (CONFIG_MCUX_COMPONENT_middleware.pkcs11)
    mcux_add_source(
        SOURCES README.md pkcs11t.h pkcs11f.h pkcs11.h
    )
    mcux_add_include(
        INCLUDES ./
    )
endif()
