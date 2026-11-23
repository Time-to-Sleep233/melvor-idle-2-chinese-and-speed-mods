# Melvor Idle 2：简体中文汉化与加速 MOD

两个可独立安装的非官方 MOD，面向 Windows 上的 Steam 抢先体验版（EA，App ID `3218350`），不适用于独立 Demo。

## 下载

- [下载简体中文汉化 v0.6.14](https://github.com/Time-to-Sleep233/melvor-idle-2-chinese-and-speed-mods/releases/download/release-2026-11-23-zhcn-v0.6.14/MelvorIdle2-zhCN-v0.6.14-footer-countdown.zip)
- [下载加速 MOD v0.3.11 · EA 离线调试版](https://github.com/Time-to-Sleep233/melvor-idle-2-chinese-and-speed-mods/releases/download/release-2026-11-19-r1/MelvorIdle2-Speed-v0.3.11-r1.zip)

也可分别查看[汉化发布页](https://github.com/Time-to-Sleep233/melvor-idle-2-chinese-and-speed-mods/releases/tag/release-2026-11-23-zhcn-v0.6.14)与[加速 MOD 发布页](https://github.com/Time-to-Sleep233/melvor-idle-2-chinese-and-speed-mods/releases/tag/release-2026-11-19-r1)。请下载 MOD 安装包，不要下载 GitHub 自动生成的源码压缩包。

## 版本与用途

| MOD | 版本 | 功能 |
| --- | --- | --- |
| 简体中文汉化 | v0.6.14 | 在已有中文词条的基础上补译、校对。本版修复底部升级倒计时更新时引起的界面伸缩，保留中文时间单位。 |
| 加速 MOD（EA 离线调试版） | v0.3.11 | F8 切换游戏倍率，F9 显示或隐藏加速控件；只有在支持的离线补丁生效时，F7 才能切换离线跟随。 |

适配版本为 `0.11.6-alpha.1`（Steam Build `26724394`）。EA 更新可能改变兼容性，不要在版本不匹配时强行安装离线差分。

## 安装与卸载

1. 退出游戏，先备份自己的存档。两个 MOD 可以只选其中一个。
2. 把每个 ZIP **完整解压到不同的文件夹**，不要在压缩包预览中运行脚本。
3. 在要安装的 MOD 文件夹内运行 `一键安装.bat`，再运行同一文件夹中的 `安装检查.bat`。要同时使用两个 MOD，就分别执行一次。
4. 从 Steam 启动游戏。要移除某个 MOD，退出游戏后运行**该 MOD** 文件夹里的 `一键卸载.bat`。

离线加速使用针对特定版本的 DLL 差分，只有原始文件精确匹配时才应应用；请保留安装器建立的原版备份。首次试用离线跟随时，先进入角色、选择倍率、正常退出，再回到同一角色。安装和回滚、部分游戏场景已做隔离测试；没有用真实角色存档验证离线收益。

## 遇到问题

如果安装检查报告游戏版本或 DLL 不匹配，请停止安装，不要手动覆盖 DLL。遇到误译、加速异常或安装失败，可以[提交问题反馈](https://github.com/Time-to-Sleep233/melvor-idle-2-chinese-and-speed-mods/issues/new?template=mod-report.yml)。请写明游戏和 MOD 的版本、问题发生在哪一步；公开反馈不需要附存档或账号信息。

本项目与 Games by Malcs、Jagex 或 Steam 无隶属关系。游戏及第三方素材的权利归各自权利人；本仓库未为这些内容授予开源许可。
