# Cool GitHub Radar

定期蒐集那些讓人產生「居然有人把這個做出來」感覺的 GitHub 專案。

特別關注技術奇觀、數位自主、工程師文化、資安與側通道、復古硬體改造、網路文化、民間教科書，以及真正有新意的 AI 工具。

## 瀏覽推薦

- [2026 年 8 月](recommendations/2026/2026-08.md)

## 資料與規則

- [專案總表](data/projects.json)：已知與已分享專案的唯一資料來源，用於嚴格去重。
- [偏好設定](data/preferences.json)：依使用者回饋持續調整的口味模型。
- [分類字典](config/categories.json)：統一分類 ID、名稱及定義。
- [搜尋策略](config/search-strategy.md)：每次搜尋、評分、排除與輸出的工作規則。
- [資料結構 Schema](schemas/project.schema.json)：驗證專案總表格式。

## 專案狀態

- `seed`：使用者已經知道或主動提供，不得當成新推薦。
- `shared`：雷達已正式推薦。
- `rejected`：曾評估但不符合口味或品質門檻。
- `follow_up`：曾推薦專案的重大後續，不視為全新推薦。

目前已匯入 26 個 seed repositories。
