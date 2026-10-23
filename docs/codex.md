# Codex 怎么充值、开通？额度跟着什么走（2026）

> 返回 [ChatGPT 充值 / GPT代充指南](../README.md) · 最近核对：2026-10-23

## 没有单独的“Codex 会员”

很多人搜“Codex 充值”“Codex 代充”，实际要办的是 **ChatGPT 会员**。Codex 不单独售卖，用 ChatGPT 账号登录，额度跟着会员档位走：

- **Plus**：可以用 Codex 的网页版、CLI 和 IDE 插件，适合日常写代码。
- **Pro（100 / 200 / 500）**：功能和 Plus 基本一致，额度更高，适合长时间、多项目使用。

具体能用哪些模型、额度多少，以 [ChatGPT 官方定价页](https://chatgpt.com/pricing/) 和 Codex 里显示的为准。

## 三种容易混在一起的“Codex 充值”

| 你想要的 | 实际要办的 | 说明 |
|---|---|---|
| 能用 Codex | 开 ChatGPT Plus 或 Pro | 国内用支付宝、微信可以在 [CallAI小铺](https://shop.callai.one/) 正价代充，开通到自己的账号 |
| 会员额度用完了还想用 | 在官方设置里买 credits，或升级到 Pro | credits 和升档都以官方页面为准 |
| 在程序里调用模型 | OpenAI API 余额 | API 和 ChatGPT 会员是两套计费，开会员不会加 API 余额 |

## 开通后让 Codex 认到新档位

1. 先在 ChatGPT 网页的设置里确认套餐已经变成你买的档位；
2. 在 Codex（CLI、IDE 插件或 App）里**退出登录再重新登录**，让它刷新账号状态；
3. 查看 Codex 里的用量页面，确认额度按新档位显示。

还是显示旧档位的话，参考 [到账排查清单](after-payment.md)。

## 什么时候该从 Plus 升 Pro

- Codex 经常因为额度用完而中断，影响到要交付的工作；
- 同时在多个项目里长时间跑 Codex；
- 偶尔撞一次额度、或者只是网络慢，不用急着升档。

档位对比见 [套餐选择专题](choose-plan.md)。
