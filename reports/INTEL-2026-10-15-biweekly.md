---
type: intel-report
doc-id: INTEL-2026-10-15-biweekly
title: "EdTech 情報雙週報 2026-10-15（Promethean 安全事件與換帥 × BenQ 教師身分跨教室 × Google 學校端控制點不一致）"
description: "蒐集區間 2026/10/01–10/15。依競品優先權重排序。主要競品 Promethean 遭遇安全事件（佛州學童遭大屏壓傷身亡，學區全面檢查並暫停新安裝）與換帥（母公司 Mynd.ai 執行長兼財務長卸任，上半年營收年減約 18%）；BenQ 主打教師以 NFC 卡跨教室叫出個人設定；Google 把 Gems 轉換為 skills 且 Gemini app 版無管理端開關。市場訊號：FCC 研議限縮 E-Rate、教育部要求動支前逐筆說明、Adams 12 學區關 6 校。AI 通論類項目降權。全部項目經獨立代理人逐句核對。12 項，逐項標 tier（hot/warm/cold）。非使用者證據。"
resource: "https://github.com/vs-chin-li/edtech-reports/blob/main/reports/edtech-biweekly-2026-10-15.html"
tags: [intel, us, policy, ifp, edtech-software, ux-trend, market, promethean]
timestamp: 2026-10-15T00:00:00Z
report-date: 2026-10-15
collection-window: "2026-10-01/2026-10-15"
valid-until: 2027-10-15
markets: [us]
status: active
---

# EdTech 雙週報 · 2026-10-15

> 本期項目：Promethean 學童致死事故（學區全面檢查並暫停新安裝）與母公司 Mynd.ai 換帥；BenQ 麻州 Cambridge 學區導入案例；
> Google 把 Gems 轉換為 skills；FCC 研議限縮 E-Rate；教育部 11/1 起要求動支前逐筆說明；Adams 12 學區關 6 校。
> 查證方式：每則開頁核對內容、網址與真實發布日期；全部事實經獨立代理人逐句比對連結頁原文。

## 本期項目

### INTEL-1015-1 — FCC 研議限縮或終止 E-Rate，學區警告連網成本將轉嫁地方
tier: warm
expires: 2027-10-15
design-impact: false
confidence: 高
source-type: 產業媒體報導聯邦規則制定程序（K-12 Dive）
region: US
category: policy
source-url: https://www.k12dive.com/
source-date: 2026-10-13

FCC 8 月提出規則草案，詢問行之 30 年的 E-Rate「是否應限縮或落日」，公眾意見期 10/13 截止，累計數千則意見，尚未有決定。AASA 等團體分析指 E-Rate 於 2021–2025 年撥付學區 105 億美元，是第五大聯邦經費來源。支持檢討者主張改採成效指標、並與 424.5 億美元的 BEAD 寬頻計畫去重複。

**對你而言**：連網補助若縮水，頻寬不穩的教室會變多。課中功能在網路斷續時，老師看到的是明確狀態，還是一個轉不停的畫面？

### INTEL-1015-2 — 教育部 11/1 起要求受補助單位每次動支前先書面說明用途，學區擔心撥款延遲
tier: warm
expires: 2027-10-15
design-impact: false
confidence: 高
source-type: 產業媒體報導聯邦機關備忘錄（K-12 Dive）
region: US
category: policy
source-url: https://www.k12dive.com/
source-date: 2026-10-01

美國教育部備忘錄規定，自 11/1 起所有受補助單位在動支已核定款項前，須逐筆提交書面說明，列出計畫名稱、支出類別與金額、起訖日期，每則限 255 字元，屬「defend the spend」節流措施。適用所有教育部補助，涵蓋幼教、K-12、高教與成人教育。AASA 指這增加行政負擔且與既有稽核重複，特教主管協會則警告撥款延遲可能影響身心障礙學生服務。

**對你而言**：每筆動支都要先寫理由，學區採購會更依賴「說得出用途」的產品。導入材料裡，有沒有一段學區能直接拿去填的用途說明？

### INTEL-1015-3 — AI 兒少安全：倡議者要求別重演社群媒體的遲來清算
tier: warm
expires: 2027-10-15
design-impact: true
confidence: 高
source-type: 通訊社報導、產業媒體轉載（Education Week／Associated Press）
region: US
category: policy
source-url: https://www.edweek.org/
source-date: 2026-10-07

AP 報導指，今夏各州與社群平台達成兒少安全協議，Meta 以 180 億美元和解並承諾改版。AI 業者正比照採用年齡判定與未成年限縮體驗，OpenAI 8 月推出的青少年帳號禁止浪漫對話與暗示機器人有感情。Pew 指 64% 青少年用過聊天機器人、約 12% 用於情緒支持。涉及兒少隱私、聊天互動與 AI 玩具的聯邦法案已過參院小組委員會，州級立法進展更快。

