---
tags: [investment, options, concept]
sources: [options-greeks-and-implied-volatility.md, leaps-long-term-options-practical-manual.md, leaps-infinite-rollover-compounding-strategy.md]
created: 2026-04-24
updated: 2026-04-25
---

# Delta

## Summary

[[Delta]] 是期权价格对标的价格变动的一阶敏感度。当前知识库同时记录了它在交易实践中的另一个用途：常被近似理解为期权到期进入实值的理论概率。

新的 [[LEAPS]] 来源进一步把 [[Delta]] 作为合约筛选和展期触发指标：长期深度价内看涨期权常选择 Delta 约 0.7 到 0.8，以获得更接近正股的价格表现。

## Key Notes

- [[Delta]] 越大，期权价格对标的价格变化越敏感。
- 在 [[Sell Put]] 的回调建仓场景中，来源偏好使用较低 Delta 的远虚值合约控制风险。
- [[LEAPS]] 合约选择偏好 Delta 约 0.7 到 0.8。
- 在 [[LEAPS 无限续杯策略]] 中，Delta 大于 0.9 触发收割和展期，Delta 小于 0.5 触发冷静期后的分层加仓判断。

## Related Pages

- [[Gamma]]
- [[Sell Put]]
- [[隐含波动率]]
- [[LEAPS]]
- [[期权展期]]
