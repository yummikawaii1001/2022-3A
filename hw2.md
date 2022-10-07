![PERT](關鍵路徑.png "")

```mermaid
gantt
    title A Gantt Diagram

    研擬計畫           :a1 ,2022-01-01, 1d
    任務分配           :a2 ,after a1 ,4d
    取得硬體           :a3 ,after a2 , 17d
    程式開發           :a4 ,after a3, 70d
    安裝軟體           :a5 ,after a4 ,10d
    程式測試           :a6 ,after a5 ,30d
    撰寫使用手冊       :a7 ,after a6 ,25d
    轉換檔案           :a8, after a7,20d
    系統測試           :a9, after a8,25d
    使用者訓練         :a10 ,after a9,20d
    使用者測試         :a11 ,after a10,25d
    
```
