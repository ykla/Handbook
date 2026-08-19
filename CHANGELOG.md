# 编辑日志

- 2026.8.19 同步 freebsd-doc 上游至 <https://github.com/freebsd/freebsd-doc/commit/2d4e1e6814f734cfdc382704696710a638769d92>。本次同步涵盖以下 12 个上游 commit：
  - `2d4e1e68` mirrors: ftp1.az.FreeBSD.org does not support FTP
  - `dd511736` mirrors: list the community mirror in Azerbaijan
  - `ea7ac309` doc: Update source files (en .po), for translations
  - `b23c17d9` 14.5-R: Revert previous commit until the 14.5-R release
  - `ab0db63e` 14.5-R: Temporary version bump for 14.5-R
  - `a06d4089` handbook: bump for 15.1-R
  - `9d82c9fe` Register our official mirror in France
  - `ba221a23` Fix assorted typos and grammar
  - `61a4734e` doc: Update source files (en .po), for translations
  - `d0d8468a` handbook/multimedia: Improve wording in the mpv section
  - `bcd8df85` handbook/cutting-edge: Add an introduction
  - `239cdf46` press: Add Foundation blog posts for May-July 2026
  变更文件清单：
  - 新增 `di-27-zhang-freebsd-geng-xin-yu-sheng-ji/27.2.-jian-jie.md`（cutting-edge 新增 Introduction H2 节，倒序重命名原 27.2-27.9 → 27.3-27.10）
  - 修改 `di-27-zhang-freebsd-geng-xin-yu-sheng-ji/27.3.-geng-xin-freebsd.md`（27.3.3 升级小节措辞与上游对齐）
  - 修改 `gai-shu.md`（FreeBSD 15.0-RELEASE → 15.1-RELEASE，对应 `a06d4089`）
  - 修改 `fu-lu-a.-huo-qu-freebsd/a.1.-jing-xiang-zhan.md`（新增法国与 Azerbaijan 镜像站，对应 `9d82c9fe`、`dd511736`、`2d4e1e68`）
  - 修改 `di-9-zhang-duo-mei-ti/9.4.-shi-pin-bo-fang-qi.md`（mpv 配置说明与 TTRPG 自动应用条件，对应 `d0d8468a`）
  - 修改 `SUMMARY.md`、`mu-lu.md`（新增 27.2.简介 条目并重排后续章节编号）
  - 修复重命名引起的跨章节破损交叉引用：`di-17-zhang-jail/17.12.-geng-xin-jail.md`、`di-25-zhang-xu-ni-hua/25.7.-shi-yong-freebsd-shang-de-bhyve-xu-ni-ji.md`、`di-35-zhang-gao-ji-wang-luo/35.10.-shi-yong-pxe-jin-hang-wu-pan-cao-zuo.md`、`di-10-zhang-pei-zhi-freebsd-nei-he/10.6.-ru-guo-fa-sheng-le-yi-xie-cuo-wu.md`，以及 chapter 27 内部链接（27.6/27.7/27.8/27.9）
  校对范围：上述所有改动文件，三轮逐句校对 + 一轮复查，以 `en/` 对应 `.adoc` 英文原文为权威源核对版本号、镜像站点、mpv 配置说明、章节结构及交叉引用一致性。

- 2026.7.20 同步第 23 章 ZFS 至 <https://github.com/freebsd/freebsd-doc/commit/f8d86635bc2f2d2706a1f084c0bbc260468e489f>（H2 从 8 节扩展到 10 节，新增 ZFS 原生加密、引导环境等章节；重写 Tuning；删除 ZFS on i386；新增 RAID-Z 扩展、dRAID、特殊分配类、热备与 zfsd、TRIM、池检查点、块克隆、书签、快照持有、可恢复传输、纠错接收、项目配额、重写已有数据、NFSv4 ACL、ARC 大小与监控、同步写入 ZIL 与 SLOG、直接 I/O、recordsize 与 volblocksize、导入 GELI 加密池等小节）
- 2026.7.16 同步第 17 章 jail 至 <https://github.com/freebsd/freebsd-doc/commit/56ba04a704e911e7f8f87be271f31f1dedc8f793>（H2 从 9 节扩展到 16 节，新增 VNET jail、Linux jail、NAT 和端口转发、服务 jail、从 jail 内部管理、更多 jail 选项、jail 与 ZFS 等章节）
- 2026.6.29 同步最新
- 2026.6.2 第 32-34 章校对完成
- 2026.6.2 第 17-25 章校对完成
- 2026.5.26 进行更新
- 2025.12.1 仅更新 handbook/cutting-edge 到 <https://cgit.freebsd.org/doc/commit/?id=099e57c42a>
- 2025.8.15 同步至 <https://github.com/freebsd/freebsd-doc/commit/f6d5b57b005213d676aa958f48ea1315ee682aff>
- 2025.5.2 机器翻译至 <https://github.com/freebsd/freebsd-doc/commit/8f28a757b13aa8d1db6528453b4bd9df776271e9>
- 2024.9.28
  - 2.1 校对完成
  - 2.2 校对完成
  - 2.3 校对完成
  - 2.4 校对完成
  - 2.5 校对完成
  - 2.6 校对完成
  - 2.7 校对完成
  - 2.8 校对完成
  - 2.9 校对完成
  - 2.10 校对完成
- 2024.9.27
  - 1.1 校对完成
  - 1.2 校对完成
  - 1.3 校对完成
