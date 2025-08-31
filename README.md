# deepseek_api_call

<!-- 徽章 -->
[![License: GPL v3](https://img.shields.io/badge/License-GPLv3-blue.svg)](https://www.gnu.org/licenses/gpl-3.0)
![Build Status](https://img.shields.io/badge/Build-Passing-brightgreen)
<!-- 项目简介 -->
一个简单的命令行工具，调用 DeepSeek API 实现 AI 聊天对话，支持多模型选择与流式输出。


<!-- 详细描述 -->
本项目通过 Python 脚本与 DeepSeek API 交互，支持自定义模型、系统角色和流式输出，适合快速集成 AI 聊天能力。无需复杂配置，开箱即用。

## ✨ 主要特性

*   支持 DeepSeek 多模型（普通/思考模式）
*   支持流式与非流式输出
*   可自定义系统角色
*   命令行交互体验友好

## 目录

- [安装](#-安装)
- [快速上手](#-快速上手)
- [贡献指南](#-贡献指南)
- [许可证](#-许可证)

## 🚀 安装

**先决条件**

确保你已经安装了以下环境：
*   Python 3.13 

**安装步骤**

1.  克隆本仓库
    ```bash
    git clone https://github.com/Adrian-Eve/deepseek_api_call.git
    ```
2.  进入项目目录
    ```bash
    cd deepseek_api_call
    ```
3. 在项目目录中创建 .env 文件并在其中添加以下以下内容以配置 API 密钥
   ```bash
   export DEEPSEEK_API_KEY="<YOUR_API_KEY>"
   ```

## 💡 快速上手

运行主程序，按提示选择模型、输出方式和系统角色，即可开始对话：

```bash
uv run main.py # 这会自动安装所需依赖
````

## 🤝 贡献指南
我们欢迎所有类型的贡献！如果你希望为这个项目做出贡献，请阅读我们的 CONTRIBUTING.md 文件，其中包含了我们的行为准则和提交代码的流程。


## 📄 许可证
本项目使用 GPL3 许可证。有关详细信息，请参阅 LICENSE 文件。

## 🙏 致谢
感谢 DeepSeek 提供的 API 服务。
感谢所有贡献者。

由 Adrian-Eve 创建
