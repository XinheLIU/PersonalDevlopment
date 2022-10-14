# PersonalDevlopment


## 字节跳动

### Summary (Monetization, Data Scientist)

- 冷启动策略设计：针对推荐系统中新广告和流量数据匮乏的探索-利用问题，利用数据Debias（ Counterfactual Evaluation，Doubly Robust Method）以及强化学习（Stochastic Negative Sampling, Top-K Off-Policy Learning)等方案来提高系统探索效率和一致性，增强模型泛化性，累计取得+xx%广告收入增长
- 投放激励和生态治理：以投放系统针对客户和流量的扶持（Boost）资源分配最优化为目标，通过因果机器学习/增效建模和合成控制的方式，评估扶持在系统/客户层面的ROI，和研发合作实现根据增效统一分配扶持资源的方案，取得平均ROI提高yy%的收益
- 迁移学习策略：在隐私监管加强，无法获取IOS系统下用户粒度数据的背景下，挖掘可接触不同层级数据相似性及迁移效果，评估多种迁移学习方案（Multi-task, Distillation, Semi-supervised)，设计可迁移特征评估/迭代框架和指标，累计损失挽回zz%以上
- 数据指标和产品设计：协同团队，迭代对齐排序的推荐系统评估核心指标和新创意型投放系统核心指标。设计新的A/B实验及线上评估方案优化组间效果溢出问题。设计和数据产品一起设计自动归因，异动归因等数据产品，取得团队内广泛应用


## 高盛

### Summary (Systematic Trading Strategies, Desk Strat)

- 量化交易策略开发：负责高盛多因子和波动率在内的多种指数量化交易策略（QIS）设计和开发。在职期间开发跨资产多因子，VIX-CDX相对价值， Dispersion，波动率 Carry等策略，夏普比率0.5-2.5。
- 数据和风险管理产品建设：优化迭代高盛量化核心模块（回测平台，资产组合最优化（Mosaic）、风险管理TDAPI、市场数据和机器学习一体化交易等）并产品化，以平台和服务方式开放给机构投资者。
- 风险溢价因子策略：在因子层面利用因子动量\Crowding\宏观经济模型(nowcasting)等方法对产品组合进行的动态择时，衡量择时对风险收益(例如夏普比率) 影响，给与投资者动态择时建议以策略，覆盖面3亿+。将不同市场的策略通过不同组合最优化技巧构建跨市场全球投资组合。夏普比1.8
- 波动率交易策略：设计多种Volatility Carry策略（Intraday\Credit\Theta-Neutral, etc.），设计，开发业界第一个Dispersion类策略(单个策略覆盖50+个股期权) 以及相关波动率模型设计和纠偏（Calibration）。夏普比率0.5-2.0，低相关性。AUM 10亿+。
- 回测和分析平台优化：开发2.0版回测框架，并将组内资产配置（Black-Litterman）、因子统计有效性检测、相关矩阵估计、业绩归因、组合分析指标（Analytics）等模块化开放给客户。利用实时市场数据对所有(4000+)投资策略进行日内估计，将每日数据计算提前8小时左右，显著提高客户体验。