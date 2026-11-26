# Mirror notice / 镜像说明

本仓库是为了保存已经消失的上游项目而建立的镜像。

## 代码

- 上游原仓库：`JMBQ/azurlane`（Azur Lane MOD MENU，C++），2026 年已被删除，原账号 `JMBQ` 也已注销。
- 本仓库代码取自现存 fork `arminkey04/azurlane-mod-menu`，保留完整 93 次提交历史与 `1.0` `2.0` `2.5` `2.6` `2.7` 五个标签。
- 另一份可用的 fork 备份：`Goeimei/azurlane`（92 次提交 + 1 次 fork 作者的 CI 提交）。

## 成品

- 来源：`azzzddddd/Azurlane-Build` 的 Release `3.4.0-APK`。
- 本仓库 Release `3.4.0-APK` 内含 B 站服 9.7.25 分卷：`bilibili-V.9.7.25.7z.001`（800 MB）与 `bilibili-V.9.7.25.7z.002`（637 MB）。
- 解压方式：两个分卷放同一目录，用 7-Zip 打开 `.001` 合并解压，不要单独处理 `.002`。

## 同步

`.github/workflows/mirror.yml` 支持手动触发（workflow_dispatch），参数为源码仓库、发布仓库、标签、资产通配符。重新运行会强制对齐上游代码并重新上传对应资产。