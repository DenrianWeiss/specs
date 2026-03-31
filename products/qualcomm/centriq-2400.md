---
name: Centriq 2400
categories: ["AArch64", "Qualcomm", "服务器"]
images: ["./centriq_2400.jpg", "./stardragon_4800.jpg"]
brand: Qualcomm
architecture: ARMv8
arch_version: v8.0
instructions: fp asimd evtstrm aes pmull sha1 sha2 crc32 cpuid asimdrdm
variants:
  - Centriq 2434
  - Centriq 2452
  - Centriq 2460
  - StarDragon 4800
cores:
  Centriq 2434: 40 cores (40x Qualcomm Falkor)
  Centriq 2452: 46 cores (46x Qualcomm Falkor)
  Centriq 2460: 48 cores (48x Qualcomm Falkor)
frequency:
  Centriq 2434: 2.3/2.5 GHz
  Centriq 2452: 2.2/2.6 GHz
  Centriq 2460: 2.2/2.6 GHz
l0_cache:
  24 KB per core
l1_cache:
  32 KB data + 64 KB instruction per core
l2_cache:
  12 MiB
l3_cache:
  1.25 MiB per core
memory_type: DDR4
launch_date: 2017
tdp:
  Centriq 2434: 110W
  Centriq 2452: 120W
  Centriq 2460: 120W
memory_channels: 6
pcie_version: "3.0"
pcie_lanes: 32
---

## 备注

华芯通昇龙 (StarDragon) 4800 系列为对应的 Centriq 处理器添加国密模块的版本，其参数与后两位相同的 Centriq 处理器基本相同

## 参考资料

- [Qualcomm Centriq Deck](https://www.qualcomm.com/content/dam/qcomm-martech/dm-assets/documents/qualcomm_centriq_2400_media_deck.pdf)