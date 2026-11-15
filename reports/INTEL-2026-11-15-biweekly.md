---
type: intel-report
doc-id: INTEL-2026-11-15-biweekly
title: "EdTech 情報雙週報 2026-11-15（Microsoft Classroom × Google 學生帳號 AI 預設關閉 × Clever 學生 MFA）"
description: "蒐集區間 2026/11/03–11/15。依競品優先權重排序。本期項目：Microsoft Classroom 推出；Google 將 K-12 學生帳號 Search 與 Gemini 預設關閉及芝加哥抗議；Clever 學生多因素驗證與個別學生螢幕時間；Google Classroom Guided Learning；學校配發 Chromebook 訴訟；澳洲數位排毒；美國教育部補助規則；Anthropic 與教師工會隱私協議；ViewSonic 臺灣教育科技展；Fordham 學生科技誤用調查；Stanford AI 學習研究回顧；Microsoft 免費 A1 退場；Mynd.ai ADS 比率變更；Boxlight 股東會；SETDA 州教育科技趨勢；St. Louis 關校。AI 通論類項目降權。全部項目經獨立代理人逐句核對。16 項，逐項標 tier（hot/warm/cold）。非使用者證據。"
resource: "https://github.com/vs-chin-li/edtech-reports/blob/main/reports/edtech-biweekly-2026-11-15.html"
tags: [intel, us, apac, policy, ifp, edtech-software, ux-trend, market, promethean, microsoft, google, clever]
timestamp: 2026-11-15T00:00:00Z
report-date: 2026-11-15
collection-window: "2026-11-03/2026-11-15"
valid-until: 2027-11-15
markets: [us, apac]
status: active
---

# EdTech 雙週報 · 2026-11-15

> 本期項目：Microsoft Classroom；Google K-12 學生帳號 Search 與 Gemini 預設關閉、芝加哥抗議；Clever 學生 MFA 與螢幕時間；Google Classroom Guided Learning；Chromebook 訴訟；
> 澳洲數位排毒；美國教育部補助規則；Anthropic 與教師工會協議；ViewSonic 臺灣教育科技展；Fordham 調查；Stanford 研究回顧；Microsoft 免費 A1 退場；Mynd.ai ADS 比率變更；Boxlight 股東會；SETDA 報告；St. Louis 關校。
> 查證方式：每則開頁核對內容、網址與真實發布日期；全部事實經獨立代理人逐句比對連結頁原文。

## 本期項目

### INTEL-1115-1 — Microsoft 宣布獨立的 Microsoft Classroom，整合作業、成績與 OneNote 課堂筆記本，也能透過 LTI 在既有 LMS 內使用
tier: hot
expires: 2027-02-09
design-impact: true
confidence: 高
source-type: 官方產品部落格（Microsoft Education Blog）
region: Global
category: edtech-software
source-url: https://techcommunity.microsoft.com/
source-date: 2026-11-11

Microsoft 11/11 公告，Classroom 是獨立的 Microsoft 365 教學體驗，不取代 Teams for Education 或 Microsoft 365 LTI。它整合 Assignments、Classwork、Grades、OneNote Class Notebook、Learning Accelerators 與 Insights，AI 備課工作區 Teach 也會放進來；也可透過 LTI 在既有 LMS 內使用。預覽版預計 2027 年初。

**對你而言**：競品把教學流程集中到一個入口。老師從 LMS 進到自家課中互動時，需要另外登入或重建班級嗎？

### INTEL-1115-2 — Google 將對 K-12 學生帳號預設關閉 Search 與另兩項 AI 功能，需管理員開啟；芝加哥家長與教育者到 Google 辦公室抗議
tier: warm
expires: 2027-11-15
design-impact: true
confidence: 高
source-type: 產業媒體報導（K-12 Dive）；芝加哥抗議引自 The 74 轉載 Chalkbeat
region: US
category: policy
source-url: https://www.k12dive.com/
source-date: 2026-11-05

K-12 Dive 報導，Google 將對 K-12 學生帳號預設關閉 Search 與另兩項 AI 功能，理由是學校要求對學生使用 AI 服務有更多控制，但何時開始仍不明；管理員可重新開啟 Search、Gemini 等服務。批評者稱這是「敵意的最後通牒」。據 The 74 轉載 Chalkbeat，芝加哥公立學校已封鎖學生使用生成式 AI；Google 表示禁用 AI 的學校將無法使用搜尋，約 30 人 11/11 到 Google 芝加哥辦公室抗議。

