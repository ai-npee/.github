# 安全策略

## 报告漏洞

如果你在本组织的仓库中发现安全问题（例如脚本中的命令注入、路径穿越、密钥泄露），
请**不要**公开提交 Issue，改为通过以下方式私下联系维护者：

- 发送邮件至组织公开邮箱，标题注明「安全报告」
- 或通过 GitHub 的 [私密安全公告](https://docs.github.com/en/code-security/security-advisories)
  提交（仓库 → Security → Report a vulnerability）

## 我们关心的范围

- `scripts/`、`tools/` 下的 Python 脚本
- 构建脚本（PowerShell / Shell）
- GitHub Actions 工作流
- 任何可能导致用户本地文件被意外覆盖或上传的路径处理逻辑

## 不在此范围内的报告

- 由用户自行重建的教材内容（版权问题请走正常的侵权投诉流程）
- 依赖项自身的漏洞（请直接向上游报告，同时欢迎告知我们以便升级版本）

## 响应时间

我们会尽力在 **7 天内**确认收到报告，并在评估后同步修复计划。
