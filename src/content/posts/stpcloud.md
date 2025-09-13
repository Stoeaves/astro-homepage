---
title: StpCloud部署及使用
published: 2025-09-13
tags: [StpCloud, 使用教程]
category: StpCloud
image: ''
draft: false
pinned: false
---

:::note
StoneLeaves 私人云盘基于原创项目 StpCloud 搭建~
::github{repo=Stoeaves/StpCloud}
:::

**在线预览：[StpCloud](https://file.seave.top)**

:::tip[目录]
> [准备工作](#准备工作)
> [部署](#部署)
> [剩余工作](#剩余工作)
> [Worker 环境变量](#worker-环境变量)
> [Github Token 说明](#github-token-说明)
:::

## 目录：

- [准备工作](#准备工作)
- [部署](#部署)
- [剩余工作](#剩余工作)
- [Worker 环境变量](#worker-环境变量)
- [Github Token 说明](#github-token-说明)

#### 准备工作

- 一个 Github 账户
- 一个 Cloudflare 账户
- Github Personal Access Token (Classic)

#### 部署

- **Cloudflare Worker:**
- 前往[Cloudflare](https://dash.cloudflare.com)
- 创建一个 Worker
- 复制[\_worker.js](https://github.com/Stoeaves/StpCloud/blob/main/_worker.js)的内容
- 粘贴至创建的 Worker 当中并部署
- **Github:**
- Fork 此仓库
- 在你 Fork 的仓库里修改 **`vite.config.ts`** 中第 26 行的 **`__API_URL__`** 的链接改成你的 Worker 地址（可以自定义）
- 再次返回 Cloudflare Worker 当中创建一个 Worker
- 选择 **`导入储存库`** 并选择你 Fork 的仓库
- 无需任何操作直接点击部署等待成功即可

#### 剩余工作

- 在 Github 中创建一个仓库（可以是**私密仓库**）
- 为 Worker 配置环境变量

#### Worker 环境变量

| 变量名       | 是否必须 | 说明                         |
| :----------- | :------- | :--------------------------- |
| ADMIN_PASS   | 是       | 管理员密码                   |
| GITHUB_TOKEN | 是       | Github Personal access token |
| REPO_OWNER   | 是       | Github 账户名                |
| REPO_NAME    | 是       | 仓库名                       |
| REPO_BRANCH  | 是       | 仓库分支                     |

#### Github Token 说明：

- **需要的权限** ~~如果你相信我们你可以勾选所有权限~~ _当然我知道你不会这样做_
- 1._repo_ 所有权限
- 2._project_ 所有权限
- 3._codespace_ 所有权限

#### 更新日志：

`暂无`
