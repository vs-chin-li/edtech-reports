---
type: intel-report
doc-id: INTEL-2026-09-18-biweekly
title: "EdTech 情報雙週報 2026-09-18（兩大學區關掉學生端 AI × 評斷標準轉向成果證據 × WCAG 3 改寫符合性模型）"
description: "蒐集區間 2026/09/01–09/18。主軸：紐約市對 2-K 至 8 年級停用學生端生成式 AI 一年、LAUSD 全年級一律禁用，兩者都保留教師使用；AFT／UFT 與 Microsoft 簽下 11/1 生效的法律可執行 AI 資料協定；APA 主張評斷教育科技不能只看螢幕時間，AugmentED 研究顯示 AI 評批判思考準確率不過 78%；W3C 發布 WCAG 3.0 新工作草案，符合性改為單一等級＋上下回報層。IFP 硬體維持年會後空窗。16 項，逐項標 tier（hot/warm/cold）。非使用者證據。"
resource: "https://github.com/vs-chin-li/edtech-reports/blob/main/reports/edtech-biweekly-2026-09-18.html"
tags: [intel, us, policy, edtech-software, ux-trend, market]
timestamp: 2026-09-18T00:00:00Z
report-date: 2026-09-18
collection-window: "2026-09-01/2026-09-18"
valid-until: 2027-09-18
markets: [us]
status: active
---

# EdTech 雙週報 · 2026-09-18

> 主軸：本期落在「學生端生成式 AI 被制度性關閉」與「評斷標準同時轉向成果證據」同時發生的節點。
> 紐約市 9/2 對 2-K 至 8 年級停用學生端 AI 一年、LAUSD 9/3 對全年級學生一律禁用，兩者都保留教師的備課與行政使用；
> AFT／UFT 與 Microsoft 9/9 簽下 11/1 生效的法律可執行資料協定；APA 9/14 主張別只看螢幕時間、
> AugmentED 研究顯示 AI 評批判思考準確率不過 78%；W3C 9/10 發布 WCAG 3.0 新工作草案改寫符合性模型。
> IFP 互動大屏本期無重大更新。查證方式：五大面向逐層掃描本期區間，每則開頁核對內容、網址與真實發布日期，並標信心等級與來源類型。
> 註：本期排程於 9/15 觸發、實際執行於 9/18，窗口延伸至 9/18，與前期（2026-09-01）之間無空隙。

## 本期項目

### INTEL-0918-1 — 紐約市對 2-K 至 8 年級關掉學生端生成式 AI，並訂螢幕時間上限
tier: warm
expires: 2027-09-18
design-impact: true
confidence: 高
source-type: 政府一手（NYC 市長辦公室新聞稿）
region: US
category: policy
source-url: https://www.nyc.gov/
source-date: 2026-09-02

9/2 由市長 Mamdani 與總監 Samuels 公布，2026-27 學年實施一年：2-K 至 8 年級禁用學生端生成式 AI 與陪伴型聊天機器人，約 60 萬名學生、佔全市三分之二。螢幕時間 3–5 年級建議每日 30 分鐘、6–8 年級 45 分鐘，2 年級以下限制一對一使用。身障學生輔助科技、多語學習者、職涯課程學生為例外；教師仍可用 AI 做備課與行政工作。高中開放五項試點，上限 5 萬人。

**對你而言**：例外清單把輔助科技與多語學習者留在線上。課中互動若以「學生裝置參與」為前提，當這層被關掉、只剩輔助用途可用時，同一堂課的參與動線還走得通嗎？

### INTEL-0918-2 — 洛杉磯聯合學區更進一步：全學區、全年級學生一律禁用生成式 AI
tier: warm
expires: 2027-09-18
design-impact: true
confidence: 高
source-type: 產業媒體（K-12 Dive）
region: US
category: policy
source-url: https://www.k12dive.com/
source-date: 2026-09-03

9/3 公布，2026-27 學年對所有年級學生關閉生成式 AI。此前的規則是 13 歲以上、完成數位公民課並閱讀使用規範者可存取核准平台，如今一併收回。學區同日召開 Generative AI Ad Hoc Committee 首次會議，將在本學年結束前向教育委員會提出政策建議。報導未列學生端例外，也未提及教師使用限制。與紐約市同週宣布，使全美兩大學區同時對學生端 AI 按下暫停。

