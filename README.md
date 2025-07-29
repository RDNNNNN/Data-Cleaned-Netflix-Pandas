# 項目：整理 Netflix 電影演員評分資料

## 分析目標

此資料分析的目的是，整理不同類型影視作品，如喜劇片、動作片、科幻片中，各演員出演作品的平均 IMDB 評分，從而找出各類型中的高評分作品演員

本項目的目的在於練習整理資料，以便得到可供下一步分析的資料

## 簡介

原始資料記錄了所有在 2022 年 7 月美國地區可觀看的 Netflix 電視劇及電影資料

資料包含兩個檔案：`titles.csv` 和 `credits.csv`

`titles.csv` 包含電影及電視劇相關信息，包括影視作品ID、標題、類型、描述、流派、IMDB（一個國外的在線評分網站）評分等 

`credits.csv` 包含超過 7 萬名出現在 Netflix 影視作品的導演及演員訊息，包括名字、影視作品 ID、人物名、演員類型（導演/演員）等

`titles.csv` 每列的意思如下：
- id：影視作品 ID
- title：影視作品標題
- show_type：作品類型，電視節目或電影
- description：簡短描述
- release_year：發布年份
- age_certification：適齡認證
- runtime：每集電視劇或電影的長度
- genres：流派類型清單
- production_countries：出品國家列表
- seasons：如果是電視劇，則是季數
- imdb_id：IMDB 的 ID
- imdb_score：IMDB 的評分
- imdb_votes：IMDB 的投票數
- tmdb_popularity：TMDB 的流行度
- tmdb_score：TMDB 的評分

`credits.csv` 每列的意思如下：
- person_ID：演員 ID
- id：參與的影視作品 ID
- name：姓名
- character_name：角色姓名
- role：演員類型，演員或導演
