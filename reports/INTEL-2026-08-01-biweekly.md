---
type: intel-report
doc-id: INTEL-2026-08-01-biweekly
title: "EdTech 情報雙週報 2026-08-01（ISTE 年會後發布空窗：角色感知首頁 × E-Rate 存廢 × 州級 AI 素養）"
description: "蒐集區間 2026/07/16–08/01。主軸：Google Classroom 角色感知首頁改版、FCC E-Rate $2.5B 補助存廢之戰、州級 AI 素養指引累積；適逢 ISTE 年會後發布空窗，5 項，逐項標 tier（hot/warm/cold）。非使用者證據。"
resource: "https://github.com/vs-chin-li/edtech-reports/blob/main/reports/edtech-biweekly-2026-08-01.html"
tags: [intel, us, policy, edtech-software, ux-trend, market]
timestamp: 2026-08-01T00:00:00Z
report-date: 2026-08-01
collection-window: "2026-07-16/2026-08-01"
valid-until: 2027-08-01
markets: [us]
status: active
---

# EdTech 情報雙週報 · 2026-08-01

> 主軸：適逢 ISTE 年會後的發布空窗，項目數少於平常、不硬湊。本期落在「角色感知首頁」（Google Classroom 改版）、「E-Rate 存廢」（FCC 檢討）與「州級 AI 素養」（Michigan 指引）三條線。
> IFP 互動大屏本期無重大更新（本季發表集中在 Bett 2026 與 ISTELive 26，已於前兩期收錄）。
> 查證方式：五大面向逐層掃描近 14 天（一手/權威層 → 產業媒體層 → 展會/報告層），每則開頁核對內容、
> 網址與真實發布日期，並標信心等級與來源類型。開頁查證後排除或校正：Illinois 400 頁指引、Anthropic
> Claude for Teachers、ClassDojo 全校溝通套件三則已於上期收錄；SchoolAI「Dot AI／PowerUps」實際為
> 2025-07-16 舊聞；ExploreK12 品牌整併屬上期窗口；myViewBoard/ClassSwift/AirSync 本期查無窗口內可核對新版；
> Microsoft M365 Education 為 6/24 發布、7 月僅既定分批上線；ED SPPO 夏季 webinar（8/12 起）屬窗口後。

## 本期項目

### INTEL-0801-1 — Google Classroom：角色感知首頁——教師／學生／管理者各自儀表板
tier: hot
expires: 2026-10-19
design-impact: true
confidence: 高
source-type: 廠商官方（Google Workspace Updates，並經 7/24 週報再確認）
region: US/Global
category: edtech-software
source-url: https://workspaceupdates.googleblog.com/
source-date: 2026-07-21

7/21 公告、7/27 起全球分批上線的 Classroom 首頁改版，把原本散落的工具收攏為一個依角色動態呈現的中央入口：教師端有「學生作業互動洞察／指派完成度追蹤／功能聚光燈」；學生端有「Enrolled」課程視圖與「Due soon」模組（列出未來 7 天內、最多 5 筆待交作業）；管理者端看參與度指標。模組可收合以自訂版面。符合資格的學生另會看到「Learn with Gemini」（依作業脈絡觸發學習動作選單）與「Class learning tools」。跨所有 Workspace 版本與個人帳號，影響逾 1.5 億使用者。

**對你而言**：Google 把首頁改成「先分角色、再談功能」，並把待辦與洞察推到最前面。自家課堂軟體與大屏首頁，老師一進來看到的是「今天要幹嘛」（待交、待批、班級狀況），還是一排功能圖示？學生端有沒有一個等同「Due soon」的收斂清單？AI 入口是依當下作業脈絡浮現，還是固定埋在選單裡等人去找，值得一問。

### INTEL-0801-2 — 本期訊號：「角色決定介面」從分權設定走上首頁
tier: warm
expires: 2027-08-01
design-impact: true
confidence: 中
source-type: 推論（以 Google 7/21 一手發布為主，銜接前期教師掌控權觀察）
region: US
category: ux-trend
source-url: https://workspaceupdates.googleblog.com/
source-date: 2026-07-21

過去「角色」多半只影響權限與可見選單；本期 Google Classroom 改版把它推進一步——同一個首頁，教師看到班級洞察與待批，學生看到自己的待交清單，管理者看到參與度指標，連 AI 模組都只對符合資格者出現。這與上期「教師掌控權前景化」（逐作業 AI 分級、教師先審閱 AI 產出）是同一條線的延伸：介面不再是一套版面配不同權限，而是依角色重組內容優先序。

