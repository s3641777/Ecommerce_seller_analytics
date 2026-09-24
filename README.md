# E-Commerce Seller Performance Analytics with AI Insights

## 專案概述
分析巴西電商平台 Olist 的賣家成效數據，自動識別高取消率賣家，
並透過 Gemini AI 分析客戶評價，找出根本原因並提出改善建議。

## 技術架構
- **數據分析：** R、tidyverse、dplyr
- **視覺化：** ggplot2
- **AI 整合：** Google Gemini API（rgemini）
- **報告產出：** RMarkdown

## 數據集
Brazilian E-Commerce Public Dataset by Olist（Kaggle）
- 99,441 筆訂單
- 3,095 個賣家
- 99,224 筆客戶評價

## 核心發現
- 識別出 12 個高取消率賣家（取消率 > 15%）
- 最高取消率達 42.9%
- AI 分析顯示主要問題：物流延遲、漏發商品、商品描述不實

## 如何執行
1. 下載 Olist 數據集（Kaggle）
2. 設定 Gemini API Key
3. 執行 `seller_analysis.Rmd`

## 作者
Tzu-Yun (Serena) Chien
