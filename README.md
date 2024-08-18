# Insurance Company Benchmark (COIL 2000) 預測潛在消費者及識別識別重要因素-露營車保險

![Insurance Company Image](https://imgur.com/BWu0nAS)
.

## About the project

專案目標是從保險公司的角度出發，預測顧客是否會購買露營車保險。

"Insurance Company Benchmark" 資料集包括來自不同顧客的紀錄. 每個顧客紀錄包含人口、社會經濟特徵（郵遞區號層級）與其他保險產品相關特徵（個人層級）。

訓練集的紀錄有5822筆，測試集則有4000筆。

**在這個專案中，我們運用三種方法來處理不平橫資料的問題：
1.使用多種抽樣方法 
2.使用umbalanced-learn library中專門處理不平衡問題的模型 
3.調整少數類別的權重**

資料集來源 [here](https://archive.ics.uci.edu/dataset/125/insurance+company+benchmark+coil+2000)

## Built with

- Python 3.10.12
- Jupyter Notebook
