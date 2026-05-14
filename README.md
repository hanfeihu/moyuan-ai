# 墨元 AI / Moyuan AI

墨元 AI 是一个开源的 AI 生图商业化平台模板，面向中文用户、内容团队、电商商家和开发者，目标是快速搭建一个可运营的 AI 图片生成网站。

官网域名规划：<https://moyuanai.com>

## 项目定位

墨元 AI 不只是一个模型调用页面，而是一套围绕“生成可用图片”的完整产品骨架：

- 中文提示词优化
- 文生图、图生图、参考图生成
- 电商主图、小红书封面、海报、头像、产品场景图模板
- 用户系统与积分计费
- 支付宝支付接入
- 图片生成历史与案例广场
- 管理后台与运营数据
- 可扩展的模型供应商适配层

## 适合谁

- 想搭建 AI 生图网站的创业者
- 需要快速验证 AI 图片产品的团队
- 需要人民币支付、支付宝接入和中文工作流的开发者
- 想做私有化部署或企业内部图片生成工具的公司

## 仓库结构

```txt
moyuan-ai/
  apps/
    web/              # 前端网站
    api/              # 后端服务
  packages/
    ai-providers/     # OpenAI / 其他图像模型适配
    payments/         # 支付宝 / 后续微信支付适配
    shared/           # 共享类型、常量、工具
  docs/
    deployment.md     # 部署说明
    alipay.md         # 支付宝接入说明
    openai.md         # OpenAI 图像能力接入说明
    roadmap.md        # 产品路线图
  assets/
    wechat-qr.png     # 联系微信二维码
```

## 联系方式

公司：杭州特米诺偲人工智能科技有限公司

- 邮箱：<hanfeihu@tminos.com>
- 微信：`13656670870`
- 微信二维码：见 [assets/wechat-qr.png](assets/wechat-qr.png)

## 商业化方向

开源项目负责传播和自部署，官方站点负责省心服务：

- 官方托管版
- Pro 模板库
- 企业 API
- 团队版
- 私有化部署
- 定制开发

## 开源协议

本项目使用 AGPL-3.0 协议开源，详见 [LICENSE](LICENSE)。

品牌名、域名、Logo、官方站点视觉资产和商标权益不随源码授权自动开放，详见 [TRADEMARK.md](TRADEMARK.md)。
