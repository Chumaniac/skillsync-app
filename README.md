# SkillSync 桌面版已合并

桌面应用、命令行工具和网页版现由 [SkillSync 主仓库](https://github.com/Chumaniac/skillsync) 统一维护。

- [在线试用](https://chumaniac.github.io/skillsync/)
- [下载中文桌面版](https://github.com/Chumaniac/skillsync/releases/tag/user-2026.11.11-zh)
- [查看构建说明](https://github.com/Chumaniac/skillsync/blob/main/docs/build.md)
- [提交问题](https://github.com/Chumaniac/skillsync/issues)

本仓库保留早期用户版提交、发行包及其 SHA-256 校验文件。

## 从历史快照构建

需要复现此仓库版本时，使用 Node.js 24，从当前仓库克隆并安装锁定依赖。核验默认为只读检查，真实运行未启用。

```sh
git clone https://github.com/Chumaniac/skillsync-app.git
cd skillsync-app
npm ci
npm run build
node dist/cli/index.js --help
```

[安装与构建](docs/build.md) · [离线使用说明](docs/user-guide.md)
