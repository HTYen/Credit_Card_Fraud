# Credit_Card_Fraud
此資料集為比賽資料集中的train，沒有test，所以test要自行切割  
因原始的test為90-120天發生的，所以我在"Credit_Card_Fraud_basic_model_HT.ipynb"也是依時間去切train,test(1-71天,72-90天)  
資料集似乎不公開，所以大家學習與討論技術就好，但不要把資料拿給別人  
評分標準為f1 score  
notebook命名方式：請在最後加上個人名稱  
  
2020/3/4  
新增"Feature_Engineering_Practice1_HT.ipynb"，裡面嘗試新增一欄 num_trades_3d 紀錄該卡號(cano)發生這筆交易的前三天，有多少次交易。可先想想程式碼要怎麼寫，再看我的可怎麼改進。
2020/3/3  
目前可嘗試研究的兩個方向:  
1. (機器學習)cross_validate測出來的結果與測test中的分數相比差太多，尚未知道原因為何，請見"Credit_Card_Fraud_basic_model_HT.ipynb"
2. (資料前處理)特徵工程要新增什麼欄位  
  
可參考別人的資料：  
https://github.com/KuanHaoHuang/tbrain-esun-fraud-detection/blob/master/doc/%E7%AB%B6%E8%B3%BD%E6%B5%B7%E5%A0%B1_StarRingChild.pdf  
http://blog.tcfst.org.tw/asvda/file/JQ04/08.%E9%87%91%E8%9E%8D%E4%BF%A1%E7%94%A8%E5%8D%A1%E7%B5%841204.pdf  
