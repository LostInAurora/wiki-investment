---
aliases: [期权展期, Roll, Rolling, 展期, Roll Up and Out, Roll Out, Row Up and Out, Row Out]
tags: [investment, options, execution, concept]
sources: [leaps-long-term-options-practical-manual.md, leaps-infinite-rollover-compounding-strategy.md]
created: 2026-04-25
updated: 2026-04-25
---

# 期权展期

## Summary

[[期权展期]] 是通过平掉旧合约、买入或卖出新的远期或不同执行价合约，延续策略暴露并重新管理风险参数的动作。在两个 [[LEAPS]] 来源中，它都比直接行权更重要，因为展期可以保留剩余外在价值，并避免临近到期时的 [[Theta]] 加速损耗。

## Key Notes

- 在 [[天哥期权：LEAPS长期期权投资全实战手册]] 中，若还想持有长期暴露，展期优先于直接行权。
- 在 [[LEAPS 无限续杯策略]] 中，当剩余天数小于 300 天时，不管盈亏都执行展期。
- 当 [[Delta]] 大于 0.9 时，来源建议卖出高 Delta 合约并换到更远期、Delta 约 0.7 的新合约。
- 展期会产生交易成本和潜在税务影响，因此需要结合 [[Limit Order]] 和现金管理。

## Related Pages

- [[LEAPS]]
- [[LEAPS 无限续杯策略]]
- [[Theta]]
- [[Delta]]
- [[Limit Order]]
- [[期权滑点]]
