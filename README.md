# wildfire_rt1050_semc

[不同硬件的 Debug配置表格]
wildfire EVB         (Debug_wildFire_qspi)
K2500 UI board       (Debug_k2500UI_hyper)
NXP imxrt1052 EVB    (Debug_nxpEvb_hyper)


[通过semc_sdram.c中的CONFIG_SDRAM_TEST_3MB 切换两种测试方式]
#define	CONFIG_SDRAM_TEST_3MB 1                 测试SDRAM的 3MB 空间
#define	CONFIG_SDRAM_TEST_3MB 0                 测试SDRAM的 16KB 空间
