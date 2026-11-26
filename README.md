# 路邊野花的海拔地圖

本地植物學期末報告「路邊野花的隱形戰爭：利用全臺開放資料解析大花咸豐草與非入侵組的海拔消長」的 3D 互動網頁。

- 單一檔案 `index.html`：資料已內嵌為 JSON，Three.js 由 jsDelivr CDN 載入。
- 資料由 `06_web/06_prep_web_data.py` 從 03／04 分析結果產生，數字未經手動修改。
- 資料來源：TBN（2026-11-15 下載）、內政部 20 m DTM（2025）、OpenStreetMap。

## 11/26 更新
- 加入兩組同筆數（每期 53 筆、重抽 1,000 次）的 P95 對照，資料來自 `04_temporal/04_p95_control.csv`。
- 每個網格加入各時期公民科學紀錄數（iNaturalist、台灣中油生態地圖 APP、TBN-DP），可切換「柱色：公民科學比例」。
- 植物照片引用自 Wikimedia Commons（直接連結，未存入 repo）：大花咸豐草 [Starr 080601-5248](https://commons.wikimedia.org/wiki/File:Starr_080601-5248_Bidens_alba_var._radiata.jpg)（Forest & Kim Starr，CC BY 3.0）；小白花鬼針 [Fukufukurou](https://commons.wikimedia.org/wiki/File:Bidens_pilosa_var_minor_developing_flower_head_-_Fukufukurou.jpg)（授權見原頁）。照片載入失敗時只顯示文字。
- `og.png` 是分享連結時的預覽圖（1200×630）。
