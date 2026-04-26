---
aliases: [隐含波动率, IV, implied volatility]
tags: [investment, options, concept]
sources: [options-greeks-and-implied-volatility.md, leaps-long-term-options-practical-manual.md]
created: 2026-04-24
updated: 2026-04-25
---

# 隐含波动率

## Summary

[[隐含波动率]] 是从期权市场价格反推出来的未来波动预期。当前知识库将它视为期权价格的一种预期表达形式，反映市场对未来不确定性的定价，而不是可以直接观测到的历史事实。

新的 [[LEAPS]] 来源补充了事件风险场景：财报前隐含波动率可能抬升，财报后若不确定性消退，[[IV Crush]] 会压低期权权利金。

## Key Notes

- 它由期权当前价格、标的价格、执行价、期限和利率等变量倒推得到。
- 期权价格越高，在其他条件相同的情况下，对应的 [[隐含波动率]] 往往越高。
- 它与 [[Vega]] 直接相关，并通过 [[波动率微笑]] 体现在不同执行价之间的差异上。
- 财报等事件后隐含波动率骤降，可能让看对方向的期权买方仍然亏损。

## Related Pages

- [[Vega]]
- [[波动率微笑]]
- [[IV Crush]]
- [[Delta]]
- [[Gamma]]
- [[知识：期权风险指标与隐含波动率深度解析]]
