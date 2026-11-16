# Celeste-Mod

Celeste / Everest Mod 发布仓库。可直接安装的 ZIP 放在 GitHub Releases 中，每个版本独立保存，方便更新与回退。

## 下载 ModSettingsBrowser（Mod 设置管理器）

- [下载最新安装包](https://github.com/special-account/Celeste-Mod/releases/latest/download/ModSettingsBrowser.zip)
- [查看所有版本与更新说明](https://github.com/special-account/Celeste-Mod/releases)
- [0.2.10 版本](https://github.com/special-account/Celeste-Mod/releases/tag/modsettingsbrowser-v0.2.10)

为「Mod 选项」增加两栏浏览、按 Mod 分组的搜索结果、收藏和自定义排序，复用原 Mod 的设置控件及回调。

## 安装与更新

1. 需要 Celeste 和 Everest 1.6662.0 或更新版本。
2. 下载 Release 的 **ModSettingsBrowser.zip** 附件，放入游戏的 `Mods` 文件夹，保留 ZIP，不必解压。
3. 重启游戏，从主菜单或关卡暂停菜单进入「Mod 选项」。使用 CeleMod / Olympus 时，在当前配置组合中启用 `ModSettingsBrowser`。
4. 更新前关闭游戏，用新 ZIP 替换旧包，避免同时保留多个版本。

GitHub 自动生成的 Source code 压缩包仅包含仓库内容；安装请使用上述 Mod ZIP 附件。完整使用说明和许可证包含在安装包内。

## 版本发布约定

- 标签格式：`modsettingsbrowser-v<版本号>`，与包内 `everest.yaml` 的版本保持一致。
- 每个新版本创建一个 Release，保留旧版附件与更新记录，便于回退。
- 安装包名称保持 `ModSettingsBrowser.zip`；将最新稳定版标记为 Latest，上方「下载最新安装包」链接即可继续使用。
- 发布说明包含本版变化、Everest 依赖、安装方式和已知限制。
- 若将来在本仓库发布其他 Mod，请为每个 Mod 增加独立下载入口；仓库级 Latest 链接需随之调整。