**對你而言**：LAUSD 收回的正是「年齡＋完成訓練＝解鎖」這套分級開通設計。若自家軟體也用類似條件開放功能，學區一句話要全區關閉時，後台有沒有一個開關做得到？

### INTEL-0918-3 — 美國心理學會：評斷教育科技不能只看螢幕時間
tier: warm
expires: 2027-09-18
design-impact: true
confidence: 高
source-type: 產業媒體報導專業學會報告（K-12 Dive）
region: US
category: policy
source-url: https://www.k12dive.com/
source-date: 2026-09-14

K-12 Dive 9/14 報導 APA 新報告。APA 主張政策應看「學生在螢幕上做什麼、科技取代掉什麼活動」，以及工具是否真的改善學習成果，而非只看使用時長。替代的評估面向包括：內容品質、環境脈絡（背景螢幕、成人在日常作息中的裝置使用）、科技的目的與用法，以及使用後至少維持一週的學習與技能遷移。報告並指出廠商應提供獨立驗證，證明的是知識保留，而不只是投入度或喜好度；生成式 AI 另需額外防護與年齡限制。

**對你而言**：「使用後一週仍留存」是一條比使用率嚴格得多的線。若要拿得出這種證據，課中評量資料得跨越單堂課被接起來——現在的報告是否還是以一堂課為邊界？

### INTEL-0918-4 — 禁令從手機延伸到智慧眼鏡：「偵測不到」成為校方的核心顧慮
tier: warm
expires: 2027-09-18
design-impact: true
confidence: 高
source-type: 產業媒體整理多學區政策（Education Week）
region: US
category: policy
source-url: https://www.edweek.org/
source-date: 2026-09-14

EdWeek 9/14 整理：Fairfax County、Prince William County（維州）、Greenville County（南卡）、Carson City（內華達）、Parker（亞利桑那）等學區已於本學年禁止學生使用智慧眼鏡；猶他州 7 月立法在校期間全州禁用；College Board 也在 SAT 考試中禁用。多數併入「個人數位通訊裝置」規範，或在學生行為準則中與智慧手錶、手機並列。校方顧慮集中在無法偵測——老師無從得知學生正在聽或看什麼——以及考試作弊、未經同意錄下同學與教師。猶他州法允許健康監測或 IEP 調整等例外。

**對你而言**：值得注意的是理由不是功能本身，而是「老師看不出來」。課堂管理介面若要讓老師掌握學生的裝置狀態，揭露到什麼程度才算夠用而不變成監看？

### INTEL-0918-5 — AFT／UFT 與 Microsoft 簽下法律可執行的 AI 資料協定，11/1 生效
tier: hot
expires: 2026-12-08
design-impact: true
confidence: 高
source-type: 產業媒體（K-12 Dive）
region: US
category: edtech-software
source-url: https://www.k12dive.com/
source-date: 2026-09-09

K-12 Dive 9/9 報導。協定禁止 Microsoft 將學生與教育人員資料用於訓練 AI 模型或廣告；資料的使用、保存與刪除決定權留在學校；要求嚴謹的安全措施，並要求 AI 工具的設計避免對學生造成有害或操弄性的體驗。標準自 2026-11-01 起適用全美所有學區，學區可直接納入既有或新的 Microsoft 合約，無須重新議約。AFT 主席 Randi Weingarten 稱其為首例，並期望 OpenAI 與 Anthropic 跟進。

**對你而言**：「不得用於訓練」從隱私政策的敘述變成可執行條款。這件事若要讓老師在課堂當下看得見，該顯示在哪一層——功能入口、資料送出前，還是完全不顯示？

### INTEL-0918-6 — 紐約市的「核准工具」長什麼樣：每週分鐘上限＋六項廠商檢核
tier: hot
expires: 2026-12-02
design-impact: true
confidence: 高
source-type: 產業媒體（EdTech Innovation Hub；細節與 NYC 官方新聞稿一致）
region: US
category: edtech-software
source-url: https://www.edtechinnovationhub.com/
source-date: 2026-09-03

