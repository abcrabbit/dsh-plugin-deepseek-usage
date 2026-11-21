# 余额 / Token 用量

在左下角显示「余额/Token」入口，并在会话区查看 DeepSeek 账户全部历史用量、UncensoredLLM 中转余额与本机 Token 用量：余额、消费金额、Token 与调用次数，可按日期、API Key、模型筛选；两个账户余额约每 2 小时自动刷新。

Adds a Balance/Token entry at the sidebar foot and shows the DeepSeek account full usage history, the UncensoredLLM relay balance and its local token usage: balance, spend, tokens and request counts, filterable by date, API key and model; both provider balances refresh about every 2 hours.

## 安装

**方式一（推荐）**：在 DSH 插件的「发现」页添加索引源

```
https://raw.githubusercontent.com/abcrabbit/dsh-plugin-index/main/index.json
```

然后搜索并安装本插件。

**方式二（手动）**：下载本仓库，在 DSH「设置 → 插件 → 添加插件 → 本地目录」中选择本目录。

## 兼容性

- DSH 0.2.2 系列（在 `0.2.2-rc.5` 上验证）
- 许可证：MIT
## 注意事项

首次打开面板会请求 DeepSeek 账户余额；中转站余额在面板内配置。