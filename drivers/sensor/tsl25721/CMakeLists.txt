# SPDX-License-Identifier: Apache-2.0

zephyr_library()

zephyr_library_sources(tsl25721.c)
zephyr_library_sources_ifdef(CONFIG_TSL25721_TRIGGER tsl25721_trigger.c)
