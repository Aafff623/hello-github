# hello-github

<p>
  <a href="https://github.com/Aafff623/hello-github/blob/main/LICENSE"><img src="https://img.shields.io/github/license/Aafff623/hello-github?style=flat-square&color=blue" alt="License: MIT"></a>
  <a href="https://github.com/Aafff623/hello-github/graphs/contributors"><img src="https://img.shields.io/github/contributors/Aafff623/hello-github?style=flat-square&color=green" alt="Contributors"></a>
  <a href="https://github.com/Aafff623/hello-github/actions"><img src="https://img.shields.io/github/actions/workflow/status/Aafff623/hello-github/main.yml?style=flat-square" alt="Build Status"></a>
</p>

---

## 📖 目录

- [🙋‍♂️ 个人介绍](#-个人介绍)
- [📚 学习内容](#-学习内容)
- [🚀 快速开始](#-快速开始)
- [📁 目录结构](#-目录结构)
- [🛠️ 技术栈](#-技术栈)
- [📖 学习资源](#-学习资源)
- [🤝 贡献指南](#-贡献指南)
- [📄 许可证](#-许可证)

---

## 🙋‍♂️ 个人介绍

你好！我是 **Aafff623**，这是我的 GitHub 学习仓库 🎉

此前上学期的我对于github没有进行系统化的学习, 如今作为一个"入门新手"，这个仓库记录了我从零开始学习 Git 和 GitHub 的完整历程。从最基础的"什么是 Git"到后来折腾 GitHub Actions、Webhooks organization 等高级功能，每一步的成长都被我记录了下来并且作为Commit push上去。

如果你也是刚接触 GitHub 的新手，欢迎参考我的学习路径！(推荐皮皮虾的github课程) , 如果有任何问题，欢迎提 [Issues](https://github.com/Aafff623/hello-github/issues) 交流~

> 💡 **学习心得**: 真的不要只看教程，自己动手操作一遍印象会深很多！

---

## 📚 学习内容

这个仓库涵盖了我学习过的所有知识点：

| 主题 | 说明 |
|------|------|
| **Git 基础** | 仓库创建、提交历史、分支管理、合并冲突解决 |
| **GitHub 工作流** | Fork、Pull Request、代码审查流程 |
| **GitHub Desktop** | 图形化界面操作，方便新手上手 |
| **IDEA Git 集成** | 在 IDE 中直接使用 Git |
| **VS Code + GitLens** | 编辑器内置 Git 功能 |
| **Git 命令行** | 深入理解底层命令 |
| **Git LFS** | 大文件存储优化 |
| **GitHub Actions** | CI/CD 自动化构建与部署 |
| **GitHub Packages** | 包管理功能 |
| **GitHub Pages** | 静态网站部署 |
| **Webhooks & REST API** | 自动化集成外部服务 |
| **仓库高级管理** | 组织创建、安全设置 |

---

## 🚀 核心学习知识点

```bash
# 克隆仓库到本地
git clone https://github.com/Aafff623/hello-github.git
cd hello-github

# 查看仓库状态
git status

# 查看提交历史（图表形式）
git log --oneline --graph --all

# 创建特性分支
git checkout -b feature/your-feature-name

# 添加并提交更改
git add .
git commit -m "描述你的更改内容"

# 推送到远程分支
git push origin feature/your-feature-name
```

---

## 📁 目录结构

```
hello-github/
├── .github/                  # GitHub 自动化配置
│   ├── workflows/            # CI/CD 工作流示例
│   └── dependabot.yml        # 依赖自动更新配置
├── docs/                     # 学习资料
│   ├── note/                 # 个人整理的笔记
│   └── shirp_github_note/    # 课程配套 PDF (38篇)
├── src/                      # 练习代码
│   └── test/                 # 测试脚本
├── main.py                   # Python 入口文件
├── demo6.py                  # 示例代码
├── test_demo.py              # 测试用例
├── color.txt                 # 小工具
├── requirements.txt          # Python 依赖
├── package.json              # Node.js 配置
├── CLAUDE.md                 # Claude Code 配置
├── CONTRIBUTING.md           # 贡献指南
├── LICENSE                   # MIT 许可证
└── README.md                 # 项目说明
```

---

## 🛠️ 技术栈

学习过程中使用到的工具：

- **版本控制**: Git, GitHub
- **客户端**: GitHub Desktop, IDEA, VS Code
- **编程语言**: Python, JavaScript
- **自动化**: GitHub Actions, Webhooks
- **部署**: GitHub Pages, Docker

---

## 📖 学习资源

### 官方文档
- [GitHub 官方文档](https://docs.github.com/zh) - 最权威的参考
- [Pro Git 中文版](https://git-scm.com/book/zh/v2) - 免费的 Git 书籍
- [GitHub Skills](https://skills.github.com) - 交互式入门教程

### 我的学习笔记
仓库中整理了 **38篇** 配套学习笔记 PDF，其中两篇 /note 下的是自己手敲的, /docs 下的是通过百度的ai总结视频 -> pdf的, 基本涵盖了从基础到进阶的完整内容。

### 学习建议（踩坑总结）
1. 🌱 新手推荐从 GitHub Desktop 入手，图形界面更直观
2. 📖 一定要看官方文档，比第三方教程更准确
3. 🔄 多动手练习，命令行才是真正的大招
4. 🐛 遇到冲突别慌，这是最好的学习机会
5. 🤖 试试用 Actions 自动化一些简单任务

---

## 🤝 贡献指南

欢迎任何形式的贡献！即使是纠正一个错别字也很有帮助~

1. Fork 本仓库
2. 创建你的特性分支：`git checkout -b feature/amazing-feature`
3. 提交你的更改：`git commit -m '添加一些出色的特性'`
4. 推送到分支：`git push origin feature/amazing-feature`
5. 打开 Pull Request

详细贡献指南请查看 [CONTRIBUTING.md](CONTRIBUTING.md)。

### PR 标题格式

使用约定式提交格式：
- `feat:` - 新功能
- `fix:` - 修复 bug
- `docs:` - 文档更新
- `refactor:` - 代码重构
- `perf:` - 性能优化
- `test:` - 测试相关
- `chore:` - 日常维护

---

## 📄 许可证

本项目采用 MIT 许可证 - 详见 [LICENSE](LICENSE) 文件。

```
MIT License

Copyright (c) 2026-present, Aafff623

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```

---

## 🏃‍♂️ 继续学习

学无止境！如果你对这个仓库感兴趣，欢迎 Star ⭐ 或 Follow 我的 GitHub！

> 🚀 学习 GitHub 的路上，我们一起进步！

---

<p align="center">
  <sub>✨ 记录一个普通学生的 GitHub 学习之旅</sub>
</p>