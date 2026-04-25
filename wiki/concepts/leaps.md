---
aliases: [LEAPS, 长期期权, 长期股权预期证券]
tags: [investment, options, leverage, concept]
sources: [cash-flow-waterfall-system.md, leaps-long-term-options-practical-manual.md, leaps-infinite-rollover-compounding-strategy.md]
created: 2026-04-24
updated: 2026-04-25
---

# LEAPS

## Summary

[[LEAPS]] 是到期时间通常在一年以上的长期期权，在当前知识库中有两种用法：一是作为 [[仓位配比系统]] 中小比例、高弹性的战术仓位；二是作为正股替代工具，用较少资金获得接近正股的方向暴露，同时把最大亏损限制为已支付权利金。

新的 LEAPS 来源补充了更完整的执行框架：合约偏好 1.5 到 3 年到期、[[深度价内期权]]、[[Delta]] 约 0.7 到 0.8；标的应来自长期趋势向上的大市值资产，例如 [[QQQ]]、[[SPY]]、[[NVIDIA]]、[[Tesla]] 或 [[Alphabet]]。来源还强调，LEAPS 不等于持有到期，进入最后阶段前需要平仓或 [[期权展期]]，以避免 [[Theta]] 加速损耗。

## Key Notes

- 在 [[现金流瀑布]] 框架中，[[LEAPS]] 属于期权层中约 20% 的弹性仓位。
- [[天哥期权：LEAPS长期期权投资全实战手册]] 建议 LEAPS 在总仓位中控制在 10% 到 20%，避免满仓使用。
- 入场可结合 [[RSI]]、[[布林带]] 和 [[VIX]]；来源给出的 LEAPS 入场参考包括 RSI 小于等于 40、价格触及布林带下轨、VIX 大于 15。
- [[LEAPS 无限续杯策略]] 使用 60% LEAPS 和 40% 现金储备，这是独立策略预算，不应直接等同于整个账户配置。
- 不建议用 LEAPS 赌财报，因为 [[IV Crush]] 可能吞噬权利金。
- 深度价内 LEAPS 可能存在 [[期权滑点]]，执行时应使用 [[Limit Order]]。

## Compatibility Notes

[[现金流瀑布]] 来源强调 LEAPS 获利后应把利润撤出期权层，回补 [[现金仓位]] 和 [[定投仓位]]。[[天哥策略：LEAPS期权“无限续杯”实战复利策略]] 则强调在 LEAPS 策略内部通过 [[期权展期]] 和收割差价降低持仓成本。两者不是完全冲突，但适用于不同风险预算：前者是账户级风险管理，后者是进攻型 LEAPS 子策略。

## Related Pages

- [[RSI]]
- [[布林带]]
- [[VIX]]
- [[Delta]]
- [[Theta]]
- [[深度价内期权]]
- [[期权展期]]
- [[LEAPS 无限续杯策略]]
- [[现金流瀑布]]
- [[仓位配比系统]]