EdTech Innovation Hub 9/3 補上細節。高中五項試點各有明確的使用時間上限——Quill 每週 15 分鐘、Edia 20 分鐘，其餘類似；全體高中生每年上兩堂 45 分鐘的 AI 素養模組。工具審查以「是否對學習具關鍵性」為門檻，逐項檢核廠商的安全、透明、倫理、學習設計證據、既有研究與使用者回饋蒐集；判定為非必要者可被擋掉。五項試點分工明確：Quill 做文本細讀與證據運用、Edia 做數學、Brisk Teaching 跨科支援教師自建活動、Playlab 教學生檢視 AI 產出的偏誤與推理、Intel AI-Ready Schools 做學期專題。

**對你而言**：值得觀察的是「每週分鐘數」成了核准條件。若採購方開始要求逐工具的時間上限，產品端要能回答的不只是用了多久，而是誰有權設這個上限。

### INTEL-0918-7 — Google 擴充免費教師 AI 訓練：15 分鐘模組、每月首週三上新、數位徽章
tier: hot
expires: 2026-12-02
design-impact: false
confidence: 高
source-type: 廠商官方（blog.google；已確認不含新產品功能）
region: US/Global
category: edtech-software
source-url: https://blog.google/
source-date: 2026-09-03

9/3 官方部落格。Google AI Educator Series 為免費隨選訓練，模組設計在 15 分鐘內完成並取得數位徽章，每月第一個週三上新。新模組涵蓋：自動化例行行政（如家長通知信）、以 Gemini Guided Learning 的蘇格拉底式提問做個人化學習、以 Deep Research 做學生研究，以及遊戲化模組「AI Quest: Market Marshes」。9/19 另辦線上 Badge-a-thon，含教師閃電講、模組導覽與 ISTE 對齊的徽章認證。本則屬教師專業發展，未含新的 Classroom 產品功能。

**對你而言**：值得一問的是節奏：15 分鐘一個模組、每月固定上新，把教師學習切成可預期的小步。自家功能更新的說明若也照這個顆粒度切，老師會更容易跟上嗎？

### INTEL-0918-8 — SMART Lumio 九月版把「匯入」做成背景工作：可邊等邊做事
tier: hot
expires: 2026-11-30
design-impact: true
confidence: 中
source-type: 廠商官方 release notes（SMART support；僅標月份，無日層級發布日）
region: US/Global
category: edtech-software
source-url: https://support.smarttech.com/
source-date: 2026-09-01

官方 release notes 的九月項目：匯入檔案時提供更詳細的進度顯示；新增背景匯入，使用者可在檔案處理期間繼續工作，稍後從 Processing 面板取用；AI Assist 的支援語言清單也開始公開。八月版則加入可收合的左側導覽、Handout Dashboard 的學生作品即時縮圖、超過 30 天的課堂自動歸入 Older Sessions，以及多檔同時匯入與「是否可編輯」的單一開關。官方頁未標日層級發布日，source-date 以該月首日記錄。

**對你而言**：把匯入改成背景工作，解決的是老師備課時被迫等待。自家匯入教材的流程目前是把人留在原地等，還是放他先去做下一件事？

### INTEL-0918-9 — W3C 發布 WCAG 3.0 新工作草案：符合性模型改為單一等級＋上下回報層
tier: warm
expires: 2027-09-18
design-impact: true
confidence: 高
source-type: 標準組織一手（W3C WAI 公告）
region: Global
category: ux-trend
source-url: https://www.w3.org/
source-date: 2026-09-10

9/10 的更新進一步發展提案中的符合性模型，並更新了已進到「Developing」階段的指引與要求。與 WCAG 2.2 最大的差別在於符合性如何評估與回報：草案提議採單一符合等級，在其上下另設回報層級，並把要求分成三類（Core 為任何符合聲明的必要條件、Supplemental 超出該基準）以取代熟悉的 A／AA／AAA。適用範圍也擴大到網頁內容、應用程式、工具、出版與新興網頁技術。W3C 明確表示 3.0 仍是未完成草案、不取代 2.2，組織仍應持續符合 2.2 的 A 與 AA。

