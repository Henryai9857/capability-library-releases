# 能力仓库 Mac

[下载 DMG 安装包](https://github.com/Henryai9857/capability-library-releases/releases/download/v0.18.1/CapabilityLibrary-0.18.1.dmg) · [所有版本](https://github.com/Henryai9857/capability-library-releases/releases/latest)

需要 Apple Silicon（M 系列芯片），macOS 14 或更新系统；暂不支持 Intel Mac。

## 安装与连接

1. 下载 Release 中的 `CapabilityLibrary-版本.dmg`，双击打开，将“能力仓库.app”拖到旁边的 `Applications`（应用程序）快捷方式。复制完成后推出安装磁盘，从“应用程序”打开。若旧版正在运行，请先退出。ZIP 保留用于自动更新或手动解压安装；不要下载 Source code。
2. 本软件为本机签名预览版，**未经过 Apple 公证**。首次打开如被 macOS 阻止，请确认来源后自行按系统“隐私与安全性”提示操作。企业受管 Mac 可能不允许运行。不要关闭系统安全保护。
3. 在飞书连接设置输入你自己的 App ID 和 App Secret；密钥仅保存在你的 Mac 钥匙串。你的飞书应用必须由台账／文档管理者授予读写权限。共享同一台账和文档即可协作。

当前面向既定团队台账及文档模板。应用凭据、真实卡片、文档、缓存和草稿均不包含在下载包中。

## 后续更新

菜单“能力仓库 → 检查更新…”；也支持自动检查。确认后下载、验签并安装重启。更新包通过 Sparkle EdDSA 签名校验，验签失败不会安装。首次下载的信任确认与后续更新验签是两件事。

配置和草稿保留在本机。更新后若 macOS 再次询问钥匙串访问，需要本人允许。

更新清单：https://henryai9857.github.io/capability-library-releases/appcast.xml

## 使用指南

首次打开 0.18.0 会显示五步引导，支持跳过。以后可从侧栏“使用指南”或“帮助 → 使用指南…”重新查看。
