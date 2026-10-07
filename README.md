# ZML 模组索引中心 (Mod Index)

ZML (ZMDModLoader / ZeroModLoader / ZMLModLoader) 的官方模组索引仓库。

## 功能介绍

本仓库维护一份全局模组索引清单 [`index.json`](index.json)，向 ZML 启动器中的「获取模组」功能提供可安装的在线模组列表。

每个模组在索引中记录以下元数据：
- 模组 ID 与显示名称
- 当前最新版本号及简介
- 作者信息及标签
- 图标链接 (`raw.githubusercontent.com`)
- 产物压缩包直链 (`asset_url`) 与 SHA-256 校验和
- 依赖项列表与主动态库文件名

## 发布与更新

使用 [模组模板 (Endfield-ModTemplate)](https://github.com/sakevel/Endfield-ModTemplate) 构建的模组在 GitHub 发布 Release 标签时，会自动向本仓库提交 Pull Request 更新索引清单。
