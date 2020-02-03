# 健保特約醫事機構-藥局

-   資料來源 : https://data.nhi.gov.tw/Datasets/DatasetDetail.aspx?id=329&Mid=A111068
-   資料下載日期 2020.02.04

# 檔案說明

-   pharmacies.csv : 原始資料檔案
-   empty_addr.csv : 無住址資料清單（一般是藥局休業或停業）
-   依照「分區業務組」切割資料集（方便上傳到 Google My Map - 2000 筆資料限制）
    -   northern.csv : 北區
    -   southern.csv : 南區
    -   central.csv : 中區
    -   eastern.csv : 東區
    -   kaoping.csv : 高屏地區
    -   taipei.csv : 台北地區
        -   taipei_city.csv : 臺北市
        -   other_county.csv : 非台北市 - 包含新北，基隆宜蘭和金門

# ToDo List

-   加入各地方衛生所資訊
-   列出 52 沒有特約藥局的偏鄉和他們的衛生所

# Google My Map

-   [全國健保特約藥局](https://www.google.com/maps/d/u/0/edit?mid=1xRqZsMAVY8cBEhmL2WC4koVstbca7Z8N&ll=24.00932072661157%2C119.71143862203735&z=8)

# 授權聲明

-   資料來自衛福部健保署，採用臺灣政府開放資料授權 https://data.gov.tw/license
-   程式碼（如果有的話）採用 MIT 授權
