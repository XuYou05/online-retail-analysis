# 数据说明

## 来源

**UCI Machine Learning Repository — Online Retail Dataset**

- 官方页面：https://archive.ics.uci.edu/dataset/352/online+retail
- 直接下载（xlsx，约 23 MB）：
  https://archive.ics.uci.edu/ml/machine-learning-databases/00352/Online%20Retail.xlsx

## 内容

英国一家在线零售商的真实交易记录，2010-12-01 至 2011-12-09。

| 字段 | 说明 |
|---|---|
| InvoiceNo | 发票号；以 `C` 开头表示取消单 |
| StockCode | 商品编码 |
| Description | 商品名称 |
| Quantity | 数量（可能为负，表示退货） |
| InvoiceDate | 开票时间 |
| UnitPrice | 单价 |
| CustomerID | 客户 ID（约 25% 缺失） |
| Country | 国家 |

## 本仓库不包含数据文件

原始文件 46 MB，超出常规仓库建议体积。请按上面的链接自行下载，保存为 `online_retail.csv`。