**對你而言**：被學區關掉的功能，連帶影響了不相干的功能。自家某項功能被管理員關閉時，學生畫面上會怎麼呈現？

### INTEL-1115-3 — Clever 宣布學生可用徽章、圖片、PIN 等八種方式做多因素驗證，並可量測每位學生的螢幕使用時間
tier: hot
expires: 2027-02-11
design-impact: true
confidence: 高
source-type: 官方公司部落格（Clever）
region: US
category: edtech-software
source-url: https://www.clever.com/
source-date: 2026-11-13

Clever 11/13 公告 NEXT@ Clever 產品更新：Classroom MFA 提供八種適合學生的驗證方式，如 Clever Badges、登入圖片與 PIN；自 2026 年 11 月起，管理員可量測到個別學生的實際螢幕時間；學區可限制分享給 1,250 多個應用夥伴的 SIS 欄位。公告也提到，Microsoft 將自 2027/2/1 起取消 Entra ID 的語音與簡訊登入碼。

**對你而言**：Clever 為學生設計低齡也能用的驗證方式。最低年級的學生加入自家課中互動時，能不靠老師自己完成嗎？

### INTEL-1115-4 — Google Classroom 可在作業中加入 Guided Learning，教師可看個別學生對話紀錄
tier: hot
expires: 2027-02-02
design-impact: true
confidence: 高
source-type: 官方產品公告（Google Workspace Updates）；即時洞察引自 Google 官方部落格
region: Global
category: edtech-software
source-url: https://workspaceupdates.googleblog.com/
source-date: 2026-11-04

Google Workspace 11/4 公告：教師可把 Guided Learning 加進 Google Classroom 的任何作業，並可查看個別學生的對話紀錄；適用 Education Fundamentals、Standard、Plus，教師與學生須在 Gemini 設為開啟的群組或 OU 內。Google 官方部落格 11/3 表示 Guided Learning 即日起在 Google Classroom 全球上線，並提供即時洞察，找出全班可能需要協助之處。

**對你而言**：競品給老師全班卡關的即時視角。ClassSwift 的即時回饋在大屏上，老師一眼看得出哪題該停下來講嗎？

### INTEL-1115-5 — 家長提告：指 13 歲女兒用學校配發 Chromebook 與 Google 搜尋 AI 模式對話後陷入心理危機
tier: hot
expires: 2027-02-04
design-impact: true
confidence: 中
source-type: 產業媒體報導訴訟（Education Week）；內容為原告主張，尚未經法院認定
region: US
category: policy
source-url: https://www.edweek.org/
source-date: 2026-11-06

EdWeek 報導，訴訟 11/4 在加州 Santa Clara 郡高等法院提出，原告律師稱這是第一件針對 Google Chromebook 的案件。學生用學校配發的 Chromebook 使用 Google 搜尋由 Gemini 驅動的 AI 模式；據訴狀，她透過與 AI 聊天機器人的對話，深信自己有心理疾患；事情經由學校的第三方監控軟體發現。報導並提到 Google Classroom 已向所有年齡的 K-12 學生開放 Gemini 聊天機器人。

**對你而言**：訴訟對象是學校配發的裝置。自家學生端若出現開放式 AI 回應，老師能即時看到學生收到了什麼嗎？

### INTEL-1115-6 — 澳洲教育部長會議同意全國「數位排毒」：成立專責小組，限制小學使用生成式 AI
tier: warm
expires: 2027-11-15
design-impact: false
confidence: 中
source-type: 地區媒體報導部長會議決議（Region）；官方公報 PDF 無法開啟
region: APAC
category: policy
source-url: https://region.com.au/
source-date: 2026-11-06

Region 報導，澳洲各州教育部長同意成立 Australian Schools Digital Detox Taskforce 推動改革，並限制小學學生使用生成式 AI，以及學生在中學評量中使用生成式 AI。五年級 NAPLAN 寫作測驗將自 2028 年改回紙本；另設 Teaching and Learning Commission，作為負責全國課綱的單一機構。

**對你而言**：規範對象是學生使用的數位工具。全班共看大屏的課中互動，在這類規範下會被歸為學生螢幕時間嗎？

