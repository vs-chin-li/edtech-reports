---
type: intel-report
doc-id: INTEL-2026-09-01-biweekly
title: "EdTech 情報雙週報 2026-09-01（聯邦成效證據指引 × 學生端 AI 進開學動線 × 採購端要可交代性）"
description: "蒐集區間 2026/08/16–09/01。主軸：美國教育部 8/20 Dear Colleague 指引把成效證據、家長透明與螢幕時間目的寫成聯邦立場；OpenAI ChatGPT for Teens 以年齡自動分流與 Study Mode 建立未成年 AI 介面基準；Google 開學季推出學生端 study notebooks 並為 Classroom 加上 Context-Aware Access；採購端把使用回報、SSO/rostering、人工監督寫進合約。IFP 硬體維持年會後空窗。11 項，逐項標 tier（hot/warm/cold）。非使用者證據。"
resource: "https://github.com/vs-chin-li/edtech-reports/blob/main/reports/edtech-biweekly-2026-09-01.html"
tags: [intel, us, policy, edtech-software, ux-trend, market]
timestamp: 2026-09-01T00:00:00Z
report-date: 2026-09-01
collection-window: "2026-08-16/2026-09-01"
valid-until: 2027-09-01
markets: [us]
status: active
---

# EdTech 情報雙週報 · 2026-09-01

> 主軸：本期落在「聯邦把成效證據與對家長透明寫進正式指引」與「學生端 AI 全面進入開學動線」同時發生的節點。
> 美國教育部 8/20 以 Dear Colleague 信要求以學習成果而非使用時數評斷工具、對供應商列出獨立評估與揭露能力限制的期待；
> OpenAI 8/18 推出 ChatGPT for Teens（年齡自動分流、Study Mode、監護人看得到邊界看不到內容）；
> Google 8/19 上線學生端 study notebooks 與 student hub、8/26 為 Classroom 加上 Context-Aware Access；
> 採購端則由 EdWeek 8/20 與 MarketScale 8/29 指出「合約從未定義成功」，把使用回報、SSO/rostering、人工監督推成條款。
> IFP 互動大屏本期無重大更新（本季發表集中在 Bett 2026 與 ISTELive 26，已於前兩期收錄）。
> 查證方式：五大面向逐層掃描近 14 天（一手/權威層 → 產業媒體層 → 展會/報告層），每則開頁核對內容、
> 網址與真實發布日期，並標信心等級與來源類型。開頁查證後排除或校正：Nearpod 開學季更新實際為 2026-08-06（上期窗口）；
> MagicSchool Back-to-School 為 2026-06-25；SMART Lumio WCAG 2.2 為 2026-07-07；Instructure 2026 Evidence Report 為 2026-03-10；
> Canva for Education 最新一波為 Canva Create 2026（4–5 月）；EdTech Innovation Hub「8 月熱門故事」一則實為 2025-09-05 舊文；
> Microsoft EDU「Back to School August 2026」貼文無法開頁取得正文與明確發布日，依誠實原則不列；SchoolAI 查無可核對官方新聞稿；
> ADA Title II 已延至 2027-04、FCC E-Rate 意見期 10/13 截止，本期均無新里程碑。

## 本期項目

### INTEL-0901-1 — 美國教育部發布課堂科技「負責任使用」指引：以學習成果而非使用時數評斷工具
tier: warm
expires: 2027-09-01
design-impact: true
confidence: 高
source-type: 政府一手（U.S. Department of Education 新聞稿）
region: US
category: policy
source-url: https://www.ed.gov/
source-date: 2026-08-20

8/20 由 Assistant Secretary Kirsten Baesler 具名的 Dear Colleague 信，是聯邦針對課堂科技選用與檢討的正式立場。核心主張：優先看教學價值而非「娛樂式投入」；工具須有獨立證據證明能改善學習成果；學校應定期檢討成效，證據顯示無效就換掉、反覆確認有缺陷就整個移除。同時強調要減少不必要的螢幕暴露、讓科技有明確的教學目的與使用時長，並要求學校與供應商對家長揭露科技如何被使用、學生用了多久、是否確實帶來有意義的學習。指引亦指出，選對的教學科技能支持身心障礙學生、縮小學習落差。此信銜接 2025-07 McMahon 部長提出的五項 AI 原則（含「保護學生資料」）。

