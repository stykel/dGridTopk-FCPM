dGridTopk-FCPM实验数据集<br>
======

数据集由 `真实数据集` 和 `合成数据集` 组成。<br>
<br>

真实数据集<br>
-------
真实数据集位于 [Real Data Sets](https://github.com/stykel/dGridTopk-FCPM/tree/main/Real%20Data%20Sets) 文件夹中，包含 **昆明市POI数据集**（[2018_kunming_poi.csv](https://github.com/stykel/dGridTopk-FCPM/blob/main/Real%20Data%20Sets/2018_kunming_poi.csv)，特征数：23，实例个数：298851 ） 和 **上海市POI数据集**（[2018_shanghai_poi.csv](https://github.com/stykel/dGridTopk-FCPM/blob/main/Real%20Data%20Sets/2018_shanghai_poi.csv)，特征数：23，实例个数：218800 ） 。
<br>

两个真实数据集的数据特征均为：{ 实例特征，实例id，实例坐标（经纬度） }

合成数据集<br>
------- 
合成数据集位于 [Synthetic Data Sets](https://github.com/stykel/dGridTopk-FCPM/tree/main/Synthetic%20Data%20Sets) 文件夹中，包含用于测试 **时间与实例数关系的数据集**（位于 [ins](https://github.com/stykel/dGridTopk-FCPM/tree/main/Synthetic%20Data%20Sets/ins) 文件夹中） 和用于测试 **时间与clumpy关系的数据集**（位于 [clumpy](https://github.com/stykel/dGridTopk-FCPM/tree/main/Synthetic%20Data%20Sets/clumpy) 文件夹中） 。
<br>

* **时间与实例数关系的数据集（合成数据集组1）**<br>
  20万实例：[instance_20W.data](https://github.com/stykel/dGridTopk-FCPM/blob/main/Synthetic%20Data%20Sets/ins/instance_20W.data) <br>
  40万实例：[instance_40W.data](https://github.com/stykel/dGridTopk-FCPM/blob/main/Synthetic%20Data%20Sets/ins/instance_40W.data) <br>
  60万实例：[instance_60W.data](https://github.com/stykel/dGridTopk-FCPM/blob/main/Synthetic%20Data%20Sets/ins/instance_60W.data) <br>
  80万实例：[instance_80W.data](https://github.com/stykel/dGridTopk-FCPM/blob/main/Synthetic%20Data%20Sets/ins/instance_80W.data) <br>
  100万实例：[instance_100W.data](https://github.com/stykel/dGridTopk-FCPM/blob/main/Synthetic%20Data%20Sets/ins/instance_100W.data) <br>

* **时间与clumpy关系的数据集（合成数据集组1）**<br>
  clumpy=5：[clumpy_5.data](https://github.com/stykel/dGridTopk-FCPM/blob/main/Synthetic%20Data%20Sets/clumpy/clumpy_5.data) <br>
  clumpy=10：[clumpy_10.data](https://github.com/stykel/dGridTopk-FCPM/blob/main/Synthetic%20Data%20Sets/clumpy/clumpy_10.data) <br>
  clumpy=15：[clumpy_15.data](https://github.com/stykel/dGridTopk-FCPM/blob/main/Synthetic%20Data%20Sets/clumpy/clumpy_15.data) <br>
  clumpy=20：[clumpy_20.data](https://github.com/stykel/dGridTopk-FCPM/blob/main/Synthetic%20Data%20Sets/clumpy/clumpy_20.data) <br>
  clumpy=25：[clumpy_25.data](https://github.com/stykel/dGridTopk-FCPM/blob/main/Synthetic%20Data%20Sets/clumpy/clumpy_25.data) <br>

所有合成数据集的数据特征均为：{ 实例id，实例特征，实例坐标（经纬度） }