**對你而言**：方向是從「過了哪些檢核項」轉向「回報到哪一層」。若未來要交代的是一份分層報告，自家課中互動元件目前有沒有一份說得出口的無障礙現況清單？

### INTEL-0918-10 — 研究：AI 評批判思考的準確率不超過 78%，弱項集中在反駁與邏輯謬誤
tier: warm
expires: 2027-09-18
design-impact: true
confidence: 高
source-type: 產業媒體報導研究（K-12 Dive／AugmentED · AERDF）
region: US
category: ux-trend
source-url: https://www.k12dive.com/
source-date: 2026-09-02

K-12 Dive 9/2 報導 AERDF 旗下 AugmentED 的研究，以 ETS 與 Carnegie Foundation 的評分標準（六項批判思考子技能）測試 AI 評閱 6–12 年級論說文的能力。即使加上微調與額外提示，各子技能準確率都沒超過 78%。相對強的是跨來源綜合資訊與評估證據強度；明顯較弱的是運用反駁、區分事實與意見、下結論、辨識邏輯謬誤。創辦人 Sherry Lachman 直言「還沒到可以上場的程度」。研究者強調導入前須先驗證，並警告別讓 AI 擋掉學生自行發展批判思考的機會。

**對你而言**：準確率因子技能而異，這是個介面問題而不只是模型問題。若評量功能引入 AI 評閱，老師看得出哪一項判斷比較可信、哪一項該自己重看嗎？

### INTEL-0918-11 — 猶他 Jordan 學區：把 AI 定位成「思考夥伴」而非產出者，回報批判思考提升 28%
tier: warm
expires: 2027-09-18
design-impact: true
confidence: 中
source-type: 產業媒體報導單一學區自陳成效（K-12 Dive；非獨立第三方評估）
region: US
category: ux-trend
source-url: https://www.k12dive.com/
source-date: 2026-09-09

K-12 Dive 9/9 報導。Jordan School District（西約旦市）兩年前導入 AI 工具，明訂用法為「思考夥伴而非內容產出者」，不讓 AI 評改作業、不取代師生互動；教師可把它當助教做初步評閱回顧，但全程保留人工監督。學區以 82 位教師、近 14,000 則學生與 AI 的對話為分析基礎，回報學生批判思考提升 28%，跨學科與年級的高層次推理能力增加一倍以上。學區官員的說法是「不想把學生寫作或師生互動交給 AI」。

**對你而言**：值得檢視的是「初步評閱 vs. 正式評閱」怎麼在介面上分開。若 AI 只做前者，它的輸出該不該長得跟老師的正式評語一樣？

### INTEL-0918-12 — 特教爭議程序出現 AI 誤用：官方給家長的能力邊界對照清單
tier: warm
expires: 2027-09-18
design-impact: true
confidence: 高
source-type: 產業媒體報導官方資助機構指南（K-12 Dive；指南原件為 2026-07）
region: US
category: ux-trend
source-url: https://www.k12dive.com/
source-date: 2026-09-09

K-12 Dive 9/9 報導 CADRE（美國教育部資助的特教爭議解決中心）的家長指南——指南原件發布於 2026 年 7 月。各州回報書面申訴與正當程序案件同時增加，內容也變得更長更複雜。指南警告 AI 會出錯、有附和偏誤、也不了解特定孩子的處境，並列出具體風險：家長若輸入可識別資訊或機密文件會暴露孩子個資、AI 可能誤釋 IDEA、在正當程序文件中引用不存在的判例、給錯申辦要求與程序。可用之處則是解釋 IDEA 術語、生成給老師與行政人員的問題、在 IEP 會議前練習溝通。

**對你而言**：官方把 AI 的能力邊界寫成一份「可以做什麼／不要拿去做什麼」的對照。自家 AI 功能的邊界說明，有沒有寫到這種可以逐條對照的程度？

### INTEL-0918-13 — 本期訊號：學生端被關掉之後，教師中介成為唯一還開著的路
tier: warm
expires: 2027-09-18
design-impact: true
confidence: 中
source-type: 推論（以 NYC 官方新聞稿 9/2＋K-12 Dive 9/3、9/9、9/14 為據，銜接前期「可交代性往介面移動」觀察）
region: US
category: ux-trend
source-url: https://www.k12dive.com/
source-date: 2026-09-14

