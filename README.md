# 107AB0744

pecheck 判斷所抓取的檔案是否為PE檔
getstring 用來擷取檔案裡面的內容
networkx 畫圖
jaccard 做malwave相似度之比較
若threshold設為0.8，則表示使用jaccard算出的數字只要大於等於0.8以上兩者就會進行連線。
若threshold設為0.3，則表示使用jaccard算出的數字只要大於等於0.3以上兩者就會進行連線。
關聯值設太高或太低都不好，太高連接線太少，則會找不到相關的惡意程式；太低連接線太多，則會造成每個惡意程式都相關，所以太高或太低，所呈現出來的結果都不是很準確。
