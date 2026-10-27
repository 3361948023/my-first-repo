# 我的学习路线与回家操作清单

> 由 DeepSeek Harness 助手整理（2026-10-27）。这份文件放在 GitHub 上，任何电脑都能获取：
> `git clone git@github.com:3361948023/my-first-repo.git`

---

## 一、三步台阶路线

### 台阶 1：日常用 Git/GitHub（已基本完成 ✅）

已经会：`clone` / `add` / `commit` / `push` / SSH 免密登录。

还需要补的高频命令：

| 命令 | 作用 |
|------|------|
| `git pull` | 拉取远程最新更新 |
| `git branch` | 查看/创建分支 |
| `git log` / `git status` | 看历史 / 看当前改动 |
| `.gitignore` 文件 | 忽略不想上传的文件 |

教程：廖雪峰 Git 教程 → https://liaoxuefeng.com （用到再查即可）

---

### 台阶 2：学编程（当前重点 🎯）

**语言路线：JavaScript → TypeScript → Node.js → 回来看 deepseek-harness**

原因：deepseek-harness 是 TypeScript 写的，而 TypeScript 是「加了类型的 JavaScript」，一条路直达，不用绕道。

学习顺序：

1. 基础语法：变量、类型、条件、循环、函数
2. 核心概念：数组、对象、作用域
3. 进阶：异步（async/await）、模块（import/export）
4. TypeScript：在 JS 基础上加类型
5. Node.js：让 JS 脱离浏览器跑脚本

学习资源（免费中文）：

| 用途 | 地址 |
|------|------|
| 主教程 | 现代 JavaScript 教程 → https://zh.javascript.info |
| 边学边练 | freeCodeCamp → https://www.freecodecamp.org |
| 查文档 | MDN → https://developer.mozilla.org |
| TypeScript | 官方手册 → https://www.typescriptlang.org/zh |

方法论：**编程是练出来的，不是看出来的。** 每学一个概念就写一个小程序，每天 30 分钟。

---

### 台阶 3：搞懂 AI 框架（长远目标 ⏳）

等做到这三件事，再回来看 deepseek-harness：

- [ ] 能读懂一个 TypeScript 项目
- [ ] 会用 Node.js 跑一个项目（`npm install` + 跑起来）
- [ ] 理解「模块 / 包 / 依赖」是什么

之后顺着 `docs/architecture.md` 往下读即可。

---

## 二、回家后要做的步骤（重要！）

### 1. 装 Git

- 下载：https://git-scm.com/downloads/win
- 一路 Next 装完。

### 2. 配 Git 身份

```bash
git config --global user.name "3361948023"
git config --global user.email "3361948023@qq.com"
```

> `user.name` 想用真名，把引号里的内容改成你的名字即可。

### 3. 装 Node.js（学 JS 必需）

- 下载：https://nodejs.org → 选 **LTS** 版本 → 一路 Next。

### 4. 生成 SSH 密钥（每台电脑都要有自己的）

```bash
ssh-keygen -t ed25519 -C "3361948023@qq.com"
```

一路回车（默认位置、可留空密码）。然后：

1. 打开 `C:\Users\你的用户名\.ssh\id_ed25519.pub`
2. 复制里面**一整行**内容
3. 打开 https://github.com/settings/keys → 点 **New SSH key**
4. Title 随便填，Key 里粘贴，点 **Add SSH key**

### 5. 把仓库下载到家里电脑

```bash
git clone git@github.com:3361948023/my-first-repo.git
```

---

## 三、我的 GitHub 信息

| 项 | 值 |
|----|----|
| 用户名 | `3361948023` |
| 邮箱 | `3361948023@qq.com` |
| 仓库 | https://github.com/3361948023/my-first-repo |
