# 自动派单
基于各种文本分类方法实现自动派单。

## 数据集
2471条训练数据，592条测试数据。

## 如何使用

```bash
$ python train.py
```

## 准确率

NaiveBayes|MultinomialNB|SGD|
|---|---|---|
|0.90033|0.91047|0.93412|

### SGD 的详细报表

![image](https://github.com/foamliu/Auto-Triage/raw/master/images/classification_report.jpg)

