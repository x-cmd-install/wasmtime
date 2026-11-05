# wasmtime

[English version](./README.md)

A lightweight WebAssembly runtime that is fast, secure, and standards-compliant

[![x-cmd/install — wasmtime Code Quality Monitoring Repo Card](https://x-cmd.com/repo-card/wasmtime.svg?lang=zh)](https://x-cmd.com/install/wasmtime)

## 安装

```sh
x install wasmtime
```

## 代码洞察

合计: **791,083** 行代码（覆盖前 5 种语言、共 **5545** 个文件）。

| 语言 | 代码 | 注释 | 空行 | 文件数 |
|------|-----:|-----:|-----:|------:|
| Rust | 633,292 | 38,332 | 68,263 | 2132 |
| WebAssembly | 122,881 | 141,405 | 11,724 | 3180 |
| Toml | 10,899 | 417 | 1,887 | 108 |
| CppHeader | 6,076 | 2,481 | 1,697 | 64 |
| Cpp | 5,217 | 309 | 978 | 61 |

## OpenSSF Scorecard 评分

总评分: **6.4 / 10**

评分最低的几项:

- **Token-Permissions** (0/10) — detected GitHub workflow tokens with excessive permissions
- **CII-Best-Practices** (0/10) — no effort to earn an OpenSSF best practices badge detected
- **Pinned-Dependencies** (3/10) — dependency not pinned by hash detected -- score normalized to 3

## 源代码

- **上游仓库**: <https://github.com/bytecodealliance/wasmtime>
- **官网**: <https://wasmtime.dev/>
- **许可证**: Apache-2.0

## 发布

- **最新版本**: `dev` (2026-10-29)
- **最近提交**: 2026-11-05
- **Release 含资产**: 39 个

## 流行度

- **Star**: 18,822 · **Fork**: 1,914 · **开放 issue**: 3,791 · **贡献者**: 782

## 累计统计

- **发布数**: 233 · **已合并 PR**: 10349 · **开放 PR**: 115 · **已关闭 issue**: 3036 · **开放 issue**: 755 · **提交数**: 17667

## 最近活动

| 时间窗口 | 起始 | 发布 | 已合并 PR | 开放 PR | 已关闭 issue | 开放 issue | 提交 |
|---|---|---:|---:|---:|---:|---:|---:|
| 30d | 2026-10-06 | 12 | 361 | 45 | 74 | 34 | 336 |
| last60d | 2026-09-06 | 22 | 576 | 53 | 133 | 47 | 516 |
| 90d | 2026-08-07 | 29 | 714 | 54 | 166 | 59 | 644 |
| last180d | 2026-05-09 | 50 | 1245 | 63 | 289 | 94 | 1146 |
| 360d | 2025-11-10 | 84 | 2191 | 77 | 513 | 153 | 2027 |
| last720d | 2024-11-15 | 99 | 3937 | 87 | 948 | 265 | 3600 |

## Release 资产

| 资产 | 大小 | 目标平台 |
|------|-----:|----------|
| [isle-veri-cache.tar.gz](https://github.com/bytecodealliance/wasmtime/releases/download/v50.0.1/isle-veri-cache.tar.gz) | 3.9 MiB | `native/unknown` |
| [wasi_snapshot_preview1.command.wasm](https://github.com/bytecodealliance/wasmtime/releases/download/v50.0.1/wasi_snapshot_preview1.command.wasm) | 50.6 KiB | `other` |
| [wasi_snapshot_preview1.proxy.wasm](https://github.com/bytecodealliance/wasmtime/releases/download/v50.0.1/wasi_snapshot_preview1.proxy.wasm) | 16.7 KiB | `other` |
| [wasi_snapshot_preview1.reactor.wasm](https://github.com/bytecodealliance/wasmtime/releases/download/v50.0.1/wasi_snapshot_preview1.reactor.wasm) | 50.4 KiB | `other` |
| [wasmtime-platform.h](https://github.com/bytecodealliance/wasmtime/releases/download/v50.0.1/wasmtime-platform.h) | 11.8 KiB | `other` |
| [wasmtime-v50.0.1-aarch64-android-c-api.tar.xz](https://github.com/bytecodealliance/wasmtime/releases/download/v50.0.1/wasmtime-v50.0.1-aarch64-android-c-api.tar.xz) | 12.6 MiB | `other` |
| [wasmtime-v50.0.1-aarch64-android.tar.xz](https://github.com/bytecodealliance/wasmtime/releases/download/v50.0.1/wasmtime-v50.0.1-aarch64-android.tar.xz) | 10.0 MiB | `other` |
| [wasmtime-v50.0.1-aarch64-linux-c-api.tar.xz](https://github.com/bytecodealliance/wasmtime/releases/download/v50.0.1/wasmtime-v50.0.1-aarch64-linux-c-api.tar.xz) | 12.9 MiB | `native/linux/arm64` |
| [wasmtime-v50.0.1-aarch64-linux.tar.xz](https://github.com/bytecodealliance/wasmtime/releases/download/v50.0.1/wasmtime-v50.0.1-aarch64-linux.tar.xz) | 10.3 MiB | `native/linux/arm64` |
| [wasmtime-v50.0.1-aarch64-macos-c-api.tar.xz](https://github.com/bytecodealliance/wasmtime/releases/download/v50.0.1/wasmtime-v50.0.1-aarch64-macos-c-api.tar.xz) | 12.1 MiB | `native/darwin/arm64` |
| [wasmtime-v50.0.1-aarch64-macos.tar.xz](https://github.com/bytecodealliance/wasmtime/releases/download/v50.0.1/wasmtime-v50.0.1-aarch64-macos.tar.xz) | 9.0 MiB | `native/darwin/arm64` |
| [wasmtime-v50.0.1-aarch64-musl-c-api.tar.xz](https://github.com/bytecodealliance/wasmtime/releases/download/v50.0.1/wasmtime-v50.0.1-aarch64-musl-c-api.tar.xz) | 13.1 MiB | `other` |
| [wasmtime-v50.0.1-aarch64-musl.tar.xz](https://github.com/bytecodealliance/wasmtime/releases/download/v50.0.1/wasmtime-v50.0.1-aarch64-musl.tar.xz) | 10.4 MiB | `other` |
| [wasmtime-v50.0.1-aarch64-windows-c-api.zip](https://github.com/bytecodealliance/wasmtime/releases/download/v50.0.1/wasmtime-v50.0.1-aarch64-windows-c-api.zip) | 24.8 MiB | `native/win/arm64` |
| [wasmtime-v50.0.1-aarch64-windows.zip](https://github.com/bytecodealliance/wasmtime/releases/download/v50.0.1/wasmtime-v50.0.1-aarch64-windows.zip) | 11.5 MiB | `native/win/arm64` |
| [wasmtime-v50.0.1-armv7-linux-c-api.tar.xz](https://github.com/bytecodealliance/wasmtime/releases/download/v50.0.1/wasmtime-v50.0.1-armv7-linux-c-api.tar.xz) | 13.2 MiB | `native/linux/arm` |
| [wasmtime-v50.0.1-armv7-linux.tar.xz](https://github.com/bytecodealliance/wasmtime/releases/download/v50.0.1/wasmtime-v50.0.1-armv7-linux.tar.xz) | 10.4 MiB | `native/linux/arm` |
| [wasmtime-v50.0.1-i686-linux-c-api.tar.xz](https://github.com/bytecodealliance/wasmtime/releases/download/v50.0.1/wasmtime-v50.0.1-i686-linux-c-api.tar.xz) | 15.0 MiB | `native/linux/x86` |
| [wasmtime-v50.0.1-i686-linux.tar.xz](https://github.com/bytecodealliance/wasmtime/releases/download/v50.0.1/wasmtime-v50.0.1-i686-linux.tar.xz) | 11.5 MiB | `native/linux/x86` |
| [wasmtime-v50.0.1-i686-windows-c-api.zip](https://github.com/bytecodealliance/wasmtime/releases/download/v50.0.1/wasmtime-v50.0.1-i686-windows-c-api.zip) | 23.9 MiB | `native/win/x64` |
| [wasmtime-v50.0.1-i686-windows.zip](https://github.com/bytecodealliance/wasmtime/releases/download/v50.0.1/wasmtime-v50.0.1-i686-windows.zip) | 11.7 MiB | `native/win/x64` |
| [wasmtime-v50.0.1-riscv64gc-linux-c-api.tar.xz](https://github.com/bytecodealliance/wasmtime/releases/download/v50.0.1/wasmtime-v50.0.1-riscv64gc-linux-c-api.tar.xz) | 16.2 MiB | `native/linux/riscv64` |
| [wasmtime-v50.0.1-riscv64gc-linux.tar.xz](https://github.com/bytecodealliance/wasmtime/releases/download/v50.0.1/wasmtime-v50.0.1-riscv64gc-linux.tar.xz) | 11.7 MiB | `native/linux/riscv64` |
| [wasmtime-v50.0.1-s390x-linux-c-api.tar.xz](https://github.com/bytecodealliance/wasmtime/releases/download/v50.0.1/wasmtime-v50.0.1-s390x-linux-c-api.tar.xz) | 13.5 MiB | `other` |
| [wasmtime-v50.0.1-s390x-linux.tar.xz](https://github.com/bytecodealliance/wasmtime/releases/download/v50.0.1/wasmtime-v50.0.1-s390x-linux.tar.xz) | 10.6 MiB | `other` |
| [wasmtime-v50.0.1-src.tar.gz](https://github.com/bytecodealliance/wasmtime/releases/download/v50.0.1/wasmtime-v50.0.1-src.tar.gz) | 192.4 MiB | `native/unknown` |
| [wasmtime-v50.0.1-x86_64-android-c-api.tar.xz](https://github.com/bytecodealliance/wasmtime/releases/download/v50.0.1/wasmtime-v50.0.1-x86_64-android-c-api.tar.xz) | 14.7 MiB | `other` |
| [wasmtime-v50.0.1-x86_64-android.tar.xz](https://github.com/bytecodealliance/wasmtime/releases/download/v50.0.1/wasmtime-v50.0.1-x86_64-android.tar.xz) | 10.9 MiB | `other` |
| [wasmtime-v50.0.1-x86_64-linux-c-api.tar.xz](https://github.com/bytecodealliance/wasmtime/releases/download/v50.0.1/wasmtime-v50.0.1-x86_64-linux-c-api.tar.xz) | 15.0 MiB | `native/linux/x64` |
| [wasmtime-v50.0.1-x86_64-linux.tar.xz](https://github.com/bytecodealliance/wasmtime/releases/download/v50.0.1/wasmtime-v50.0.1-x86_64-linux.tar.xz) | 11.0 MiB | `native/linux/x64` |
| [wasmtime-v50.0.1-x86_64-macos-c-api.tar.xz](https://github.com/bytecodealliance/wasmtime/releases/download/v50.0.1/wasmtime-v50.0.1-x86_64-macos-c-api.tar.xz) | 13.8 MiB | `native/darwin/x64` |
| [wasmtime-v50.0.1-x86_64-macos.tar.xz](https://github.com/bytecodealliance/wasmtime/releases/download/v50.0.1/wasmtime-v50.0.1-x86_64-macos.tar.xz) | 10.2 MiB | `native/darwin/x64` |
| [wasmtime-v50.0.1-x86_64-mingw-c-api.zip](https://github.com/bytecodealliance/wasmtime/releases/download/v50.0.1/wasmtime-v50.0.1-x86_64-mingw-c-api.zip) | 29.0 MiB | `other` |
| [wasmtime-v50.0.1-x86_64-mingw.zip](https://github.com/bytecodealliance/wasmtime/releases/download/v50.0.1/wasmtime-v50.0.1-x86_64-mingw.zip) | 20.4 MiB | `other` |
| [wasmtime-v50.0.1-x86_64-musl-c-api.tar.xz](https://github.com/bytecodealliance/wasmtime/releases/download/v50.0.1/wasmtime-v50.0.1-x86_64-musl-c-api.tar.xz) | 15.1 MiB | `other` |
| [wasmtime-v50.0.1-x86_64-musl.tar.xz](https://github.com/bytecodealliance/wasmtime/releases/download/v50.0.1/wasmtime-v50.0.1-x86_64-musl.tar.xz) | 11.5 MiB | `other` |
| [wasmtime-v50.0.1-x86_64-windows-c-api.zip](https://github.com/bytecodealliance/wasmtime/releases/download/v50.0.1/wasmtime-v50.0.1-x86_64-windows-c-api.zip) | 27.0 MiB | `native/win/x64` |
| [wasmtime-v50.0.1-x86_64-windows.msi](https://github.com/bytecodealliance/wasmtime/releases/download/v50.0.1/wasmtime-v50.0.1-x86_64-windows.msi) | 12.2 MiB | `native/win/x64` |
| [wasmtime-v50.0.1-x86_64-windows.zip](https://github.com/bytecodealliance/wasmtime/releases/download/v50.0.1/wasmtime-v50.0.1-x86_64-windows.zip) | 12.5 MiB | `native/win/x64` |

## 发行版状态

在 [repology.org](https://repology.org/project/wasmtime) 上共有 **51** 个发行版报告此项目。**14** 个 ✅ 已是最新上游版本，**25** 个 ⚠️ 使用旧版本。

| 发行版 | 版本 | 状态 |
|--------|------|------|
| Arch | `50.0.1` | ✅ latest |
| Homebrew | `50.0.1` | ✅ latest |
| Nix unstable | `50.0.0` | ⚠️ outdated |
| Void | `0.25.0` | ⚠️ outdated |
| Alpine edge | `47.0.3` | ⚠️ outdated |

## 改进这些数据

wasmtime 的安装元数据由 [x-cmd/install](https://github.com/x-cmd/install) 索引维护——这是一份由 x-cmd 在安装时读取的精选 YAML 包列表。如果 `wasmtime` 缺失、过期，或安装行为有问题，欢迎在该 repo 提 issue 或 PR：

- **提交 issue**: <https://github.com/x-cmd/install/issues/new>
- **编辑包条目**: <https://github.com/x-cmd/install/edit/main/wasmtime.yml>（或索引实际使用的路径）

本页面的数据（card / loc / scorecard / release）由 [x-cmd-install-action](https://github.com/x-cmd-install/x-cmd-install-action) 自动采集，每日重新生成。**安装行为**（版本选择、平台差异、依赖处理）的改进应提交到上游索引。

_数据快照: `data/card/261105.yml` · 2026-11-05T06:44:33Z._