### INTEL-1115-7 — 美國教育部改寫補助規則，學區擔憂經費不穩定
tier: warm
expires: 2027-11-15
design-impact: false
confidence: 高
source-type: 教育非營利媒體報導（The 74）
region: US
category: policy
source-url: https://www.the74million.org/
source-date: 2026-11-09

The 74 報導，教育部刪減 12 州近 1.7 億美元的社區學校補助；11/1 生效的一項全聯邦政府規定，要求受補助者每次請款都提出書面理由。另一項提案允許「為了便利」中途取消補助，收到逾 5,500 則意見，23 位州檢察長反對。

**對你而言**：補助可能中途中止，學區採購會更謹慎。學區從試用走到正式採購時，自家產品能提供哪些使用數據？

### INTEL-1115-8 — Anthropic 與教師工會簽訂學生 AI 隱私協議，由學校決定資料保存與刪除
tier: hot
expires: 2027-02-08
design-impact: false
confidence: 高
source-type: 產業媒體報導（K-12 Dive）
region: US
category: policy
source-url: https://www.k12dive.com/
source-date: 2026-11-10

K-12 Dive 報導，這份具法律約束力的協議條款，將適用於 Anthropic 與學區的既有合約；學生與教育者資訊僅能用於經授權的教育目的，由學校控制資料保存多久與何時刪除。AFT 主席 Weingarten 稱這離產業標準更近一步。

**對你而言**：協議把保存期限與刪除權交給學校。學區 IT 在自家管理端找得到設定保存期限與刪除資料的地方嗎？

### INTEL-1115-9 — ViewSonic 在 2026 臺灣教育科技展展出 myViewBoard AI 教材製作與大型 LED 案例
tier: hot
expires: 2027-02-10
design-impact: false
confidence: 高
source-type: 自家官方新聞稿（ViewSonic 台灣）
region: APAC
category: ifp
source-url: https://www.viewsonic.com/
source-date: 2026-11-12

ViewSonic 11/12 新聞稿：於臺北世貿一館 B822 攤位展出，首度公開展示 myViewBoard 全新 AI 輔助教材製作與學習分析功能，系統可自動生成符合 myViewBoard 應用的 OLF 格式教材。案例包括東海大學導入 294 吋 All-in-One LED、臺大體育館以 231 吋 All-in-One LED 取代手動計分板。

**對你而言**：AI 把既有教材轉成統一格式。老師打開轉好的教材時，看得出哪些頁面是 AI 生成或改寫的嗎？

### INTEL-1115-10 — Fordham 調查：逾四分之三高中生承認上課時間誤用科技，三分之二說學校裝置可開 YouTube
tier: warm
expires: 2027-11-15
design-impact: true
confidence: 高
source-type: 產業媒體報導全國調查（K-12 Dive／Fordham Institute）
region: US
category: ux-trend
source-url: https://www.k12dive.com/
source-date: 2026-11-11

K-12 Dive 報導 Fordham Institute 調查：略高於四分之三的高中生表示在上課時間誤用科技；62% 表示超過一半的課堂時間在用學校配發裝置；三分之二表示學校裝置可以開 YouTube。手機全面禁用時，學生使用社群媒體的可能性最低。

**對你而言**：學生在學校裝置上分心很常見。課中把內容推到學生裝置時，老師看得出誰已離開課堂畫面嗎？

### INTEL-1115-11 — Stanford 回顧 52 項研究：AI 用來支援學習比用來完成作業效果好
tier: warm
expires: 2027-11-15
design-impact: false
confidence: 高
source-type: 產業媒體報導研究回顧（Education Week）
region: US
category: ux-trend
source-url: https://www.edweek.org/
source-date: 2026-11-10

EdWeek 報導 Stanford 研究者分析 52 項隨機對照與準實驗研究：學生把 AI 用於學習支援，學習成效通常優於用 AI 完成作業；至少一項研究發現教師使用 AI 會降低學生的動機與信心。52 項研究中只有 10 項以美國 K-12 學生或教育者為對象。

**對你而言**：差別在 AI 幫學生想還是幫學生做。自家的 AI 功能，屬於哪一種？

