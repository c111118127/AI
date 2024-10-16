# 運用AI協助使用者送禮
組長 侯勝傑 C111118126

組員 溫琦竣 C111118127

組員 劉瓊穗 C111118116

專題內容概要：本專題將深入探討AI如何分析消費者行為與偏好，並將這些資訊與線上商城整合，提升購物體驗。透過數據挖掘和機器學習技術，商城可實現精準行銷，提供個性化推薦，最終達到提高轉換率和顧客滿意度的目的。
## 工作分配
### 侯勝傑
>資料收集與設備操作
### 溫琦竣
>資料收集與設備操作
### 劉瓊穗
>資料收集與設備操作

```mermaid
gantt
    title 專案進度甘特圖
    dateFormat  YYYY-MM-DD

    section 規劃階段
    訂定專題名稱與目標        :done,   des1, 2024-10-03,2024-10-08
    專題內容討論與確認        :done,   des2, 2024-10-08, 2024-10-13

    section 分析與設計階段
    需求與市場分析           :active, des3, 2024-10-13, 2024-10-20
    任務分配與資源配置        :        des4, 2024-10-20, 2024-10-25
    系統設計                :        des5, 2024-10-25, 2024-11-01

    section 開發階段
    後端程式開發             :        des6, 2024-11-01, 2024-11-15
    前端設計與開發           :        des7, 2024-11-15, 2024-11-29

    section 測試與上線階段
    系統整合測試            :        des8, 2024-11-29, 2024-12-13
    系統上線準備與測試        :        des9, 2024-12-13, 2024-12-20
    正式上線與評估           :        des10, 2024-12-20, 2024-12-24
```
![PERT圖](PERT圖.png)

graphviz
digraph {
 node[shape=record];
 rankdir="LR";
    no1 [label = "訂定專題名稱與目標 | 任務:1 | 開始:第1天 | 結束:第5天 | 需時:5天"]
    no2 [label = "專題內容討論與確認 | 任務:2 | 開始:第6天 | 結束:第10天 | 需時:5天"]
    no1->no2
    no3 [label = "需求與市場分析 | 任務:3 | 開始:第11天 | 結束:第17天 | 需時:7天"]
    no2->no3
    no4 [label = "任務分配與資源配置 | 任務:4 | 開始:第18天 | 結束:第22天 | 需時:5天"]
    no3->no4
    no5 [label = "系統設計 | 任務:5 | 開始:第23天 | 結束:第29天 | 需時:7天"]
    no4->no5
    no6 [label = "後端程式開發 | 任務:6 | 開始:第30天 | 結束:第43天 | 需時:14天"]
    no3->no6
    no4->no6
    no7 [label = "前端設計與開發 | 任務:7 | 開始:第44天 | 結束:第57天 | 需時:14天"]
    no3->no7
    no4->no7
    no8 [label = "系統整合測試 | 任務:8 | 開始:第58天 | 結束:第71天 | 需時:14天"]
    no6->no8
    no7->no8
    no9 [label = "系統上線準備與測試 | 任務:9 | 開始:第72天 | 結束:第78天 | 需時:7天"]
    no8->no9
    no10 [label = "正式上線與評估 | 任務:10 | 開始:第79天 | 結束:第82天 | 需時:4天"]
    no9->no10
}

}
```mermaid
graph TD
    A[禮物推薦機器人] --> B1[使用者輸入解析]
    A --> B2[資料庫搜尋與篩選]
    A --> B3[推薦算法]
    A --> B4[回應生成與互動]
    A --> B5[使用者體驗功能]

    B1 --> C1[關鍵字辨識]
    B1 --> C2[多輪對話管理]
    B1 --> C3[偏好學習]

    B2 --> C4[類別篩選]
    B2 --> C5[價格範圍篩選]
    B2 --> C6[品牌或節日標籤]

    B3 --> C7[基於規則推薦]
    B3 --> C8[機器學習優化]
    B3 --> C9[季節性推薦]

    B4 --> C10[推薦語句生成]
    B4 --> C11[選項比較表]
    B4 --> C12[圖片與連結嵌入]

    B5 --> C13[替代品建議]
    B5 --> C14[參數調整]
    B5 --> C15[匯出與分享]
```
