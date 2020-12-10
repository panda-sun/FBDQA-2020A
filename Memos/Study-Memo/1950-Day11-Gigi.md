# 期权
期权是一种金融衍生品，在未来某个时刻以特定的价格买入或卖出某项标的资产的权利
call：认购（看涨）；put：认沽（看跌）
行权方式：欧式期权；美式期权
## 到期收益图
1. 评估收益的风险特征：
	最大风险：（买入认购为例）：持续下跌损失认购期权全部权利金
	最大收益：（买入认购为例）：只要标的价格上升，理论上最大收益没有上线
2. 计算损益平衡点
	买入认购为例：到期时的损益平衡点=行权价+认购期权的权利金

## 期权价格
期权价格=内在价值+时间价值
内在价值：假设期权当前立即到期，买方通过选择是否行权所获取的收益
时间价值：买方支付的权利金中超出当前内在价值的部分

## 期权的四大基本交易策略
1. 买入认购期权（标的资产价格上升，波动率上升）：适用看大涨，短期内急涨
	策略优势：方向做反，损失有限；利用杠杆，以小博大；损失有限，不需要保证金
	策略劣势：时间价值持续衰减对买方不利；波动率下降对买方不利；胜率较低
2. 卖出认购期权（标的资产价格下跌，波动率下降）
	策略优势：优先收取权利金；赚取的时间价值确定；卖方具有概率优势，卖虚值期权容错性好
	策略劣势：最大收益有限；遇到大跌时收益小于买沽；若大幅上涨则损失惨重
3. 买入认沽期权：看大跌，短期内急跌
	策略优势：同买入认购
	策略劣势：同买入认购
4. 卖出认沽期权
## 期权交易的获利模式
1. 高杠杆博方向（买彩票）：看涨/看跌
2. 赚取时间价值（卖废纸）：看不涨/看不跌
3. 波动率交易：跨期买卖
## 价差策略
1. 牛市：
买入一份行权价较低的认购期权（平值/轻度实值）
卖出一份相同到期日，行权价格较高的认购期权（轻度虚值）
2. 熊市：
买入一份行权价较高的认沽期权（平值/轻度实值）
卖出一份相同到期时，行权价格较低的认沽期权（轻度虚值）
## 期权希腊字母
Delta： 衡量标的资产价格变动时，期权价格的变化幅度
Gamma： 衡量标的资产价格变动时，delta的变化幅度
Vega： 衡量标的资产价格波动率变动时，期权价格的变化幅度
Theta： 衡量随时间流逝，期权价格的变化幅度
Rho： 衡量无风险利率变动时，期权价格的变化幅度

## 交易的决策流程
1. 对行情有一个观点
2. 用什么策略类型来表达观点
3. 选择合适的合约
4. 风控+动态调整


