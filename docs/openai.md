# OpenAI 图像能力接入规划

墨元 AI 的图像生成能力建议通过独立适配层封装，避免业务代码直接绑定某一个模型或供应商。

## 适配层目标

- 文生图
- 图生图
- 参考图生成
- 局部编辑
- 多尺寸输出
- 成本统计
- 内容安全处理
- 失败重试与错误归因

## 模型命名提醒

接入前请以 OpenAI 官方文档为准确认最新可用模型名、参数、价格和组织验证要求。产品页面可以面向用户写“GPT Image 系列”或“先进 AI 图像模型”，避免把内部模型名直接作为品牌承诺。

## 建议接口

```ts
export interface ImageGenerationProvider {
  generateImage(input: GenerateImageInput): Promise<GeneratedImageResult>;
  editImage(input: EditImageInput): Promise<GeneratedImageResult>;
}
```
