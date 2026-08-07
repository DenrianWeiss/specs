---
title: CoreMark 娱乐跑分
description: CPU
---

# CoreMark 娱乐跑分

本跑分页面只作为粗略比较目的，不代表实际性能。

## Results

| 处理器产品 | 设备 | 架构 | 架构版本 | 核心实现 | 频率 | 编译器 | CoreMark/MHz | CoreMark | 备注 |
|------------|------|------|----------|----------|------|--------|--------------|----------|------|
| 国芯 GX6605s | C-Sky 诛仙剑 | C-Sky ISA V1 | - | CK610m | 0.6 GHz | GCC 6.3.0 -O2 | 2.05 | 1231.14 | [c-sky](https://c-sky.github.io/docs/gx6605s.html) |
| 矽昌 SF19A2890 | GL.iNet SFT1200 | MIPS | MIPS32r2 | interAptiv | 1.0 GHz | GCC 12.4.0 -O2 | 1.89 | 1889.88 | [Siflower](http://www.siflower.com.cn/products/detail/2) [EN](http://www.siflower.com.cn/en/products/detail/7) |
| 中兴 ZX211221 | Redacted | AArch64 | ARMv9 | Neoverse N2 | 3.0GHz | GCC 15.2.0 -O2 | 10.44 | 31320 | [ZXIC](https://www.sanechips.com.cn/chinese/product/suanlichanpin/zhufeng/index.html) |
| 鼎道智芯 SS1101 | 联想 TB571FU | AArch64 | ARMv9 | Cortex X3 | 3.29GHz | Clang 15.0.7 -O2 | 10.05 | 33090 | [SS1101](/product/smartersilicon-ss1101) |
| Centriq 2452 | Centriq 2400 REP | AArch64 | ARMv8 | Falkor | 2.6 GHz | GCC 14.2.0 -O2 -march=native | 7.34 | 19074.26 | - |
| UltraSparc IIIi | Sun Ultra 45 | sparc64 | UltraSparc III | Jalapeno | 1.6 GHz | GCC7.3.0 -O3 -march=native | 3.13 | 5003.1 | - |
| 银河飞腾 FT-1000A | - | sparc64 | - | - | 1.0 GHz | GCC 13.3.0 -O3 -march=niagara | 1.2 | 1282.39 | GCC 4.4.3 -O2: 899 @ 1.0 GHz |
| 银河飞腾 FT-1000 | - | sparc64 | - | - | 0.8 GHz | GCC 14.2.0 -O3 -march=niagara2 | 1.36 | 1282.39 | On Linux 6.12 |
| 芯昇 XS7200 | 大华 IPC | C-Sky ISA V2 | - | CK810MF | 0.617 GHz | GCC 6.3.0 -O2 | 3.12 | 1928.39 | 摄像头：你肘不过我你信吗 |
