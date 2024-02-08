[English Version](README.md)
# 水果分類專案

## 專案介紹
本專案利用 K近鄰算法（KNN）來對水果進行分類。通過分析水果的物理特性（如重量、寬度、高度和顏色得分），我們的模型能夠準確地將水果分類。

## 數據集
專案使用的數據集包含多種水果的物理特性數據，如重量、寬度、高度和顏色得分。數據集來自Kaggle的[Fruit with colors dataset](https://www.kaggle.com/datasets/mjamilmoughal/fruits-with-colors-dataset)。

## 使用方法
1. 安裝必要的 Python 庫。
2. 加載數據集。
3. 運行 KNN 分類模型。
4. 評估模型性能。

## 模型評估結果
經過仔細的測試，我們發現在原有的四項特徵（重量、寬度、高度和顏色得分）中，選擇「寬度和高度」作為分類依據，可以達到最佳的分類效果。使用這兩項特徵，模型的準確度達到了 95%，這表明綜合考慮寬度和高度是對水果進行有效分類的關鍵因素。

## 需求
本專案需要以下 Python 庫：
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn




