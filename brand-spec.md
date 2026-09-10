# 关系成长小程序 Brand Spec

来源：`DESIGN_SPEC.md` 2026-08-24 草案。视觉目标是“可爱的关系复盘外壳，冷静专业的分析内核”，但界面不制造审判、羞辱、围观或输赢焦虑。

## OKLch tokens

```css
:root {
  --bg: oklch(96.8% 0.024 70);
  --surface: oklch(98.7% 0.012 78);
  --fg: oklch(30% 0.035 48);
  --muted: oklch(50% 0.038 52);
  --border: oklch(89.5% 0.033 65);
  --accent: oklch(55% 0.12 43);
}
```

辅助语义色来自同一设计规范：

```css
:root {
  --success: oklch(53.45% 0.0854 170.61);
  --warn: oklch(62.64% 0.1248 70.45);
  --danger: oklch(50.03% 0.1821 29.51);
}
```

## 暂用名称与说话方式

- 暂用名称：慢慢说。含义是不用急着表达清楚，也不用急着分对错；不是已确定的正式品牌名。
- 语气：温柔、亲近、有对话感，像认真听你说话，不像说明书。少用术语与被动句，多用具体问题和小邀请。
- 可爱来自小动物和轻巧的措辞，偶尔用“哦”“呀”，不堆语气词，不叫用户“宝宝”，不撒娇或说教。
- 保留“探索自己”和“冲突复盘”两个核心功能名；明确操作按钮不能因为文案可爱而难以理解。
- 安全、知情同意、删除、隐私说明保持直接清楚，不轻描淡写风险，不承诺绝对保密。
- 演示就是演示：不隐藏 AI 的能力边界，不把本地模板、浏览器保存或未实现的导出说成真实服务。

## Type

- Display: `-apple-system, BlinkMacSystemFont, "PingFang SC", "Microsoft YaHei", system-ui, sans-serif`
- Body: `-apple-system, BlinkMacSystemFont, "PingFang SC", "Microsoft YaHei", system-ui, sans-serif`
- Mono: `ui-monospace, "JetBrains Mono", "SF Mono", Menlo, monospace`

## Posture rules

1. “认识自己”偏安静、私密、留白更多；“一起复盘”偏清晰、公平、可行动。
2. 不使用法槌、天平、胜诉章、败诉章或围观式审判视觉，改用证据夹、便签、修复清单隐喻。
3. 高风险内容从柔粉语气切换为浅灰白和低饱和红色，文案直接、清晰，不可可爱化。
4. 结果页表达“当前倾向”“可能”“基于你们提供的信息”，不输出人格标签、责任百分比或关系预测。
5. 卡片圆角约 12px，按钮触控目标不小于 44px，报告页用全宽分区与轻边框，避免卡片套卡片。
