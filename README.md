# Local-Gemma-Deploy 🚀

![GitHub repo size](https://img.shields.io/github/repo-size/zcy2066087379/Local-Gemma-Deploy)
![GitHub stars](https://img.shields.io/github/stars/zcy2066087379/Local-Gemma-Deploy)
![GitHub license](https://img.shields.io/github/license/zcy2066087379/Local-Gemma-Deploy)

一套专门为 **高性能笔记本 (R9 + RTX 5060)** 量身定制的本地 AI 大模型部署方案。
解决了 C 盘空间溢出、网络下载中断及 Docker 代理配置等硬核问题。

## 🛠 功能亮点
- **自动断点续传：** 彻底解决下载大模型时的 `unexpected EOF` 网络故障。
- **高性能适配：** 专门针对 8GB VRAM 显存的量化模型进行优化。
- **存储架构优化：** 强制将模型存入 D 盘，释放系统盘空间。
- **普适性：** **本指南及自动化脚本不仅适用于 Gemma 4。只需修改脚本中的模型 ID，即可一键部署 Llama 3.1、Qwen 2.5 等任何开源模型。**

## 📥 快速开始
1. 确保已安装 [Ollama](https://ollama.com)。
2. 配置环境变量 `OLLAMA_MODELS` 指向 D 盘。
3. 运行 `/scripts` 下的自动化部署脚本。

## 📚 详细图文手册
遇到报错？
👉 **[点击这里访问飞书保姆级图文教程](https://tcn4hqvdhgdg.feishu.cn/wiki/VatIwAwNxiAB6TkADZtcBSqwnlh)**

## 🤝 参与贡献
如果你在其他 GPU 配置下有更好的性能优化方案，欢迎提 [Pull Request](https://github.com/zcy2066087379/Local-Gemma-Deploy/pulls) 或提交 [Issue](https://github.com/zcy2066087379/Local-Gemma-Deploy/issues)。
