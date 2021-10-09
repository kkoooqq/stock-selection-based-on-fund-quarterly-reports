# stock-selection-based-on-fund-quarterly-reports

选股逻辑:
* 根据券商内部基金池，3星以上，对基金累计净值 1年涨幅 进行排序
* 取累计净值中位数（0.65）以上的基金 
* 查看基金持仓情况，Q4  持仓站流通股数量 - Q3  持仓站流通股数量
* 分析基金Q4 增减仓 行业 / 股票

![热力图](https://user-images.githubusercontent.com/43202488/136637129-dafccb4c-1029-42c1-a3ed-b2bb4398c7fe.png)
![分组柱状图](https://user-images.githubusercontent.com/43202488/136637133-a1c23f59-24e7-4b8b-bf24-5005c48f6932.png)