**對你而言**：自家介面裡，老師與學生看到的是不是同一套版面、只差幾個按鈕能不能點？若是，哪些內容其實該依角色重排優先序。另一個值得一問的是——教師端有沒有一處能看到「學生在 AI 上做了什麼」的軌跡；這在近期採購對話裡出現得愈來愈頻繁。

### INTEL-0801-3 — FCC E-Rate 全面檢討：$2.5B 校園連網補助面臨縮限或取消，反對動員擴大
tier: warm
expires: 2027-08-01
design-impact: false
confidence: 高
source-type: 產業媒體＋官方（Broadband Breakfast 報導 FCC NPRM 進度）
region: US
category: policy
source-url: https://broadbandbreakfast.com/
source-date: 2026-07-17

FCC 於 6/25 通過近年最全面的 E-Rate 檢討 NPRM，攤開「是否縮限、限定地理區、或整個取消」等選項，並一併檢視學生螢幕時間、內容過濾與顧問監管。E-Rate 補助逾 100,000 所學校、11,000 間圖書館的寬頻。7/17 進度：SHLB Broadband Coalition 推出倡議工具包與意見撰寫指引，ALA 已促成逾 9,000 次國會聯繫；執行長 Joey Wender 稱若 FCC 得逞「將在全國學校與圖書館預算炸出一個大坑」。正式意見期於刊登聯邦公報後 60 天截止、回覆意見再加 30 天，截止日尚未公布。

**對你而言**：聯邦端對校園連網補助的存續質疑升溫，學區預算可能連帶收縮。自家哪些功能是「一斷網就不能用」的？在低頻寬或訊號不穩的教室裡，投放與雲端協作會降級到什麼程度、老師看不看得懂當下發生什麼事——這條韌性底線值得先摸清楚，而不是等採購端來問。

### INTEL-0801-4 — Michigan 發布全州 K-12 AI 指引：聚焦學生 AI 素養與在地規劃
tier: warm
expires: 2027-08-01
design-impact: false
confidence: 高
source-type: 公共媒體引述官方（Michigan Public 引 MDE）
region: US
category: policy
source-url: https://www.michiganpublic.org/
source-date: 2026-07-14

Michigan 教育廳 7/14 與非營利 Michigan Virtual 合作發布全州 AI 指引（上期 7/15 截稿後發布，本期補收），聚焦「學生該理解的 AI」——演算法、資料與運算思維，並強調公平、負責任的導入與長期規劃；內含供學區在地討論的題組。發言人 Ken Coleman 表示後續將加入「依年齡分層的學習計畫」。此為繼 Ohio 要求各學區須於 2026-07-01 前訂定 AI 政策、Illinois 發布 400 頁指引之後，州級指引持續累積（全美已逾 30 州）的一環。

**對你而言**：州級指引正把 AI 從「校務規範」延伸成「課程期待」——學生要看得懂 AI 怎麼運作。面向學生的 AI 功能，能不能被老師直接拿來當教材討論？例如產出物有沒有可指認的依據或來源，讓老師能帶著學生看「它為什麼這樣答」，而不只是給一個結果，值得觀察。

### INTEL-0801-5 — Digital Promise $8M 開源 K-12 AI 數學輔導基礎建設 RFP 於 7/31 截止收件
tier: hot
expires: 2026-10-29
design-impact: false
confidence: 中
source-type: 產業媒體＋一手 RFP（EdTech Innovation Hub 報導 Digital Promise RFP）
region: US
category: market
source-url: https://www.edtechinnovationhub.com/
source-date: 2026-07-31

Gates 基金會支持、Digital Promise 主辦的 K-12 AI Infrastructure Program，徵求「開源、教育專用的 AI 模型基礎建設」（模型權重、訓練碼、資料集、評測工具、文件），採寬鬆授權（內容 CC BY 4.0、軟體 Apache 2.0），不資助特定廠商產品。RFP 於 6/4 開放、2026-07-31 截止收件（本期窗口內里程碑），計畫 11 月起跑、為期 30–36 個月，僅選一隊。要求申請者具 LLM 經驗、同儕審查發表，以及以真實學生資料的部署／評測經驗，並附學生資料保護與偏見緩解計畫。模型將以「效度、信度、公平、安全、成效、成本」受測。

**對你而言**：資助方把「效度、公平、安全、成效」直接寫成驗收條件，這套語彙很可能一路傳導到學區的採購問卷。若校方拿這幾項來問自家的 AI 功能，現在拿得出什麼？以及介面上要不要、如何向老師揭露 AI 的能力邊界與已知限制，值得思考。