把本期四條線放在一起：兩大學區同時關掉學生端生成式 AI，但都明確保留教師的備課與行政使用（9/2、9/3）；APA 要求的證據是「使用後一週仍留存的學習」而非使用率（9/14）；研究顯示 AI 評批判思考的各子技能準確率不過 78%（9/2）；而回報出成效的學區，把 AI 限定在「思考夥伴」、全程人工監督（9/9）。四者指向同一個方向——短期內站得住的是教師中介、人工保留最終判斷的設計，學生直接面對 AI 的路徑正在被制度性收窄。

**對你而言**：如果學生端在多個大學區被默認關閉一年，自家課中互動的核心價值還剩多少能在「學生不直接用 AI」的前提下成立？

### INTEL-0918-14 — Brookings：手機禁令的執行力在一學年內衰退，學生用量反而上升
tier: warm
expires: 2027-09-18
design-impact: true
confidence: 高
source-type: 產業媒體報導智庫調查（K-12 Dive／Brookings Institution）
region: US
category: market
source-url: https://www.k12dive.com/
source-date: 2026-09-15

K-12 Dive 9/15 報導 Brookings 的全國代表性調查，比對 2025 年 10 月與 2026 年 5 月兩波資料。近半數 13–17 歲青少年表示老師整學年對手機政策的執行變寬鬆，但 60% 的成年人認為沒有變化、僅 13% 認為變嚴。校內使用率從 28% 升到 42%。在 bell-to-bell 全面禁用的學校（56% 的學生），核心課堂使用率從 25% 升到 35%；在較彈性政策的學校（44%），從 32% 升到超過 50%。研究者歸因於學生學會繞過收納袋與置物櫃等障礙，加上教師整學年的警覺度下降。

**對你而言**：這份資料量化了一件設計上常被低估的事：規則會隨學年衰退，而大人不會察覺。課堂管理功能若靠老師持續施行才有效，它撐得過第幾個月？

### INTEL-0918-15 — 兩千名選民調查：77% 要明確法規護欄，跨黨派一致
tier: warm
expires: 2027-09-18
design-impact: false
confidence: 高
source-type: 產業媒體報導民調（K-12 Dive／Century Foundation × Morning Consult）
region: US
category: market
source-url: https://www.k12dive.com/
source-date: 2026-09-02

K-12 Dive 9/2 報導 The Century Foundation 委由 Morning Consult 執行、樣本逾 2,000 名選民的調查。擔憂比例：85% 擔心學生用 AI 交作業卻沒學到東西、81% 擔心教師被迫採用未經驗證的 AI 工具、80% 擔心學校沒把學生準備好面對 AI 時代、84% 擔心私人公司蒐集學生資料。77% 支持政府訂明確的法規護欄而非把決定留給老師（共和黨 80%、民主黨 76%）；49% 認為課堂科技使用應盡量減少。調查結論稱這些顧慮屬「非意識形態」的跨黨派共識。

**對你而言**：「教師被迫採用未驗證工具」有 81% 的人擔心，這是導入端的阻力來源。新功能的預設開啟策略，是替老師省事，還是把選擇權從他手上拿走？

### INTEL-0918-16 — EdSurge：寫給青少年的螢幕時間指引，落到四歲的教室就不成立
tier: warm
expires: 2027-09-18
design-impact: false
confidence: 中
source-type: 產業媒體 podcast（EdSurge，屬報導與討論而非量化調查）
region: US
category: market
source-url: https://www.edsurge.com/
source-date: 2026-09-02

EdSurge 9/2 的 podcast 處理政策與教室現實對不上的狀況。記者 Adam Stone 追的是幼教老師手上只有為青少年寫的螢幕時間建議、沒有適齡版本，只能「用手邊有的東西自己拼出一套做法」。節目另一段講一位密蘇里州公民科老師，因州法限制課堂手機使用而失去一個教學工具。全集問的是同一個問題：規則對不上的時候，由誰負責把它變得可行？

**對你而言**：年段落差被丟給老師自己補。自家功能若同時服務幼小與中學，預設值是按單一標準給，還是按年段給出不同的起點？
