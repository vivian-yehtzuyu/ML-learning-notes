project/
│
├── data/
│   ├── raw/                # 原始資料
│   ├── processed/          # 前處理後資料
│
├── notebooks/              # EDA、模型實驗
│   ├── 01_eda.ipynb
│   ├── 02_model_baseline.ipynb
│
├── src/
│   ├── data_loader.py      # 載入/整理資料
│   ├── preprocess.py       # 前處理函式
│   ├── features.py         # 特徵工程
│   ├── train.py            # 訓練流程
│   ├── evaluate.py         # 評估流程
│
├── models/                 # 已訓練模型
│
├── utils/                  # 工具函式（logging、metrics）
│
├── requirements.txt        # 套件清單
└── main.py                 # 主程式入口
