# pymongodb

## 前置作業

### Google map api 
請按照 google docmentation 步驟 https://developers.google.com/places/web-service/get-api-key

### 未安裝mongodb環境
https://www.mongodb.com/download-center/community
<br> 選擇Windows X64 下載</br> 

安裝完後開啟C:\Program Files\MongoDB\Server\4.2\bin\mongo.exe
<br> 開啟mongo確定是否可使用<br> 

### 已經有安裝mongodb環境
<br> pymongo安裝pip install pymongo<br> 
<br> gmplot安裝pip install gmplot<br> 

### 安裝完pymongo後參考菜鳥教程 pymongo執行連線程式
  import pymongo
 
myclient = pymongo.MongoClient("mongodb://localhost:27017/")
mydb = myclient["runoobdb"]
mycol = mydb["sites"]
 
x = mycol.find_one()
 
print(x)
如果執行沒出現錯誤代表mongodb與pymongodb設定完成，如果有錯誤請自行google







## 參考文獻

菜鳥教程：https://www.runoob.com/python3/python-mongodb-insert-document.html

https://www.runoob.com/python3/python-mongodb-query-document.html

PyMongoDB documentation：https://pymongo.readthedocs.io/en/stable/examples/geo.html#creating-a-geospatial-index

Geospatial Indexes - Data Wranging with MongoDB：https://www.youtube.com/watch?v=iGnSNfzaLf4

gmplot：https://github.com/gmplot/gmplot
