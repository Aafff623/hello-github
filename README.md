# hello-github

<p>
  <a href="https://github.com/Aafff623/hello-github/blob/main/LICENSE"><img src="https://img.shields.io/github/license/Aafff623/hello-github?style=flat-square&color=blue" alt="License: MIT"></a>
  <a href="https://github.com/Aafff623/hello-github/graphs/contributors"><img src="https://img.shields.io/github/contributors/Aafff623/hello-github?style=flat-square&color=green" alt="Contributors"></a>
  <a href="https://github.com/Aafff623/hello-github/actions"><img src="https://img.shields.io/github/actions/workflow/status/Aafff623/hello-github/main.yml?style=flat-square" alt="Build Status"></a>
</p>

---

## 📖 目录

- [项目简介](#-项目简介)
- [学习内容](#-学习内容)
- [快速开始](#-快速开始)
- [目录结构](#-目录结构)
- [学习资源](#-学习资源)
- [贡献指南](#-贡献指南)
- [许可证](#-许可证)

---

## 🎯 项目简介

`hello-github` 是一个专注于 Git 和 GitHub 实践学习的开源仓库。本项目通过系统化的学习路径和实战示例，帮助开发者从基础到进阶掌握 Git 版本控制和 GitHub 协作流程。

无论你是编程新手想了解基础的分支管理，还是资深开发者希望优化 CI/CD 工作流，这里都能提供实用的参考和示例。

---

## 📚 学习内容

| 主题 | 说明 |
|------|------|
| **Git 基础** | 仓库结构、提交历史、分支管理、合并冲突 |
| **GitHub 工作流** | Fork、Pull Request、代码审查流程 |
| **GitHub Actions** | CI/CD 自动化构建与部署配置 |
| **GitHub Pages** | 静态网站部署与自定义域名 |
| **Webhooks & API** | 通过 REST API 集成外部服务 |
| **Git LFS** | 大文件存储与管理优化 |
| **安全功能** | 仓库保护与漏洞扫描设置 |
| **客户端工具** | Desktop、IDEA、VS Code 集成使用 |

---

## 🚀 快速开始

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
├── .claude/              # Claude Code AI 配置
│   ├── settings.json     # IDE 和工具配置文件
│   └── rules/            # 开发规则与指南
├── docs/                 # 文档与学习资料
│   └── shirp_github_note/ # PDF 学习笔记资料
├── src/                  # 源代码示例
│   └── test/             # 测试脚本与演示
├── .git/                 # Git 仓库数据
├── .gitattributes        # Git 属性配置
├── .gitignore            # 忽略文件配置
├── LICENSE               # MIT 许可证
├── CONTRIBUTING.md       # 贡献指南
└── README.md             # 项目说明文档
```

---

## 📚 学习资源

### 官方文档
- [GitHub 官方文档](https://docs.github.com/zh) - GitHub 功能完整参考
- [Pro Git 中文版](https://git-scm.com/book/zh/v2) - 免费的 Git 综合指南
- [GitHub 学习实验室](https://skills.github.com) - 交互式教程

### 工具与客户端
- [GitHub Desktop](https://desktop.github.com) - Git 和 GitHub 的图形界面工具
- [GitKraken](https://www.gitkraken.com) - 可视化 Git 客户端
- [VS Code GitLens](https://marketplace.visualstudio.com/items?itemName=gitkraken.gitlens) - VS Code 中增强的 Git 功能

### 学习建议
1. 先掌握 Git 基础概念（本地仓库、暂存区、远程仓库）
2. 熟悉分支管理与合并策略
3. 实践 Pull Request 工作流程
4. 配置 CI/CD 自动化工作流
5. 探索 GitHub 高级功能（Packages、Pages、Actions）

---

## 🤝 贡献指南

欢迎任何形式的贡献！请遵循以下流程：

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

---

## 📄 许可证

本项目采用 MIT 许可证 - 详见 [LICENSE](LICENSE) 文件。

```
MIT 许可证

Copyright (c) 2026-present, Aafff623

特此免费授予任何 获取本软件和相关文档文件（"软件"）的人处理软件的权限，
包括但不限于使用、复制、修改、合并、出版、分发、再许可和/或销售软件的副本，
并允许软件提供给其接受的人员，须符合以下条件：

上述版权声明和本许可声明应包含在软件的所有副本或重要部分中。

本软件按"原样"提供，无任何明示或暗示的保证，包括但不限于适销性、特定用途适用性和非侵权性的保证。
在任何情况下，作者或版权持有人均不对因软件或使用软件或其他交易中的软件而导致的任何索赔、损害或其他责任负责，无论是在合同、侵权或其他行为的基础上。
```

---

## 🌟 致谢

感谢所有为本项目做出贡献的开发者和学习者！

如有问题或建议，欢迎通过 [Issues](https://github.com/Aafff623/hello-github/issues) 联系我们。

---

<p align="center">
  <sub>✨ 为开发者社区打造的学习资源</sub>
</p>
