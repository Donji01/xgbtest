# xgbtest
dataszie:1000,for test


作为一个xgb的预测测试文件，该模型对数据先进行了简单的描述性分析

extract是特征的扩展，

数据缺失值是采用'nearst插值处理'

enginer是数据分期，按照放款时间进行区分

在进行模型的测试的时候，选用了前1000行的数据进行xgbtest,模型的ks值结果为0.37

