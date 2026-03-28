# Time-Series-Analysis
时间序列分析与预测
技术栈：Pandas + Statsmodels + Prophet/LSTM
数据：睡眠状态识别数据扩展
功能：特征工程、多模型比较、部署
延续：完善数据挖掘课程项目

time-series-analysis/
├── README.md
├── requirements.txt
├── data/
│   ├── sleep_data/    # 睡眠状态识别数据
│   └── stock_data/    # 股票数据示例
├── notebooks/
│   ├── 01_eda.ipynb   # 探索性分析
│   ├── 02_feature_engineering.ipynb
│   └── 03_model_comparison.ipynb
├── src/
│   ├── preprocessing.py
│   ├── features.py
│   ├── models.py
│   └── evaluation.py
└── results/           # 分析结果
    └── reports/       # 自动生成报告
