# AutoML

AutoML : Automated Machine Learning

## PyCaret

https://github.com/pycaret/pycaret

## auto-sklearn

https://github.com/automl/auto-sklearn

## mljar-supervised

https://github.com/mljar/mljar-supervised/

## autogluon

https://github.com/autogluon/autogluon

# EDA

探索的データ解析 (EDA : Exploratory Data Analysis)

## ydata-profiling

https://github.com/ydataai/ydata-profiling

## AutoViz

https://github.com/AutoViML/AutoViz

## sweetviz

https://github.com/fbdesignpro/sweetviz

# データ分析

## pandas

### データ集約

`df.groupby([列1,列2])`

`df.groupby([列1,列2]).sum()`,`df.groupby([列1,列2]).mean()`,`df.groupby([列1,列2]).max()`,`df.groupby([列1,列2]).min()`,`df.groupby([列1,列2]).count()`

`df.groupby([列1,列2]).agg(['count','max', 'min', 'sum'])`

### 要約統計量

`df.describe()`

### 要約情報

`df.info()`

### クロス集計

`pd.crosstab()`

### ピボットテーブル

`df.pivot_table()`

### データの出現数をカウント

`pb.value_counts()`

## numpy

### 分散

`np.var()`

### 標準偏差

`np.std()`

### 合計

`np.csum()`

### 累積和

`np.cumsum()`

# 分類問題

## クラス確率

`model.predict_proba(test_x)`

2値分類の 0か1 か の 1 になる確率を取得する場合、下のように2列目を取得  
`model.predict_proba(test_x)[:,1]`

# 時系列

## 指数加重移動平均, 指数加重移動標準偏差

ewm.mean(), ewm().std()