**對你而言**：指引把「使用時長」與「對家長交代」同時放上檯面。課中即時評量與白板教學這些場景，現在留下的是「誰按了什麼」的操作紀錄，還是「這段時間學生實際做了什麼、學到什麼」的教學紀錄？後端報告畫面若要回答學校「這個工具有沒有用」，需要的欄位跟現在呈現的參與度／出席數字是不是同一組？產品在哪個介面位置說明自己的能力邊界與適用情境——是只在官網，還是老師開啟功能的當下就看得到——值得一問。

### INTEL-0901-2 — 同一份指引對「供應商」開出的具體清單：獨立評估、公開成效、揭露能力與限制
tier: warm
expires: 2027-09-01
design-impact: true
confidence: 高
source-type: 產業媒體逐條拆解一手文件＋業界訪談（EdSurge）
region: US
category: policy
source-url: https://www.edsurge.com/
source-date: 2026-08-20

EdSurge 8/20 拆解這封信對兩端的要求。對學區：區分休閒與教學科技、以學習成果而非螢幕時間評斷、採購時優先考量有 RCT 證據的產品、建立導入與成效檢討流程、投資教師專業發展。對供應商：與教師和家長共同設計產品、進行獨立評估與 RCT、在最大化教學價值的前提下盡量壓低螢幕暴露、「在可行時」公開學生學習成效發現、對產品能力與限制保持透明。Baesler 同時提醒不應單以學生使用時間長短評斷教育科技，因為遠距存取對偏鄉與身障學生特別重要。業界對「重成果」方向多表歡迎，但 Helen Crompton 與 Jean-Claude Brizard 批評這種放任式做法缺乏全國性的學生隱私、無障礙與資料保護標準，恐擴大各州之間的落差。

**對你而言**：「對產品能力與限制保持透明」落到介面上是個尚未有共識的設計題。AI 輔助功能（生成題目、生成教材、生成摘要）在使用當下要不要、以及用什麼形式說明「它適合什麼、不適合什麼」？寫在說明文件、放進首次使用引導、還是留在產出結果旁邊，三種選擇對老師的信任建立完全不同。批評方點名的「無障礙沒有全國標準」意味著各州各自要求，介面的無障礙表現若要能逐州交代，需要的是可查驗的規格說明還是產品內的設定項，值得先想清楚。

### INTEL-0901-3 — 聯邦為 edtech 辯護，與州級／學區的螢幕時間限制形成張力
tier: warm
expires: 2027-09-01
design-impact: false
confidence: 高
source-type: 產業媒體分析（K-12 Dive）
region: US
category: policy
source-url: https://www.k12dive.com/
source-date: 2026-08-20

K-12 Dive 8/20 的解讀點出這封信的政治位置：它是教育部在螢幕時間限制持續擴散之際的第一個明確表態。Baesler 主張「教育科技的使用與休閒科技的使用是兩回事」，認為政策制定應聚焦教育價值而非單看螢幕暴露，並強調輔助科技對身障學生、遠距存取對偏鄉學生的價值。但同時間，數個州與 Los Angeles Unified 已在 2026 年推動使用時數限制，FCC 與 HHS 也各自對青少年螢幕暴露表達關切——聯邦內部對「課堂科技該擴張還是該節制」並未一致。

**對你而言**：當同一個學年裡，聯邦說「別只看時數」、州和大學區卻直接寫下分鐘數上限，產品端等於同時面對兩套評判標準。課堂互動情境若被要求「用最少的螢幕時間達到同樣的教學目的」，哪些動線其實可以更短——例如把內容投放到學生裝置這類場景，是每個環節都要學生盯著自己的螢幕，還是有些步驟本來就該回到大屏、回到教室前方？值得先盤點自家哪些流程是「必須看螢幕」、哪些只是習慣。

### INTEL-0901-4 — OpenAI 推出 ChatGPT for Teens：年齡自動分流、Study Mode 引導式回答、監護人看得到邊界但看不到內容
tier: hot
expires: 2026-11-16
design-impact: true
confidence: 高
source-type: 科技媒體開頁核對（TechCrunch；官方 openai.com 頁面本期無法直接開啟驗證）
region: US/Global
category: edtech-software
source-url: https://techcrunch.com/
source-date: 2026-08-18

