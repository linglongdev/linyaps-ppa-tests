# Linyaps PPA 测试

## 状态

### Latest

[![build result](https://build.deepin.com/projects/linglong:CI:latest/packages/linyaps/badge.svg?type=default)](https://build.deepin.com/package/show/linglong:CI:latest/linyaps)

[![Release Test](https://github.com/linglongdev/linyaps-ppa-tests/actions/workflows/latest-tests.yml/badge.svg)](https://github.com/linglongdev/linyaps-ppa-tests/actions/workflows/latest-tests.yml)

### Release

[![build result](https://build.deepin.com/projects/linglong:CI:release/packages/linyaps/badge.svg?type=default)](https://build.deepin.com/package/show/linglong:CI:release/linyaps)

[![Release Test](https://github.com/linglongdev/linyaps-ppa-tests/actions/workflows/release-tests.yml/badge.svg)](https://github.com/linglongdev/linyaps-ppa-tests/actions/workflows/release-tests.yml)

本项目使用 GitHub Actions 自动化测试 Linyaps PPA 仓库的可用性，确保 PPA 仓库能够正常安装和使用。

## 📋 项目简介

Linyaps PPA 测试项目旨在通过自动化测试验证 Linyaps PPA 仓库的稳定性和可用性。项目每天自动运行一次测试，检查 PPA 仓库的安装过程和基本功能是否正常工作。

### 测试目标

- ✅ 验证 PPA 仓库能够成功添加到系统
- ✅ 测试软件包的安装过程
- ✅ 验证安装后的基本功能可用性
- ✅ 检测 PPA 仓库的更新和同步状态

## 🚀 功能特性

- **自动化测试**：通过 GitHub Actions 实现完全自动化的测试流程
- **定时执行**：每天自动运行测试，持续监控 PPA 仓库状态
- **实时反馈**：测试结果实时推送到 GitHub Actions 页面
- **历史记录**：保留所有测试历史记录，便于追踪问题

## 📁 项目结构

```
linyaps-ppa-tests/
├── .github/
│   └── workflows/
│       └── release-tests.yml   # release测试工作流配置
└── README.md                   # 项目说明文档
```

## 🔧 GitHub Actions 工作流

### 工作流配置

项目使用 GitHub Actions 工作流进行自动化测试。

## 📊 测试流程

1. **环境准备**：初始化测试环境
2. **添加 PPA**：将 Linyaps PPA 仓库添加到系统
3. **更新软件源**：更新软件包列表
4. **安装测试**：安装指定的软件包
5. **功能验证**：验证安装后的基本功能
6. **结果报告**：生成测试报告并输出结果

## 📈 查看测试结果

### GitHub Actions 页面

所有测试结果都会显示在 GitHub Actions 页面：

1. 访问仓库的 **Actions** 标签页
2. 查看最新的工作流运行记录
3. 点击具体的运行记录查看详细日志

### 测试状态徽章

项目首页显示测试状态徽章，绿色表示测试通过，红色表示测试失败。

## 🔍 当前测试范围

目前项目包含以下测试内容：

- PPA 仓库安装测试
- 基本功能使用测试

更多测试用例将在后续版本中添加。
