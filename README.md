# 113_CourseTopics

|姓名|負責範圍|
|----|-------|
|劉育盈|資料收集與系統整合|
|楊凱婷|設備操作與系統整合|
|林予捷|資料收集與設備操作|



# 甘特圖
```mermaid
gantt
    title 專案甘特圖
    dateFormat  YYYY-MM-DD
    section 規劃階段
    擬定專題名稱與目標        :done,    a1, 2024-010-01, 1d
    專題內容大綱與流程擬定        :active,  a2, after a1, 4d

    section 分析與設計階段
    需求與市場分析           :         a3, after a2, 17d
    任務分配與資源配置        :        a4, after a2, 70d
    系統介面/功能設計                :       a5, after a3, 10d

    section 開發階段
    後端程式開發與資料庫設計      :        a6, after a4, 30d
    前端設計與開發           :        a7, after a5, 25d

    section 測試與上線階段
    系統整合測試            :        a8, after a5, 20d
    系統上線準備與測試        :        a9, after a6, 25d
    正式上線與評估           :        a10, after a7, 25d
```