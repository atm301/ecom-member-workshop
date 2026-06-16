# AI × LINE 官方帳號會員經營實戰工作坊 · 學員資源站

單頁學員輔助站（講師 何佳勳 / 小圭｜圭話行銷），依工作坊簡報製作。

## 提供學員

- 🏠 **開始**：3 個帶得走的成果、3 小時議程、互動投票（店家定位 / 最困擾）、開場提醒
- 🧰 **工具**：今日 6 個 AI 工具一鍵開啟（RFM / 會員等級 / Persona / 棄單挽回 / 節慶文案 / 多平台改寫）+ 5 組可複製提示詞 + 4 個串成企劃的延伸工具，全部外連 `ecom.atmarketing.tw`
- 📊 **重點**：5 大重點、流失漏斗、CAC/LTV/回購率三指標、RFM 8 大客群、分眾 4 種說法、黃金 7/30/90 複購流程
- ✍️ **實作**：動手實作 3 步驟、評分四指標、「我的企劃」6 工具完成度 checklist
- 🎟️ **方案**：免費 / Pro 月付 / 年繳定價、圭話會員專屬優惠
- 🎖️ **證明**：**輸入專屬編號（A1–A100）+ 名字** → 完成互動累積學習點數 → 達 70% 一鍵下載印著編號的**完課證明 PNG**

## 遊戲化（純前端，無後端）

登入編號、開啟工具（+12）、複製提示詞（+5）、逛分頁（+3）、互動投票（+5）都會累積點數，存在學員瀏覽器 `localStorage`（key：`lineworkshop_v1`），無個資外流風險。達總分 70% 解鎖完課證明。

## 每場可調設定（`index.html` 內 `CONFIG`）

```js
const CONFIG = {
  CERT_RATIO: 0.7,                          // 達總分幾成可領證明
  CERT_THRESHOLD: null,                     // 填數字可硬覆蓋；null = 依 CERT_RATIO 動態算
  COURSE_NAME: 'AI × LINE 會員經營實戰工作坊',
  LECTURER: '何佳勳（小圭）'
};
```

## 內建標配

- GA4（`G-RDJD1YVHR7`）+ Meta Pixel（`4979950938896019`）
- OG / Twitter Card / canonical / JSON-LD（Course）
- 長輩友善字級切換（標準 / 放大 / 特大）、行動裝置優先 RWD
- 工具連結若與現場展示網址不同，以講師現場公告為準

## 部署

純靜態單頁，直接託管 `index.html` 即可。建議路徑：`https://ecom.atmarketing.tw/workshop/`（與 canonical 一致），或 GitHub Pages。
