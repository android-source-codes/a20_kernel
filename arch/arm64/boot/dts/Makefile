# SPDX-License-Identifier: GPL-2.0
dtb-y += exynos/dtbo/exynos7885.dtb
dtbo-y += exynos/dtbo/exynos7884B-a20_cis_ser_00.dtbo
dtbo-y += exynos/dtbo/exynos7884B-a20_cis_ser_01.dtbo
dtbo-y += exynos/dtbo/exynos7884B-a20_can_single_03.dtbo
dtbo-y += exynos/dtbo/exynos7884B-a20_can_single_05.dtbo

targets += dtbs
DTB_LIST  := $(dtb-y) $(dtbo-y)
always    := $(DTB_LIST)

dtbs: $(addprefix $(obj)/, $(DTB_LIST))

clean-files := *.dtb*