8/18 全球推出（免費與付費個人方案皆適用）。若使用者自陳 13–17 歲，或系統推估其未滿 18 歲，會被自動放進青少年版本，內容防護針對自傷、輕生與戀愛／性相關對話加強。Study Mode 以引導提問與分步支援取代直接給答案，並附測驗與學習視覺化；系統偵測到疑似「用來作弊」時，會把使用者導回 Study Mode。監護人端可連結帳號、管理部分設定、設定 Quiet Hours（禁用時段）、決定 Study Mode 是否預設啟用，並在有限的高風險情境收到安全通知——但無法閱讀或監看青少年的對話內容。TechCrunch 同時質疑這些防護實際上有多容易被繞過仍待觀察，且保護遲至週活躍用戶已達 9 億後才推出。

**對你而言**：這一則同時示範了三個可對照的決策。一是「年齡不是使用者填的、是系統推估的」——若自家學生端功能要做年齡適配，資訊來源是 rostering 帶入的年級、還是需要另一套判斷？二是「引導模式可以被設成預設」——課中即時出題若有 AI 協助解題，預設是給答案還是給提示，這個預設值該由誰決定（老師、學校、還是產品本身）？三是最值得一問的：監護角色「看得到設定與警訊、看不到對話內容」這條界線，換到老師身上該畫在哪裡——老師需要看到學生跟 AI 講了什麼，還是只需要看到「哪些學生卡住了」？兩種答案會做出完全不同的教師端畫面。

### INTEL-0901-5 — Google 開學季發布：學生端 study notebooks 與 student hub 上線，教師端可依課綱調整並即時追蹤
tier: hot
expires: 2026-11-17
design-impact: true
confidence: 高
source-type: 廠商官方（Google 官方部落格）
region: US/Global
category: edtech-software
source-url: https://blog.google/
source-date: 2026-08-19

8/19 的 Back to School 發布把 Gemini 的學生端整理成一個學習中樞。Study notebooks 用診斷式小測驗找出強項與知識缺口，再產出分段（bite-sized）的個人化學習計畫；student hub 讓學生整理課綱、追蹤截止日、依課程教材建立客製學習計畫；另加上互動式視覺化與可在 Gemini Live 中口頭討論的 Deep Research 報告。教師端則在 Google Classroom 拿到 teacher-led tools，可依自身課綱調整學生的 AI 體驗並即時追蹤進度，另有連結 Classroom 的 Gemini 應用可安全地起草教案。美國符合資格的大學生另可領一年免費 Google AI Pro。

**對你而言**：值得檢視的是這條動線的順序——Google 的做法是「先診斷 → 再產出分段計畫 → 老師可調整範圍並看到進度」，把 AI 放在診斷與規劃這一端，而不只是產內容。自家課中即時評量已經在收集答題資料，這些資料現在停在「這題全班對幾成」，還是有往「這個學生下一步該練什麼」延伸的位置？如果要延伸，老師是在課中就要看到建議，還是課後在後端報告裡看？另外「teacher-led」在介面上到底長什麼樣：是老師先設好範圍學生才看得到，還是學生先用、老師事後看紀錄，這個預設會決定教師端主畫面該以「設定」還是以「觀察」為中心。

### INTEL-0901-6 — Google Classroom 支援 Context-Aware Access：管理者可依身分、地點、裝置狀態與 IP 決定誰能開啟
tier: hot
expires: 2026-11-24
design-impact: true
confidence: 高
source-type: 廠商官方（Google Workspace Updates）
region: US/Global
category: edtech-software
source-url: https://workspaceupdates.googleblog.com/
source-date: 2026-08-26

8/26 公告、8/18 起推出（Rapid 與 Scheduled Release 皆為 available now），僅限 Education Standard 與 Plus。管理者可在 Admin console 為 Classroom 設定情境式存取政策，條件包含使用者身分、地理位置、裝置安全狀態與 IP 位址，例如限定只有從特定地理區域連線才能存取 Classroom；政策可以 OU 或群組為單位套用。使用者端以 Google 登入進入 Classroom，若組織的 Context-Aware Access 設定限制了其存取，會看到說明訊息或補救選項。

**對你而言**：重點不在「能不能擋」，而在「被擋的時候使用者看到什麼」——Google 明確做了「說明訊息或補救選項」這一層。自家課中軟體若因為裝置、網路或權限條件而無法使用，老師在課堂當下看到的是可行動的說明（原因是什麼、找誰、能不能改用別的方式繼續上課），還是一個泛用的錯誤畫面？在一堂課只有四十幾分鐘的前提下，這個失敗狀態的文案與後續選項，實質上決定了老師會不會第二次再用。另外當管理者用 OU／群組把權限切得很細，老師端有沒有辦法在上課前就知道「我這班今天能用什麼」，而不是進了教室才發現。

