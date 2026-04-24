---
aliases: [Wheel Strategy]
tags: [investment, options, concept]
sources: [cash-flow-waterfall-system.md, covered-call-practical-guide.md, us-stock-options-wheel-retirement-strategy.md]
created: 2026-04-24
updated: 2026-04-24
---

# Wheel Strategy

## Summary

[[Wheel Strategy]] 在当前知识库中指由卖出 [[Sell Put]] 和卖出 [[Covered Call]] 连接起来的期权现金流循环。它在 [[仓位配比系统]] 中承担主要的收入引擎角色，目标是稳定产生权利金，而不是追求极端杠杆。

在退休场景中，来源把它描述为现金与持股之间的循环：先用现金卖出 put，接到股票后卖出 call，股票被行权后重新回到现金，再进入下一轮卖 put。

## Key Notes

- 在账户的期权层中，它占主要权重。
- 常见逻辑是先通过 [[Sell Put]] 在更满意价格争取建仓，再在持股后卖出 [[Covered Call]]。
- 它产生的利润应遵守 [[现金流瀑布]] 规则回流长期层。
- 在 [[退休现金流策略]] 中，它的目标是持续产生权利金并降低被动卖出本金的频率。
- 标的选择需要服从 [[接盘意愿]]，否则高权利金可能掩盖本金风险。

## Related Pages

- [[Sell Put]]
- [[Covered Call]]
- [[现金流瀑布]]
- [[仓位配比系统]]
- [[退休现金流策略]]
- [[接盘意愿]]
