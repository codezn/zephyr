# SPDX-License-Identifier: Apache-2.0

zephyr_sources_ifdef(CONFIG_MCUBOOT_IMG_MANAGER mcuboot.c)
zephyr_sources_ifdef(CONFIG_MCUBOOT_SHELL mcuboot_shell.c)
