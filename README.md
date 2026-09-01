OPPOk13t内核自动化编译脚本
（喵喵喵，源链接https://github.com/cctv18/oppo_oplus_realme_sm8750）
OPPO K13 Turbo(MT6899)机型内核编译脚本。

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
