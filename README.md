# AIFactory_AnomalyDetection
AIFactory제4회 2023 연구개발특구 AI SPARK 챌린지 - 공기압축기 이상 판단(23.04.03 ~ 23.04.21)
https://aifactory.space/competition/detail/2226

## Team member
정지현, 위성진

## Solution Overview
- Each type has strong linear correlation: Anomaly detection by self-supervised linear regression
- Use Max(abs(error)) from train data  as the threshold of each type
- Test samples with higher error than threshold is labeled as anomaly


## File Structure
```
├── README.md
├── dataset.zip
└── LinearRegression.ipynb
```
dataset.zip

-download from https://aifactory.space/competition/data/2226


## Train & Inference
1. Download dataset.zip from the link above, and unzip it
2. Run LinearRegression.ipynb

The submission file will be saved in `./submissions`
