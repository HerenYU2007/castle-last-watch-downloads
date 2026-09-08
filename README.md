# 最后一班岗 · Castle Last Watch

这是游戏客户端下载与更新仓库，不包含 Unity 工程源码或 Blender 源文件。

## 下载与启动

1. 在 [最新版本](https://github.com/HerenYU2007/castle-last-watch-downloads/releases/latest) 下载 **CastleLauncher.exe**，或者下载 **LastWatch-Launcher.zip** 并解压。
2. 打开启动器后自动检查版本并下载安装，完成后点击“开始游戏”。首次游戏包约 155 MiB，游戏文件约 270 MiB，更新时建议保留至少 1 GB 空间。
3. 启动器会在桌面创建 **Castle Last Watch** 快捷方式。以后通过它启动，有新版会自动更新，版本相同直接显示“开始游戏”。
4. 自动线路先尝试 GitHub，再尝试镜像；也可选择镜像并填写兼容 GitHub Releases 的 HTTPS 前缀（例如 `https://ghfast.top/`）。第三方镜像的可用性可能变化，可随时切回直连。

Windows 10/11 64 位。已有游戏可以离线启动。程序更新需要退出游戏；不需要每次重新安装启动器。启动器较大升级会提示重新下载启动器。

## 当前 Demo 内容

九波单人守城，第一／第三人称、剑盾／弩／魔法、重弩与投石机、吊桥、NPC 商店、城防升级和地下采石。

**联机目前完成 2–4 人 TCP 大厅、准备和房主开局流程。人物、敌军、城门、经济等共同战斗同步尚未完成；进入后的战斗是各自本地预览。**

## 更新方式

启动时仅比较版本号，不逐个扫描游戏文件；实际安装时校验带 RSA 签名的更新清单与 SHA-256 文件摘要，只下载发生变化的包，支持断点续传。下载到临时目录并校验后再替换；保留上一版供回退。游戏存档与 Unity 玩家设置不在替换目录内。

游戏目录：`%LOCALAPPDATA%\Programs\Castle Last Watch`。
启动器：`%LOCALAPPDATA%\Programs\Castle Last Watch Launcher`。
下载缓存：`%LOCALAPPDATA%\Castle Last Watch Updater`。

保留 [第三方素材署名](THIRD-PARTY-NOTICES.md)。下载客户端不代表获得自有代码或素材的再分发授权，第三方素材适用其原许可。
