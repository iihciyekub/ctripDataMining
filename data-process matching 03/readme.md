## 2019-3-23
针对 matching method 陈老师提出以下 DP03 配对方法

> Exact Match X1 城市、X4星级，然后找价格在实验组价格的上下10%区间里的所有酒店，计算他们Diff_Rating=CtripRating-QunarRating, 然后选择Diff_Rating为中位数的哪一家作为match的对照组。

|                                       | 阅读方式 |                                       |
| ------------------------------------- | -------- | ------------------------------------- |
| [1] ctrip-aunar-fliggy-hotelinfo.xls  |          | 未处理的数据文档                      |
| [2] 2019320fin.csv                    |          | 1去除评分小于1<br />2去除评论数小于10 |
| [3] matchHotel_                       | 上下对比 | 按原则配对的数据表                    |
| [3] matchHotel_                       | 左右对比 |                                       |
| [4] H1 matching with allrating        | 上下对比 |                                       |
| [4] H1 matching with allrating__marge | 左右对比 | (详细表)包含前100条评论               |
| [4]H1 matching with STD               | 上下对比 |                                       |
| [4]H1 matching with STD__marge        | 左右对比 | (简化表)只列出评论的STD               |