### INTEL-0901-7 — 學區實務把「AI 產出 → 人做決定」寫成明規則，並刻意不把敏感個資餵進系統
tier: warm
expires: 2027-09-01
design-impact: true
confidence: 高
source-type: 產業媒體實地訪談（K-12 Dive）
region: US
category: ux-trend
source-url: https://www.k12dive.com/
source-date: 2026-08-26

K-12 Dive 8/26 訪問多個學區的人事主管，整理出一套已在運作的人機分工原則。Indianapolis Public Schools 用 Google Gemini 自建內部工具做校長職缺的初步候選人評分，但最終人選由遴選委員會決定；受訪者直言「AI 對我們而言不是任何決策的替代品」。學區普遍避免把敏感的個人可識別資訊輸入 AI 系統，Indianapolis 也因為自建而非採購多家第三方工具，省下逾 $300,000 並保有員工資料的控制權。科羅拉多州教育廳則建議建立明確的 AI 治理架構、為每項新措施指定聯絡窗口，以避免規模化後的失控與不一致。

**對你而言**：這則的價值在於它是實際運作中的模式，不是原則宣示：AI 只做「初步排序」，人做「最終決定」，兩者在流程上被明確分開。自家任何會影響到個別學生評價的畫面——即時評量的成績彙整、後端報告的參與度分析——若引入 AI 產出的判斷或分群，介面上有沒有把「這是系統的初步判斷」與「這是老師確認過的結論」視覺上分開？還是兩者混在同一張表上、老師事後也分不清哪個數字是誰下的？另外，哪些欄位其實不需要送進 AI 就能完成任務，這個「刻意不傳」的邊界值不值得在產品說明裡對學區講清楚。

### INTEL-0901-8 — 本期訊號：「可交代性」正在成為一個介面問題，而不只是文件問題
tier: warm
expires: 2027-09-01
design-impact: true
confidence: 中
source-type: 推論（以 ED 一手指引 8/20＋K-12 Dive 8/26＋MarketScale 8/29 為據，銜接前期教師掌控權觀察）
region: US
category: ux-trend
source-url: https://www.marketscale.com/
source-date: 2026-08-29

把本期三條線放在一起看：聯邦要求學校對家長揭露科技如何被使用、學生用了多久、是否帶來有意義的學習（8/20）；學區在採購合約裡開始要求依學校與年級的使用回報（8/29）；學區實務上已把「AI 初判、人決定」寫成明規則（8/26）。三者指向同一件事——過去放在白皮書、資安問卷、DPA 附錄裡的東西，正在往產品介面移動：誰用了、用多久、AI 建議了什麼、人改了什麼。這延續前期觀察到的「教師掌控權前景化」，但重心從「老師能不能改」推進到「改完之後，這件事對外交代得出來嗎」。

**對你而言**：如果明年學區帶著「請提供這學期這個工具怎麼被用、有沒有用」來要資料，現在的後端報告畫面能回答到哪一層？是只能給登入次數與活動次數，還是能對到教學情境（哪個班、哪堂課、什麼類型的活動）？以及這份「對外交代」的視角，該是後端報告裡的一個新分頁，還是應該讓老師在課後就能一鍵匯出？把它當成新使用者（學區管理者、要向家長說明的校方）的需求來看，而不是既有報表加欄位，可能會得到不一樣的資訊架構，值得觀察。

### INTEL-0901-9 — 學區被 AI 工具數量與改版速度淹沒：資訊不對稱成為採購的核心難題
tier: warm
expires: 2027-09-01
design-impact: false
confidence: 高
source-type: 產業媒體訪談＋市場數據（Education Week）
region: US
category: market
source-url: https://www.edweek.org/
source-date: 2026-08-20

