# 电商用户行为分析与流失预测

基于 UCI Online Retail 真实数据集的端到端数据分析项目。

## 项目简介

通过对 50 万条电商交易记录进行清洗、分析与建模，实现用户行为洞察与流失风险预测。

## 主要成果

- 清洗 54 万条原始数据，有效数据保留率 73%
- 构建 RFM 用户分层模型，识别高价值用户占比 22%，流失预警用户 643 人
- 训练 Gradient Boosting 流失预测模型，AUC = 0.73
- 输出 6 张可视化图表，涵盖销售趋势、用户分层、模型评估

## 技术栈

Python | pandas | numpy | scikit-learn | matplotlib | seaborn | Jupyter Notebook

## 项目结构
```
├── ecommerce_analysis.ipynb   # 完整分析代码
├── monthly_sales.png          # 月度销售趋势
├── top10_country.png          # Top10 销售国家
├── user_distribution.png      # 用户消费分布
├── heatmap.png                # 销售热力图
├── rfm_segments.png           # RFM 用户分层
├── rfm_scatter.png            # RFM 散点图
└── model_results.png          # 模型评估结果
```

## 数据来源

[UCI Online Retail Dataset](https://archive.ics.uci.edu/dataset/352/online+retail)
