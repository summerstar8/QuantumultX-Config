# Quantumult X 配置

个人使用的 Quantumult X 规则配置，已精简优化并融合银行 / 金融 / 加密货币精细分流。

## 在线下载地址
## https://github.com/summerstar8/QuantumultX-Config/blob/main/QuantumultX.conf

## 使用方法

1. 打开 Quantumult X → 右下角风车图标
2. 进入 **配置文件** → **下载**
3. 粘贴上方在线地址并下载
4. 下载完成后选择该配置文件并启用
5. 开启 **规则分流** 模式

## 主要特性

- 精简策略组，减少冗余
- 银行精细分流（美国 / 英国 / 香港 / 德国银行独立策略）
- 加密货币独立策略（优先低延迟节点）
- AI 服务（ChatGPT / Claude / Gemini / Grok 等）单独策略
- 常用媒体（YouTube、Netflix、Disney+、Spotify）分流
- 广告拦截
- 国内直连 + 最终走代理

## 节点添加方式

本配置文件 **不包含节点**，请通过以下方式自行添加：

- 复制 `ss://` / `trojan://` / `hysteria2://` 等链接后，在 Quantumult X 中「从剪贴板导入」
- 扫描机场二维码
- 在配置的 `[server_remote]` 部分添加订阅链接

## 策略说明

| 策略名称              | 用途说明                     |
|-----------------------|------------------------------|
| Group Select          | 手动选择节点                 |
| ALL-benchmark         | 全部节点自动测速             |
| 香港节点 / 美国节点等 | 按地区自动测速               |
| US BANK               | 美国银行专用                 |
| UK BANK               | 英国银行专用                 |
| HK BANK               | 香港银行专用                 |
| Germany BANK          | 德国银行专用                 |
| FINTECH / PAYMENT     | PayPal、Stripe、Wise 等      |
| Cryptocurrency        | 币安、欧易、Coinbase 等      |
| AGI                   | AI 相关服务                  |
| Telegram / YouTube 等 | 对应应用分流                 |

## 更新记录

- 2026-11-20：初始版本发布（精简 + 银行精细分流）

## 注意事项

1. 请根据自己的节点命名习惯，调整策略组中的 `server-tag-regex` 正则匹配规则。
2. 建议定期点击「更新」以获取最新规则。
3. 本配置仅供个人学习交流使用。
