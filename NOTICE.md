# Notices / 第三方声明

## DSH Superpowers Plugin

The integration code in this repository is licensed under the MIT License in
`LICENSE`.

本仓库的 DSH 集成代码依据根目录 `LICENSE` 中的 MIT License 发布。

## Runtime schema dependency / 运行时 Schema 依赖

The desktop configuration form uses `@deepseek-ai/schemastery` 3.19.0. Its
transitive runtime dependencies are `@deepseek-ai/cosmokit` 1.9.0 and
`@standard-schema/spec` 1.1.0. All three packages are MIT licensed and are
installed by the package manager rather than vendored into this repository.

桌面配置表单使用 `@deepseek-ai/schemastery` 3.19.0；其传递依赖为
`@deepseek-ai/cosmokit` 1.9.0 与 `@standard-schema/spec` 1.1.0。三者均采用
MIT License，由包管理器安装，并未复制进本仓库。

## Vendored Superpowers content / 随包分发的 Superpowers 内容

This distribution vendors the `skills/` directory from:

- Project: `obra/superpowers`
- Repository: https://github.com/obra/superpowers
- Release: `v7.0.2`
- Commit: `22f0b463e7a5e579904dd6211a520321035526f7`
- License: MIT, reproduced verbatim in `LICENSE.superpowers`

The vendored files are recorded with SHA-256 hashes in `upstream-lock.json`.
No upstream skill file is modified in this release; `allowedDifferences` is
empty.

本发行包内的 `skills/` 来自上述固定 Superpowers 版本，其 MIT 许可证原文保存在
`LICENSE.superpowers`。所有随包文件均由 `upstream-lock.json` 记录 SHA-256；本版本
没有修改任何上游 skill，差异白名单为空。
