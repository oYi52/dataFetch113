# 113年Data Fetch範例

### 請完成以下作業

請建立一個靜態的HTML檔案，並引入以下CDN
1. Bootstrap
```html
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.1.1/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-F3w7mX95PdgyTmZZMECAngseQB83DfGTowi0iMjiWaeVhAn4FJkqJByhZMI3AhiU" crossorigin="anonymous">
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.1.1/dist/js/bootstrap.bundle.min.js" integrity="sha384-/bQdsTh/da6pkI1MST/rWKFNjaCP5gBSY4sEBT38Q/9RBh9AH40zEOg7Hlq2THRZ" crossorigin="anonymous"></script>
```
2. ApexCharts
```html
    <script src="https://cdn.jsdelivr.net/npm/apexcharts"></script>
```

請使用fetch方法讀入以下API的資料
https://data.moenv.gov.tw/api/v2/aqx_p_20?api_key=e8dd42e6-9b8b-43f8-991e-b3dee723a52d&limit=1000&sort=ImportDate%20desc&format=JSON

請以圖表(Bar Chart)以及表格（需加入placeholder）的方式呈現讀取得的資料當中「富貴角」觀測站當月降雨量變化
完成後請繳交該靜態html檔案。
