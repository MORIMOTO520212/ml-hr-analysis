# MachineLearning Human Resources Analysis
## 概要  
機械学習 ある企業の従業員のデータを基に「退職」か、「非退職」を分類予測する。

## データの変数の説明
- index - 従業員ID
- left - 離職状況（1:退職, 0:非退職）
- satisfaction_level - 満足度
- last_evaluation - 最終評価

## 学習結果
テストデータで評価した。
|model|score|
|---|---|
|Logistic only|0.790159|
|SVC only|0.947302|
|KNN only|0.936825|
|PCA and RF|0.925714|
|PCA and SVC|0.909206|
|PCA and KNN|0.914603|
|PCA and RF (GridSearch)|0.974603|