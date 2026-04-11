# 🚀 Sorting Algorithm Interactive Lab  
排序演算法互動網頁

🔗 Live Demo：  
👉 https://brian95117.github.io/sorting-algorithm/

---

## 📌 專案介紹

本專案為一個 **排序演算法視覺化與效能分析系統**，透過互動式網頁展示排序過程，並提供即時統計與圖表分析。

透過動畫與數據比較，可以更直觀理解不同排序演算法的效率差異。

---

## ✨ 專案特色

- 🎯 五種排序法完整實作
- 📊 即時視覺化動畫（柱狀圖）
- ⚡ 顯示比較次數 / 交換次數
- 🎛 可調整資料筆數與速度
- 📈 自動產生效能比較圖（Chart.js）
- 🌌 深色科技風 UI（Dashboard 風格）

---

## 📸 Demo 預覽

👉 https://brian95117.github.io/sorting-algorithm/

（可直接點擊觀看互動效果）

---

## 📚 排序演算法

| 排序法 | 英文 | 時間複雜度 |
|--------|------|------------|
| 氣泡排序 | Bubble Sort | O(n²) |
| 選擇排序 | Selection Sort | O(n²) |
| 插入排序 | Insertion Sort | O(n²) |
| 合併排序 | Merge Sort | O(n log n) |
| 堆積排序 | Heap Sort | O(n log n) |

---

## 🧠 系統功能

### 1️⃣ 排序動畫視覺化

- 柱狀圖即時呈現數據變化
- 顏色區分：
  - 🟡 當前操作
  - 🟣 比較中
  - 🟢 已排序
- 顯示：
  - 比較次數
  - 交換次數
  - 執行步驟

---

### 2️⃣ 複雜度比較

內建完整比較表：

- Best / Average / Worst
- 空間複雜度
- 穩定性

---

### 3️⃣ 效能測試（Benchmark）

📊 功能：

- 測試不同資料規模：
n = 10, 30, 60, 100, 200

- 每組資料取平均值
- 使用 Chart.js 繪製折線圖

---

### 4️⃣ 資料模式

支援多種測試情境：

- 隨機資料
- 接近排序
- 完全反序
- 自訂輸入（CSV）

---

## ⚙️ 使用方式

### ▶ 開啟系統

直接使用：

👉 https://brian95117.github.io/sorting-algorithm/

---

### ▶ 操作流程

1. 選擇排序法
2. 設定資料筆數與速度
3. 點擊「產生資料」
4. 執行排序：
   - ▶ 開始排序
   - ⏭ 單步執行
5. 查看動畫與統計結果

---

## 📊 實驗分析

### 🔍 結果觀察

- O(n²) 演算法：
  - Bubble / Selection / Insertion
  - 隨 n 增加，執行時間快速上升

- O(n log n) 演算法：
  - Merge / Heap
  - 成長較平穩，效率明顯較佳

---

### 📌 結論

- 小資料（n < 30）：
  - 插入排序效率良好

- 大資料：
  - Merge Sort 最穩定
  - Heap Sort 空間效率佳

---

## 🧩 技術架構

- HTML5
- CSS3
- JavaScript（Vanilla）
- Chart.js（圖表分析）

---

## 🎨 UI 設計

- 深色科技風（Dark Mode）
- 霓虹藍紫配色
- Grid 背景（工程感）
- Hover 浮動動畫
- Dashboard 風格

---

## 📌 作業對應

本專案已完整符合課程要求：

- ✔ 五個排序法介紹
- ✔ 基本原理說明
- ✔ 複雜度分析
- ✔ 數據模擬
- ✔ 結果呈現（圖表）
- ✔ 結論分析

---

## 👨‍💻 作者

- Name: Brian95117  
- Project: Sorting Algorithm Visualization  

---

## 📄 License

MIT License