### INTEL-1115-12 — Microsoft 將退場免費的 Office 365 A1，Classroom 只放在付費 A2–A7 版本
tier: warm
expires: 2027-11-15
design-impact: true
confidence: 高
source-type: 產業媒體報導（EdTech Innovation Hub）；方案細節引自 Microsoft Learn 官方文件
region: Global
category: market
source-url: https://www.edtechinnovationhub.com/
source-date: 2026-11-11

EdTech Innovation Hub 報導，免費 A1 將在 2028/1/1 以後的首次續約時退場；Classroom 將包含在付費的 Microsoft 365 Education A2、A3、A5、A7。Microsoft Learn 頁面寫明，免費學生方案不含 Exchange Online、SharePoint Online 與 Teams；A2 自 2026/12/1 起正式提供。

**對你而言**：學區可能改用不含 Teams 與郵件的免費方案。自家依賴 Microsoft 帳號的登入與分享流程，在這種方案下還走得通嗎？

### INTEL-1115-13 — Promethean 母公司 Mynd.ai 將 ADS 比率從 1:10 改為 1:75
tier: hot
expires: 2027-02-04
design-impact: false
confidence: 高
source-type: 公司新聞稿（PR Newswire）
region: US
category: market
source-url: https://www.prnewswire.com/
source-date: 2026-11-06

Mynd.ai 11/6 新聞稿：ADS 比率將從 1 ADS 代表 10 股普通股改為代表 75 股，效果等同 1 比 7.5 的 ADS 反向分割；新聞稿寫預計 2027/12/7 前後生效。ADS 仍在 NYSE American 以「MYND」交易，普通股不受影響，持有人無須採取行動。新聞稿未說明變更原因。

**對你而言**：這是主要競品母公司的資本動作，新聞稿未提產品。後續是否牽動 Promethean 的產品或通路，值得在下期持續觀察。

### INTEL-1115-14 — Clevertouch 母公司 Boxlight 股東通過各項提案，董事會決定不改名
tier: hot
expires: 2027-02-10
design-impact: false
confidence: 高
source-type: 公司新聞稿（SEC 8-K 附件 99.1）
region: US
category: market
source-url: https://www.sec.gov/
source-date: 2026-11-12

Boxlight 11/12 新聞稿（SEC 8-K 附件）：股東在特別會議通過各項提案，但董事會決定不進行更名；董事會尚未決定是否、何時、以何比率進行反向分割。公司預期第二批籌資毛額 200 萬美元，並可開始動用最高 1,500 萬美元的股權信用額度。Nasdaq 聽證小組 9 月認定其已恢復合規。

**對你而言**：大屏競品仍在籌措營運資金。學區比較大屏廠商時，看得到各家軟體更新與支援年限嗎？

### INTEL-1115-15 — SETDA《State EdTech Trends Report》：53% 州已發布 AI 工具採購指引
tier: warm
expires: 2027-11-15
design-impact: false
confidence: 高
source-type: 產業媒體報導全國調查（EdWeek Market Brief／SETDA）
region: US
category: market
source-url: https://marketbrief.edweek.org/
source-date: 2026-11-05

EdWeek Market Brief 報導 SETDA 第五份州教育科技趨勢報告：各州連續第二年把 AI 列為首要優先；53% 的州已發布採購 AI 工具的指引，去年約 40%；62% 指專業發展是教師最大未滿足的科技需求，上升 15 個百分點。已有採購指引的州中，約八成納入實證導向的品質指標，前一年為 45%。

**對你而言**：過半州已有 AI 採購指引。學區審查自家 AI 功能時會問的問題，在產品頁上找得到答案嗎？

### INTEL-1115-16 — St. Louis 學區投票通過關閉 9 所學校
tier: hot
expires: 2027-02-10
design-impact: false
confidence: 高
source-type: 產業媒體報導學區決議（K-12 Dive）
region: US
category: market
source-url: https://www.k12dive.com/
source-date: 2026-11-12

K-12 Dive 報導，St. Louis 公立學區董事會 11/10 以 4 比 3 通過，自 2027–28 學年將學校數從 61 所減為 52 所。1991 至 2025 年間在學人數減少 58.5%，即 25,303 人；關校能省下多少經費仍不明。學區今年稍早被降為「暫時認證」。

**對你而言**：關校後學生分散到其他學校。學生轉班後，自家課中互動的班級名單能隨 rostering 自動更新嗎？
