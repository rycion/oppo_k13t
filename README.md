欧加真 SM8750/MT6991 系列通用6.6风驰移植内核自动化编译脚本

https://img.shields.io/github/stars/cctv18/oppo_oplus_realme_sm8750?style=flat&logo=github
https://img.shields.io/github/forks/cctv18/oppo_oplus_realme_sm8750?style=flat&logo=greasyfork&color=%2394E61A

OPPO/一加/真我 骁龙8 Elite(SM8750)/天玑9400+(MT6991) 机型通用内核编译脚本。

特性

· OKI/GKI 双编译模式
· 移植官方 f2fs 源码，GKI 刷入免清 data
· LLVM/Clang 18 编译，大幅缩短编译时间
· 内置 ccache-ECS 缓存，二次编译约 6 分钟
· 支持 ReSukiSU/SukiSU Ultra/KernelSU Next/原版 KernelSU
· 移植官方风驰 scx 调速器
· O2 优化、lz4/zstd 算法更新、BBR/Brutal 拥塞控制、ADIOS IO 调度器
· 支持 Mountify、Re:Kernel、防格基带保护等

快速开始

```bash
git clone https://github.com/cctv18/oppo_oplus_realme_sm8750.git
cd oppo_oplus_realme_sm8750
./build.sh
```

鸣谢

ReSukiSU · SukiSU Ultra · susfs4ksu · KernelSU-Next · KernelSU · Baseband-guard