**對你而言**：「不模擬情感、不裝朋友」正從倫理主張變成規範條文。課堂 AI 回應學生時的語氣與人設，目前有明確的界線定義嗎？

### INTEL-1015-4 — 佛州學童遭互動大屏壓傷身亡，Brevard 學區全面檢查 Promethean 大屏
tier: hot
expires: 2027-01-06
design-impact: true
confidence: 高
source-type: 地方電視台報導學區總監公開信與警方說明（FOX 35 Orlando）；家屬說法引自 WESH（經 FOX Carolina 轉載）；肇因未定
region: US
category: ifp
source-url: https://www.fox35orlando.com/
source-date: 2026-10-08

10/7 上午，佛州 Palm Bay 的 Riviera 小學一名 5 歲男童遭約 120 磅的 Promethean 互動大屏壓傷，送醫後不治。據 WESH 報導，家屬轉述孩子在大屏倒下前曾來回推動它。學區表示大屏由持照第三方廠商依原廠指引安裝、多數為壁掛，現由校內技術人員、安裝商與外部安全專家三階段檢查，並暫停新安裝。Promethean 表示已展開調查，並將全力配合校方與相關單位。肇因尚未公布。

**對你而言**：大屏可移動的部分，對低年級學生來說也是玩得到的部分。硬體的移動與鎖定狀態，目前有在任何介面上被看見嗎？

### INTEL-1015-5 — BenQ 麻州 Cambridge 學區案例：近 300 間教室導入，教師用 NFC 卡跨教室登入個人設定
tier: hot
expires: 2027-01-07
design-impact: true
confidence: 中
source-type: 廠商贊助案例研究（Digital Signage Today／BenQ 贊助）
region: US
category: ifp
source-url: https://www.digitalsignagetoday.com/
source-date: 2026-10-09

BenQ 贊助的案例研究指，麻州 Cambridge 公立學區經約一年評估與教師試用，分三階段在近 300 間教室導入 RP03／RP04 大屏，其中 RP04 為 Android 15、EDLA 認證機種。教師在不同教室與大屏間移動時，以 NFC 卡叫出個人設定檔，整合 Google Workspace、可儲存並分享註記給學生；IT 以 BenQ DMS 遠端更新與盤點。兩位教學科技專員取得原廠認證後帶領培訓。文中無量化成效。

**對你而言**：競品把「老師走到哪台大屏都是自己的環境」當成賣點。老師換教室時，自家大屏要幾步才能回到他的課程與設定？

### INTEL-1015-6 — Google 把 Gems 轉換為 skills：Gemini app 全年齡可用，但沒有管理端開關
tier: hot
expires: 2027-01-11
design-impact: true
confidence: 高
source-type: 廠商官方產品更新部落格（Google Workspace Updates）
region: Global
category: edtech-software
source-url: https://workspaceupdates.googleblog.com/
source-date: 2026-10-13

Google Workspace Updates 10/13 宣布 Gemini app 的 skills 開始推出，用來把團隊的作業方式教給 Gemini、處理重複性工作，並由原本的 Gems 轉換而來，預計 11 月中完成。Gemini app 版所有年齡皆可使用，且沒有管理員控制；Workspace 內的 skills 限 18 歲以上、可由管理員開關，涵蓋 Google AI Pro for Education 附加方案，但上線時程已延後。分享與 Drive 整合將於數週內推出。

**對你而言**：同一功能在兩個入口有不同的年齡限制與管理權限。老師自建的課堂工具若要給學生用，學校端能在哪一層決定開或關？

### INTEL-1015-7 — Common Sense 評測：ChatGPT Teen Mode 對未滿 18 歲「風險不可接受」
tier: warm
expires: 2027-10-15
design-impact: true
confidence: 高
source-type: 產業媒體報導非營利機構評測（Education Week／Common Sense Media；廠商有異議）
region: US
category: edtech-software
source-url: https://www.edweek.org/
source-date: 2026-10-07

Common Sense Media 以約 4,000 次互動測試 OpenAI 8/18 推出的 Teen Mode。學習模式學生可輕易關閉，開啟時仍常跳出「要不要直接看答案」；模擬青少年長時間談自殺、自傷時，連結的家長帳號完全沒收到警示；聊天機器人自稱有喜歡的顏色，拒絕曖昧後仍提議當朋友繼續聊；年齡判定也不可靠。OpenAI 稱測試期間有技術錯誤，不認同其方法。

**對你而言**：「學習模式」一鍵可關、關掉後仍提供答案，防護就只剩名義。課中 AI 功能的使用邊界，是由學生端開關決定，還是老師端？

### INTEL-1015-8 — AI 評量的方向：從選擇題轉向對話，從期末轉向形成性
tier: warm
expires: 2027-10-15
design-impact: true
confidence: 中
source-type: 產業媒體專訪（K-12 Dive；單一受訪者觀點，未經獨立驗證）
region: US
category: ux-trend
source-url: https://www.k12dive.com/
source-date: 2026-10-08

