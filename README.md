# Data_Mining_Research-Practice_2020_HW5
HW5 - Fake News Detection 2  
資料集 : Fake News Detection Challenge KDD 2020  
目標 : 預測一則新聞是否reliable，分別利用RNN與LSTM對"train.csv"的資料建模，對"test.csv"測試計算Accuracy    
流程 :  
>1.資料前處理：  
a. 讀取資料，利用分割符號切割字串、建立train&test之DataFrame  
b. 去除停頓詞  
c. 文字轉向量  
2.建模  
a. 分別用RNN與LSTM對train.csv的資料進行建模，可自行設計神經網路的架構  
b. 加入Dropout Layer設定Dropout參數(建議0.7)進行比較  
c. plot出訓練過程中的Accuracy與Loss值變化  
3.評估模型  
a. 利用"text.csv"的資料對2.所建立的模型進行測試，並計算Accuracy  
