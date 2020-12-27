# Peanuts-HDWB

![build](https://github.com/pudo/dataset/workflows/build/badge.svg)

Peanuts数据集是基于[CASIA-HDWB](http://www.nlpr.ia.ac.cn/databases/handwriting/Home.html)数据集的自建手写汉字评分数据集，评分主要根据人工对每个字进行打分（1-5分）后取均值。用于训练文字分割及评分网络，评估网络可行性。

数据格式如下：

out_ave.csv:

| ID       | Score    | Char     |
| -------- | -------- | -------- |
| 图片名称 | 文字得分 | 文字代码 |

