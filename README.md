# 第一个仓库测试 ✅

这是我的第一个 GitHub 仓库，用来确认「创建 → 提交 → 推送 → 在线查看」这条链路是通的。

- 创建人：（填你的名字或 GitHub 用户名）
- 创建日期：2026-11-12
- 用途：GitHub 入门自测，不是正式项目

## 这次测试要验证的 4 件事

| # | 验证项 | 怎么看结果 |
| --- | --- | --- |
| 1 | 仓库建好了 | 浏览器能打开 `github.com/你的用户名/仓库名` |
| 2 | 文件传上去了 | 仓库首页能看到这份 README，并且自动渲染成排版 |
| 3 | 提交记录有了 | 点右上角 `Commits`，能看到至少一条提交 |
| 4 | 能在线改 | 点右上角铅笔图标，改一行字，提交后内容立刻更新 |

## 常用命令备忘

```bash
git init                          # 把当前文件夹变成 git 仓库
git add .                         # 把所有改动加入暂存区
git commit -m "第一次提交"         # 生成一条提交记录
git branch -M main                # 把主分支命名为 main
git remote add origin 仓库地址     # 关联到 GitHub 上的仓库
git push -u origin main           # 推送到 GitHub
```

## 备注

- 推送时如果要求输密码，用 GitHub 的 Personal Access Token，不是登录密码。