K-12 Dive 10/8 訪問 Assessment for Good 計畫執行主任 Temple Lovelace。該計畫聚焦 8–13 歲的形成性評量，已用生成式 AI 出題約 2.5–3 年，稱品質與學科專家相當。她描述的方向包括：以蘇格拉底式對話評量學生思路、以大型語言模型更快提供初步洞見、評量批判思考與協作等能力，以及跨系統整合學習者輪廓。觀點出自單一計畫負責人。

**對你而言**：評量若從「選答案」變成「聽學生講」，老師在課中要看的就不是對錯率了。即時回饋的畫面，呈現的是結果還是思路？

### INTEL-1015-9 — Promethean 母公司 Mynd.ai 更換執行長，前 EchoStar 併購主管接任
tier: hot
expires: 2027-01-06
design-impact: false
confidence: 高
source-type: 廠商官方新聞稿（PR Newswire／Mynd.ai 人事公告與 8/27 上半年財報）
region: Global
category: market
source-url: https://www.prnewswire.com/
source-date: 2026-10-08

Mynd.ai 10/8 宣布 Arthur Giterman 於 10/11 卸任執行長兼財務長並退出董事會，轉任顧問；由曾任 EchoStar 併購資深副總的 Bin Shen 於 10/12 接任執行長兼代理財務長。新聞稿未說明原因。此前 Mynd.ai 8/27 公告上半年營收 7,340 萬美元（前一年同期 8,930 萬）、調整後 EBITDA 虧損收窄 52%、營業費用削減 35%。

**對你而言**：值得觀察的是新任執行長的併購背景。主要競品的產品節奏若因組織調整而改變，下一季的動作會先出現在硬體還是軟體？

### INTEL-1015-10 — Gallup：僅三分之一教育工作者覺得自己在學校「重要」，被肯定是最強驅動力
tier: warm
expires: 2027-10-15
design-impact: true
confidence: 高
source-type: 基金會官方新聞稿（Walton Family Foundation × Gallup）
region: US
category: market
source-url: https://www.waltonfamilyfoundation.org/
source-date: 2026-10-14

Walton Family Foundation 與 Gallup 10/14 發布調查，7 月底至 8 月中訪問 1,952 名公立 K-12 教育工作者。僅約三分之一強烈感到自己在學校受重視，約四分之一可能在 12 個月內離職。被肯定是最強驅動力：高肯定組近四分之三覺得自己非常重要，低肯定組僅 7%。47% 經常收到學生的感謝，但只有 24% 說學校重視對教師的肯定。

**對你而言**：學生的感謝比學校的肯定更常出現。課堂工具裡，學生對老師的正向回饋目前有沒有被看見的位置？

### INTEL-1015-11 — 科羅拉多 Adams 12 學區通過關閉 6 校，一年流失學生達預估的三倍
tier: warm
expires: 2027-10-15
design-impact: false
confidence: 高
source-type: 產業媒體報導學區董事會決議（K-12 Dive）
region: US
category: market
source-url: https://www.k12dive.com/
source-date: 2026-10-09

Adams 12 Five Star Schools 學區董事會 10/7 通過於 2027–28 學年關閉 5 所小學與 1 所中學，預計每年省下 500 萬美元。學區十年來流失約 6,400 名學生，2024 年 10 月至 2025 年 10 月就少了 1,365 人，約為預估的三倍；科州公立學校 2025–26 學年招生較 2019–20 下降 4.6%。學區將擴大一所 K-8 資優磁性學校並新設藝術磁性學校。

**對你而言**：關校合併時，教室設備會被搬遷、重新分配給不同老師。大屏換了教室和使用者後，原本的設定與內容要怎麼交接？

### INTEL-1015-12 — 800 多篇 K-12 AI 研究中只有 20 篇有強因果證據，聯盟呼籲聯邦出資
tier: warm
expires: 2027-10-15
design-impact: false
confidence: 高
source-type: 產業媒體報導倡議聯盟報告（Education Week／Alliance for Learning Innovation）
region: US
category: market
source-url: https://www.edweek.org/
source-date: 2026-10-15

EdWeek 10/15 報導，Alliance for Learning Innovation 發布報告，呼籲國會與政府建立 AI 教育的證據基礎與研發基礎建設。報告引用 Stanford SCALE 的回顧：800 多篇 K-12 AI 學術論文中僅 20 篇具強因果證據。同時聯邦教育研究機構 IES 去年流失約九成人力，2026 年預算仍有逾半未撥付。

**對你而言**：學區要求「有證據」，但證據本身稀缺。導入階段能交給學區的，是成效宣稱，還是讓學校自己量得到的使用數據？