EdWeek 8/20 報導指出，教育 AI 市場 2025 年約 $2.5B 營收、推估 2033 年超過 $15B，整體教育科技產業 2030 年上看 $90B 以上；但學區官員普遍苦於工具數量過多、廠商改版過快、缺乏清楚的判斷依據。American Enterprise Institute 的 Mark Schneider 直指「廠商知道的與學區知道的之間永遠存在不對稱」，一位學區總監則直言多數工具其實沒有為學生帶來什麼改變。目前學區的把關清單包括資料處理協議與資安問卷、要求廠商保證學生資料不被販售或用於訓練模型、評分與懲處決策須保留人工監督、以及實際的成效改善評估。賓州、紐約市與芝加哥已各自訂出採購指引，聯邦層面則指引有限。亞利桑那州立大學研究者另記錄到演算法公平性的實際問題：英語學習者被系統不當扣分或誤讀。

**對你而言**：學區的把關清單其實是一份產品需求清單。「保證學生資料不用於模型訓練」「評分與懲處保留人工監督」這兩條，在自家介面上有沒有對應的可見證據——是只寫在合約與隱私政策，還是老師在使用 AI 相關功能時就看得到？研究點名的「英語學習者被誤判」直接對應到課中即時評量的多語情境：語音、手寫、開放式作答的判讀在非母語學生身上表現如何，介面有沒有讓老師發現並更正誤判的入口，值得檢視。

### INTEL-0901-10 — 採購合約開始要求使用回報與整合標準：SSO、rostering 與依年級的用量報表被寫進條款
tier: warm
expires: 2027-09-01
design-impact: true
confidence: 中
source-type: 產業媒體分析（MarketScale，屬評論／實務建議性質而非一手調查）
region: US
category: market
source-url: https://www.marketscale.com/
source-date: 2026-08-29

MarketScale 8/29 指出學區買 AI 買得快，但合約裡從一開始就沒有定義「什麼叫成功」，導致稽核與續約時無法交代，風險是「把錯的續約鎖進未來好幾年」。文中列出的採購防護做法包括：在合約前先定義要解決的學術問題、要求依學校與年級層級的使用回報、強制 SSO 與 rostering 等整合標準、把專業培訓編列為核心導入成本而非選配。文章同時點名 Utah 與 Los Angeles 的新螢幕時間政策，正在逼學校為每項工具的使用時間提出正當理由，使成效宣稱受到更嚴格檢視；並指出當老師同時使用多個 AI 工具處理不同任務時，監督與資料控管會變得更困難。

**對你而言**：「依學校與年級層級的使用回報」「SSO 與 rostering」這兩項若成為合約標配，就會直接回頭改變產品面貌。自動 rostering 的整合現況能不能撐住「以年級為單位」的報表切分，還是報表目前只切到班級與個人？以及登入這一段——老師與學生從 SSO 進來後，第一次使用的引導與權限狀態是不是清楚的？文中提到的「多工具並用讓監督變難」也值得觀察：如果老師的一堂課同時開著投屏、白板與即時評量，這三者的使用紀錄現在是分開的三份，還是能拼成學區看得懂的一堂課。

### INTEL-0901-11 — AI 的成本被拆成兩筆帳：資料中心帳單，以及重新設計作業所需的教師時間
tier: warm
expires: 2027-09-01
design-impact: false
confidence: 中
source-type: 產業媒體 podcast 節目（EdSurge，屬記者與教育工作者的討論而非量化調查）
region: US
category: market
source-url: https://www.edsurge.com/
source-date: 2026-08-19

EdSurge 8/19 的 podcast 把「AI 到底讓學校付出什麼」拆成兩層。財務層：記者 Mi Aniefuna 把教育科技一路追回到支撐它的資料中心與隨之而來的成本，指出帳單會「隨每一次使用而增長」，學區在權衡 AI 導入時往往只看課程決策、忽略了不斷上升的發票。教學層：Michael Hernandez 討論的則是當 AI 隨處可得，教學本身要跟著改——教師必須額外投入時間重新設計作業，才能在學生普遍可用 AI 的前提下維持認知強度。核心張力是：學校在資訊不完整的情況下推動 AI 導入，可能同時低估了直接營運費用與重新設計教學的間接成本。

**對你而言**：「每一次使用都在增加帳單」換到介面上是個少被討論的設計題。課中的 AI 輔助功能若是按用量計費，老師在使用當下知不知道自己在消耗什麼、學校端看不看得到用量分佈？不揭露，超支的驚訝會在續約時反噬；揭露得太重，又會讓老師在課堂中猶豫。教師時間這筆帳也值得思考——自家功能如果讓老師省下備課時間，但同時要求他們重新設計評量方式，這個「省下的」與「多花的」在產品敘事裡有沒有被誠實地擺在一起。
