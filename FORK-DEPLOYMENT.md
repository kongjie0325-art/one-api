# 🚀 Fork 部署说明

本 Fork 用于 [songquanpeng/one-api](https://github.com/songquanpeng/one-api) 的自定义部署。

## 部署环境

- **服务器**: Delux18 (x86_64 Docker)
- **端口**: 10200
- **用途**: LLM API 管理与分发（Hermes 的 LLM 路由层）
- **状态**: 运行中，通过 `new-api.zent.de5.net` 访问

## 同步

```bash
git remote add upstream https://github.com/songquanpeng/one-api.git
git fetch upstream
git checkout main
git merge upstream/main
```
