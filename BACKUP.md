# Loon 迁移到个人备份

备份日期：2026-09-15。来源：[MaYIHEI/paperclip](https://github.com/MaYIHEI/paperclip)，main 提交 `77e0d57c54ba6dfeb26ed9b625133cf4a211c9b8`。

已备份该提交的全部 115 个文件，保留目录结构、许可证和作者信息。此仓库保存当前文件快照，不含上游完整 Git 历史、Issues 或 Releases 附件。本次改动是下载链接及文档导航，不更改签到逻辑、存储键或账号数据。不自动同步上游。

## 已在 Loon 使用的脚本

先备份 Loon 当前配置，然后将其中以下地址前缀替换：

旧：`https://raw.githubusercontent.com/MaYIHEI/paperclip/`

新：`https://raw.githubusercontent.com/Timkeltis/scrips/`

后面的 `main/…` 或 `refs/heads/main/…` 和文件路径保持原样。定时签到、Cookie 获取、插件订阅及 BoxJS 订阅都要检查。不要同时启用新旧两份定时任务。保留原参数和执行时间；通常无需重新获取 Cookie，因为存储键没有改变。

新 BoxJS 地址：

`https://raw.githubusercontent.com/Timkeltis/scrips/main/paperclip.boxjs.json`

Loon Cookie 插件：

`https://raw.githubusercontent.com/Timkeltis/scrips/main/loon/paperclip-cookie/paperclip-cookie.lpx`

IP 检测插件：

`https://raw.githubusercontent.com/Timkeltis/scrips/main/loon/ipquality/ipquality.lpx`

修改后更新/下载脚本和插件，再手动运行你使用的任务验证。仓库备份不会自动修改手机上现有的 Loon 配置。

## 依赖与验证范围

原仓库自己的 Raw 下载链接、相关文档链接已迁移。作者署名和来源链接保留。

部分图标仍引用 `MaYIHEI/pin`，不属于本次 paperclip 备份；图标失效通常影响显示。业务服务、其他外部服务和上游署名链接仍保留，接口变更或凭据失效仍可能影响运行。没有执行签到请求，也没有上传个人 Cookie、token 或 Loon 私有配置。

`BACKUP-MANIFEST.json` 记录每个原文件与备份文件的 SHA-256，可核对快照内容。原 LICENSE 和脚本内版权声明完整保留。
