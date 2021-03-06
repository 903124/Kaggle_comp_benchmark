# Kaggle Tabular Competition Benchmark
Benchmark of tabular dataset using kaggle competition

| Score (Cross validation / Pubic / Private ) | Default Risk (AUC ↑)        | Fraud Detection (AUC ↑)        | Customer Satisfaction (AUC ↑)  | Safe Driver Prediction (Gini↑) |
|------------------------------|-----------------------------|--------------------------------|--------------------------------|--------------------------------|
| Logistic                     | [0.51440 / 0.55504 / 0.53800](https://www.kaggle.com/code/s903124/base-model-with-0-804-auc-on-home-credit-logistic) | [0.742576 / 0.803224 / 0.752711](https://www.kaggle.com/code/s903124/xgb-fraud-with-magic-training-logistic/notebook) | [0.553412 / 0.52249 / 0.51959](https://www.kaggle.com/code/s903124/to-the-top-v2-training-logistic)   | [0.18953 / 0.18725 / 0.19470](https://www.kaggle.com/code/s903124/2nd-place-lightgbm-solution-training-logistic)    |
| Random Forest                | [0.73676 / 0.73359 / 0.73273](https://www.kaggle.com/code/s903124/base-model-with-0-804-auc-on-home-credit-rf) | [0.943387 / 0.944480 / 0.914231](https://www.kaggle.com/code/s903124/xgb-fraud-with-magic-training-rf) | [0.756067 / 0.76580 / 0.76160](https://www.kaggle.com/code/s903124/to-the-top-v2-training-rf)   | [0.17171 / 0.20150 / 0.21191](https://www.kaggle.com/code/s903124/2nd-place-lightgbm-solution-training-rf)    |
| MLP                          | [0.67672 / 0.71152 / 0.71964](https://www.kaggle.com/code/s903124/base-model-with-0-804-auc-on-home-credit-mlp) | [0.879579 / 0.910946 / 0.852730](https://www.kaggle.com/code/s903124/xgb-fraud-with-magic-training-mlp) | [0.767340 / 0.80079 / 0.78442](https://www.kaggle.com/code/s903124/to-the-top-v2-training-mlp)   | [0.14097 / 0.19008 / 0.19936](https://www.kaggle.com/code/s903124/2nd-place-lightgbm-solution-training-mlp)    |
| 1D-CNN                       | [0.71816 / 0.74979 / 0.75524](https://www.kaggle.com/code/s903124/base-model-with-0-804-auc-on-home-credit-cnn) | [0.841671 / 0.865416 / 0.814458](https://www.kaggle.com/code/s903124/xgb-fraud-with-magic-training-cnn) | [0.821149 / 0.82849 / 0.81163](https://www.kaggle.com/code/s903124/to-the-top-v2-training-cnn)   | [0.21196 / 0.23523 / 0.24516](https://www.kaggle.com/code/s903124/2nd-place-lightgbm-solution-training-cnn)    |
| Gradient boosting (untuned)  | [0.78889 / 0.79300 / 0.78927](https://www.kaggle.com/code/s903124/base-model-with-0-804-auc-on-home-credit-untuned) | [0.94401 / 0.950708 / 0.927236](https://www.kaggle.com/code/s903124/xgb-fraud-with-magic-training-untuned)  | [0.789344 / 0.80332 / 0.78300](https://www.kaggle.com/code/s903124/to-the-top-v2-training-untuned)   | [0.27938 / 0.27799 / 0.28117](https://www.kaggle.com/code/s903124/2nd-place-lightgbm-solution-training-untuned)    |
| Gradient boosting (original) | [0.79848 / 0.80028 / 0.79741](https://www.kaggle.com/code/s903124/base-model-with-0-804-auc-on-home-credit-training) | [0.96272 / 0.959638 / 0.931280](https://www.kaggle.com/code/s903124/xgb-fraud-with-magic-training)  | [0.841088 / 0.83987 / 0.82655](https://www.kaggle.com/code/s903124/to-the-top-v2-training)   | [0.28731 / 0.28553 / 0.29039](https://www.kaggle.com/code/s903124/2nd-place-lightgbm-solution-training)   |

## Description
The above table attempt to provide some benchmark of gradient boosting-friendly task for tabular data using past Kaggle solutions that acheive a high score using a gradient boosting model. Machine learning models chosen here is logistic regression, random forest, multilayer perception, 1D convolutional neural network and gradient boosting model( XGBoost/LightGBM) used in the orignal solution, without hyperparameter tuning except the original. Thanks for @CPMP and @nyanp on Kaggle for codes snippets used in training and original authors for providing valuable solution

Original solution

Default Risk: https://www.kaggle.com/code/hikmetsezen/base-model-with-0-804-auc-on-home-credit 

Fraud Detection: https://www.kaggle.com/code/cdeotte/xgb-fraud-with-magic-0-9600

Customer Satisfaction: https://www.kaggle.com/code/zfturbo/to-the-top-v2

Safe Driver Prediction: https://www.kaggle.com/code/xiaozhouwang/2nd-place-lightgbm-solution/

