---
aliases: [LEAPS 无限续杯策略, 无限续杯, LEAPS期权“无限续杯”实战复利策略, LEAPS infinite rollover strategy]
tags: [investment, options, leverage, compounding, concept]
sources: [leaps-infinite-rollover-compounding-strategy.md]
created: 2026-04-25
updated: 2026-04-25
---

# LEAPS 无限续杯策略

## Summary

[[LEAPS 无限续杯策略]] 是一种把 [[LEAPS]] 作为长期杠杆暴露，并用 [[期权展期]]、利润收割和现金储备持续降低持仓成本的框架。来源的目标不是持有到期，而是在高 Delta、期限缩短或深度回撤时按规则调整，让长期期权仓位保持可续航。

## Operating Rules

- 初始配置建议 60% 资金买入 [[LEAPS]]，40% 留作现金储备。
- 初始合约偏好约 650 到 800 天到期、[[Delta]] 约 0.8 的 [[深度价内期权]]。
- 当 Delta 大于 0.9 时，卖出现有合约并换入更远期、Delta 约 0.7 的新合约。
- 当剩余天数小于 300 天时，不管盈亏都进行 [[期权展期]]。
- 当 Delta 小于 0.5 时，等待 30 天，再根据现金储备比例决定是否加仓。

## Risk Notes

- 该策略和 [[现金流瀑布]] 对利润处理的重点不同：前者强调在 LEAPS 策略内继续降低成本，后者强调期权利润先回补现金和长期仓位。
- 暴跌期可能要求在账面亏损时继续加仓或续约，执行压力很高。
- 获利展期可能触发短期资本利得税，影响复利效果。
- 频繁展期会放大 [[期权滑点]] 和交易摩擦。

## Related Pages

- [[LEAPS]]
- [[期权展期]]
- [[Delta]]
- [[Theta]]
- [[Limit Order]]
- [[期权滑点]]
- [[现金流瀑布]]
