# hello-github

这是 `aa6297` 的第一个 GitHub 仓库，用于验证本机与 GitHub 的连接链路（SSH 认证 + 推送）。

## 环境信息

- 建立日期：2026-11-07
- 本机系统：Windows
- Git 版本：2.55.0.windows.3
- 认证方式：SSH（ED25519 密钥，已加入 GitHub 账号）

## 这个仓库能做什么

| 目的 | 说明 |
|---|---|
| 验证连通性 | 代码能从本机推到 GitHub，说明链路完整 |
| 练习基本功 | 后续所有 `commit` / `push` / `pull` 都可以在这里试 |
| 当草稿本 | 想试什么命令，先在这里跑，不怕搞坏 |

## 常用命令速查

```bash
git status                  # 看当前改动
git add .                   # 把所有改动加入暂存区
git commit -m "说明"        # 提交一次快照
git push                    # 推送到 GitHub
git pull                    # 拉取远端更新
git log --oneline           # 看提交历史
```

## 下一步

- [ ] 完成第一次 `push`
- [ ] 在网页上看到这个 README 渲染效果
- [ ] 试着改一行字，再推一次，观察提交历史
