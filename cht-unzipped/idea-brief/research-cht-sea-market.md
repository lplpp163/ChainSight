# ChainSight 深度研究：CHT 實際能力 × 東南亞三國市場評估

> **研究日期：** 2026-04-03
> **目的：** 以 CHT 的真實業務能力為基礎，重新評估馬來西亞、越南、新加坡三國市場定位，為提案修訂提供事實依據。
> **使用方式：** 本文件的結論應直接反映在 idea-brief 的下一版修訂中。

---

## 目錄

1. [CHT 企業服務真實面貌](#1-cht-企業服務真實面貌)
2. [CHT 東南亞據點實際能力](#2-cht-東南亞據點實際能力)
3. [馬來西亞市場評估](#3-馬來西亞市場評估)
4. [越南市場評估](#4-越南市場評估)
5. [新加坡市場評估](#5-新加坡市場評估)
6. [三國比較總表](#6-三國比較總表)
7. [5G 必要性分析](#7-5g-必要性分析)
8. [CHT 真正的護城河與能力缺口](#8-cht-真正的護城河與能力缺口)
9. [對提案的具體修訂建議](#9-對提案的具體修訂建議)
10. [研究組員分工建議](#10-研究組員分工建議)

---

## 1. CHT 企業服務真實面貌

### 1.1 營收結構

CHT 2024 年合併營收約新台幣 2,340–2,400 億元，其中 ICT/企業服務佔比約 15–17%（~350–400 億），是唯一雙位數成長的板塊（年增 10–15%）。國際業務（含海纜）僅佔 5–6%（~120–150 億）。
（來源：[中華電信 2024 年報 / 法說會資料](https://www.cht.com.tw/zh-tw/home/cht/investors)）

### 1.2 實際產品線

| 產品 | 實際內容 | 成熟度 | 與 ChainSight 的相關性 |
|------|---------|--------|----------------------|
| **企業專線 / MPLS VPN** | 台灣企業市佔第一 | 極成熟 | ✅ 跨境網路核心 |
| **SD-WAN** | 與 Fortinet/VMware(VeloCloud) 合作 | 成長中 | ✅ 台灣總部↔海外工廠 |
| **IDC / 機房** | 全台 30+ 座，台灣最大 | 極成熟 | ✅ 數據存儲基礎 |
| **資安 SOC** | 政府機關最大供應商 | 成熟 | ✅ 半導體資安需求高 |
| **5G 企業專網** | 台灣已建 50–70 座場域 | 成熟 | ⚠️ 僅限台灣有效 |
| **IoT 平台** | NB-IoT/LoRa，偏智慧城市（農業、路燈、停車） | 中等 | ⚠️ 非工廠場景 |
| **AI 能力** | 語音助理、影像辨識、資安 AI；2024 成立 AI 辦公室 | 早期 | ⚠️ 無製造業 AI 產品 |
| **iEN 平台** | **智慧節能（BEMS）**：電力/空調/照明能耗管理 | 成熟 | ❌ 不是工廠 MES/SCADA |

### 1.3 iEN 平台的真相

**iEN = intelligent Energy Network**，是建築能源管理平台，不是工廠數位化平台：

- 部署在 CHT 自身 500+ 個機房及營運據點，外部客戶為政府辦公大樓、學校、醫院、商辦
- 功能：用電監控、需量控制（demand response）、空調最佳化、碳排計算
- **不具備**：機台狀態監控、OEE 計算、預測性維護、供應鏈可視化等工廠功能

> ⚠️ **提案影響：** 目前提案寫「iEN IoT 平台」會讓評審誤以為有現成工廠平台。建議弱化 iEN 品牌，改強調 CHT 的 IoT 整合能力與資料平台架構（這與 "待解決問題與風險盤點" #2 的建議一致）。

### 1.4 智慧製造實際案例（台灣）

| 客戶 | 合作內容 | 備註 |
|------|---------|------|
| **日月光 ASE（高雄）** | 5G 專網 + AGV 管理 + AOI 影像傳輸 + AR 遠端協作 | 半導體封測業最具代表性案例 |
| **台達電子（桃園）** | 5G 企業專網 + 產線自動化 + 設備狀態監控 | |
| **中鋼** | 智慧工廠 + 設備預測性維護 | |
| **台塑集團** | 能源管理 + 環境監測 | |
| **高雄港** | 5G 智慧港口，遠端操控龍門吊車 | |

（來源：[中華電信企業服務官網](https://eshop.cht.com.tw/enterprise/)；[iThome 報導](https://www.ithome.com.tw/)）

> 📌 **關鍵發現：** CHT 與日月光在台灣有 5G 智慧工廠合作。日月光同時是檳城最大的封測廠之一。這條「台灣合作關係 → 延伸到海外廠」的路徑，是 ChainSight 最自然的切入點。

### 1.5 CHT vs 遠傳 vs 台哥大

| 面向 | 中華電信 | 遠傳 | 台灣大哥大 |
|------|---------|------|-----------|
| 企業市佔 | **第一（~50%+）** | 第二（~25%） | 第三（~15-20%） |
| 5G 頻譜 | **最多：3.5GHz 90MHz + 28GHz** | 80MHz + 28GHz | 60MHz + 28GHz |
| 5G 專網數量 | **~50-70 座** | ~30-40 座 | ~20-30 座 |
| 海底電纜 | **14+ 條（獨佔優勢）** | 無自有 | 無自有 |
| 東南亞據點 | **10+ 城市** | 無 | 無 |
| 智慧製造行銷 | 較保守 | 最積極（「大人物」品牌） | 較少 |

（來源：[NCC 頻譜核配資料](https://www.ncc.gov.tw/)；各公司年報）

> 📌 **關鍵結論：** 在東南亞服務台商這個市場，**遠傳和台哥大完全不構成競爭**，CHT 是唯一有海外據點的台灣電信商。

---

## 2. CHT 東南亞據點實際能力

### 2.1 據點總覽

| 據點 | 設立時間 | 人數（推估） | 核心業務 | 特殊資產 |
|------|---------|------------|---------|---------|
| **新加坡** | 2008 年 | 30–60 人 | 區域總部、國際專線、IDC 代管 | 海纜登陸點（SJC2 等） |
| **越南** | ~2010（合資 2008） | 100–200 人 | IDC/雲端、企業網路 | **Viettel-CHT 合資（Viettel 60% / CHT 40%）** |
| **泰國** | 2017 年 | 10–20 人 | 企業專線、5G 顧問 | Delta 智慧工廠案例 |
| **馬來西亞** | **2025/12** | **10–30 人** | 國際專線、SD-WAN | 由新加坡子公司 100% 持股 |

（來源：[MarketScreener - CHT Malaysia subsidiary](https://www.marketscreener.com/news/chunghwa-telecom-expands-asean-footprint-with-establishment-of-malaysia-subsidiary-ce7d51d8d88ff62c)；[DigiTimes](https://www.digitimes.com/news/a20251203PD221/cht-malaysia-subsidiary-bandwidth.html)；[BusinessWire - Viettel-CHT](https://www.businesswire.com/news/home/20211114005315/en/)）

### 2.2 各據點能做到 vs 做不到的事

#### 馬來西亞（最關鍵但最薄弱）

**能做到：**
- 幫台商拉國際專線 / SD-WAN
- 提供跨境網路管理（台灣 ↔ 檳城）
- 資安基礎服務

**做不到：**
- ❌ 5G 專網（無頻譜、無合作電信商）
- ❌ 工廠端 IoT 感測器部署
- ❌ 本地 IDC（需租用 TM 或第三方機房如 AIMS Data Centre）
- ❌ 直接接觸非台商客戶（如 Intel、Infineon）

> ⚠️ 馬來西亞子公司的定位是「企業 ICT 服務商」，不是電信營運商。不持有任何馬來西亞電信執照。最後一哩需向 TM 或 CelcomDigi 租用。（來源：[DigiTimes](https://www.digitimes.com/news/a20251203PD221/cht-malaysia-subsidiary-bandwidth.html)）

#### 越南（CHT 在東南亞最深的佈局）

**能做到：**
- IDC / 雲端服務（越南最大 DC/雲端商之一）
- 企業跨國專線
- 與 Viettel（越南最大電信商）的直接合作通道

**做不到：**
- ❌ 工廠端 OT 整合（Viettel-CHT 的 IoT/智慧製造合作目前**停留在 MOU 層級**，無公開部署案例）
- ❌ 直接服務 Samsung/Intel/Amkor（這些大廠使用 NTT/Lumen 等全球 IT 供應商）

（來源：[BusinessWire - CHT Viettel Cloud Partnership](https://www.businesswire.com/news/home/20211114005315/en/)；[CHT joins VSCC](https://www.businesswire.com/news/home/20230221005951/en/)）

#### 新加坡（海纜樞紐，非部署據點）

**能做到：**
- 國際頻寬批發與轉接
- 服務台商新加坡區域總部
- 跨國網路的中繼節點

**做不到：**
- ❌ 大規模本地 IoT 部署
- ❌ 自建 IDC（新加坡 DC 暫停令 + 綠色認證門檻高）

#### 泰國（唯一海外智慧製造案例）

**Delta Electronics 泰國 Bangpoo 廠案例（~2022–2023）：**
- CHT 角色：**技術顧問與系統整合**（非基礎設施擁有者）
- 5G 頻譜由泰國 AIS/True 持有，CHT 不直接部署基站
- 應用：AGV、AOI、AR 遠端協作、MEC 邊緣運算
- 這是 **CHT 海外智慧製造的唯一具名公開案例**

（來源：[BTW Media - CHT Thailand Profile](https://btw.media/all/company-stories/profiles/chunghwa-telecom-thailand-a-pioneer-of-connectivity-in-thailand/)）

### 2.3 CHT 「隨台商出海」策略

**核心邏輯：** 台商在台灣用 CHT 的企業網路 → 去東南亞設廠 → CHT 提供跨國專線串接台灣總部和海外廠。

**實際服務內容：**
- 跨國 MPLS VPN / SD-WAN
- 海外 IDC co-location
- 統一帳單與 SLA 管理
- 資安延伸服務

**已知客戶類型（多數未具名）：**
- PCB 廠（臻鼎-鵬鼎、欣興）在泰越工廠
- 紡織業（儒鴻）越南廠
- 半導體封測台商海外廠
- 台資銀行海外分行

（來源：中華電信法說會簡報；[CHT 2025 海纜投資加碼至 20 億新台幣](https://www.cht.com.tw/)）

### 2.4 海底電纜資產

CHT 參與的主要海纜系統：

| 海纜 | 路由 | 與東南亞的關聯 |
|------|------|--------------|
| **SJC2** | 新加坡↔泰國↔柬埔寨↔越南↔香港↔台灣↔日本（11 登陸站，10,500km） | 直接連接 SEA 主要市場 |
| **APG** | 台灣↔日本↔韓國↔中國↔馬來西亞↔**新加坡**↔泰國↔越南 | 覆蓋全東南亞 |
| **APCN-2** | 台灣↔日本↔韓國↔中國↔香港↔馬來西亞↔**新加坡** | |
| **SJC** | **新加坡**↔香港↔日本 | |
| **TPE** | 台灣↔美國（跨太平洋） | 間接相關 |
| **NCP** | 台灣↔美國（新太平洋） | 間接相關 |

> 📌 **這是 CHT 最不可替代的資產。** 遠傳和台哥大沒有自有海纜，NTT/Singtel 雖有海纜但沒有台灣端的最後一哩。CHT 是唯一能做到「台灣工廠到東南亞工廠端到端 SLA」的台灣業者。

---

## 3. 馬來西亞市場評估

### 3.1 半導體生態系統

- 檳城擁有 **350+ 家跨國工廠** + **4,000+ 家配套中小企業**
- 佔馬來西亞封裝測試產能約 **80%**
- 全球 OSAT 產出約 **13%**
- 2023 年檳城外資投資創紀錄達 **128 億美元**
- 僅 **18%** SME 採用工業 4.0（意味著 82% 仍用 Excel + 電話）

（來源：[SEMI - Penang: Silicon Valley of the East](https://www.semi.org/en/sea-newsletter-penang-the-silicon-valley-of-the-east)）

**在檳城的主要台商封測廠：**
- 日月光 ASE
- 力成科技 Powertech
- 京元電子 KYEC
- 南茂科技 ChipMOS

### 3.2 法規環境（2025–2026 最新）

#### 5G 現況

- **2024/12/31：** DNB 單一批發壟斷正式終止
- **U Mobile** 被選為第二個 5G 網路營運商（與華為、中興合作）
- 2025/08 U Mobile 啟用第二個 5G 網路
- 但實測 83.2% 用戶仍連 DNB 頻段，僅 16.8% 用 U Mobile 自有網路
- 5G 用戶從 2023/11 的 460 萬增至 2025/11 的 **2,870 萬**
- CelcomDigi 和 Maxis 已收購 DNB 股份，推動全面私有化

（來源：[TechWire Asia - Malaysia 5G Reality Check](https://techwireasia.com/2026/01/malaysia-5g-speeds-drop-dual-network-2025/)；[SoyaCincau](https://soyacincau.com/2025/01/02/govt-revoke-dnb-5g-single-wholesale-network-status/)）

> ⚠️ **對 ChainSight 的影響：** 5G 雙網過渡期混亂，CHT 作為外商更不可能取得頻譜或合作機會。進一步印證「不要把 5G 當核心賣點」。

#### PDPA 個資法（2024 修正案）

三階段生效：
- **2025/01：** 行政變更
- **2025/04：** 「資料控制者」概念、生物辨識資料納入敏感個資、跨境傳輸新規
- **2025/06：** **強制任命 DPO**、**72 小時資料外洩通報**、資料可攜權、罰款上限提高至 **RM 1,000,000**、刑期上限 3 年

（來源：[DLA Piper - Malaysia PDPA Guidelines](https://privacymatters.dlapiper.com/2025/03/malaysia-guidelines-issued-on-data-breach-notification-and-data-protection-officer-appointment/)；[Chambers - Data Protection 2026 Malaysia](https://practiceguides.chambers.com/practice-guides/data-protection-privacy-2026/malaysia/)）

#### NIMP 2030

- 2023/09 發布，Phase 1（2023–2026）、Phase 2（2027–2030）
- 2026 年底進行中期檢討
- **新激勵框架（NIF）** 2026/03/01 生效，從「活動導向」轉為「成果導向」
- 目標：製造業 GDP 年增 6.5%，至 2030 年貢獻 RM 5,875 億

（來源：[MIDA - New Incentive Framework](https://www.mida.gov.my/media-release/new-incentive-framework-nif/)）

### 3.3 馬來西亞結論

**仍應為主戰場，但理由不是「CHT 有子公司」，而是：**

1. **4,000+ SME × 82% 未數位化** = 東南亞最大需求池
2. A 端（台商封測大廠）和 B 端（SME 供應商）**在同一個 50km 半徑**
3. NIMP 2030 × 台灣新南向 = 最強政策敘事
4. 工程師缺口（需 6 萬名，年產 5 千）= AI 的最強理由

**主要風險：** CHT 馬來西亞團隊極小（~10-30 人）、無電信執照、無合作電信商、5G 不可行

---

## 4. 越南市場評估

### 4.1 電信法規

- **2024/07/01** 新《電信法》生效，**2024/12/24** 頒布 Decree 163 施行細則
- 基礎電信外資持股上限 **51%**（CPTPP 成員可放寬至 65%，但台灣非 CPTPP 成員）
- 雲端/資料中心服務 **無外資限制**，可 100% 外資
- M2M/IoT 歸類為基礎電信服務，納入監管
- 私有 5G 頻譜僅 **30 MHz** 供企業使用，審批繁複

（來源：[Vietnam Briefing - Decree 163](https://www.vietnam-briefing.com/news/vietnam-introduces-decree-163-guidelines-for-implementing-the-2024-telecommunications-law.html/)；[KPMG - Vietnam Telecom Law](https://kpmg.com/vn/en/home/insights/2024/02/in-depth-look-into-new-law-on-telecoms-of-vietnam.html)）

### 4.2 資料主權

- **Decree 53/2022（網路安全法施行細則）：** 資料在地化為**條件觸發式**（非全面強制），僅在企業被認定違反網路安全法規且不配合時才觸發
- **Decree 13/2023（個人資料保護）：** 跨境傳輸個人資料須影響評估 + 60 天內向公安部報備
- **製造業生產數據**（機台、良率、產能）若不涉及個資，不直接受限
- 目前執法力度仍較寬鬆，但趨勢是逐步收緊

（來源：[ITIF - Vietnam Data Localization](https://itif.org/publications/2025/03/07/vietnam-data-localization-regulation/)；[DLA Piper - Vietnam Decree 13](https://www.dlapiper.com/en-us/insights/publications/crossroads-icr-insights/2023/vietnam-decree-13-and-the-new-regulations-on-personal-data-protection)；[Freshfields - Data Localisation Vietnam](https://technologyquotient.freshfields.com/post/102iulg/data-localisation-in-vietnam-highlights-under-decree-53-and-decree-13)）

### 4.3 半導體產業

| 企業 | 投資額 | 所在地 | 業務 |
|------|--------|--------|------|
| **Intel** | 15 億美元（累計） | 胡志明市 | 封測（全球約一半封測量） |
| **Samsung** | 26 億美元（累計） | 太原省 | 半導體零組件 |
| **Amkor** | 16 億美元 | 北寧省 | 先進封裝（SiP），聚焦 AI 晶片/HBM |
| **Hana Micron** | ~9.3 億美元 | 北寧省 | OSAT |
| **FPT Semiconductor** | — | 北寧 | 本土首座 OSAT 工廠（2026 宣布） |
| **Viettel** | — | 河內 | 首座晶圓廠（2026/01 開工） |

產業規模：約 50 家設計公司、15 家封測廠、6,000 名工程師（目標 2030 達 50,000 名）

（來源：[SEMI - Vietnam Semiconductor Pivot](https://www.semi.org/sea/blogs/Vietnams-Semiconductor-Pivot)；[TrendForce - Vietnam Packaging & Testing](https://www.trendforce.com/news/2025/05/16/news-vietnams-semiconductor-packaging-testing-industry-picks-up-steam/)；[Vietnam Briefing - Semiconductor Industry](https://www.vietnam-briefing.com/news/vietnam-semiconductor-industry.html/)）

### 4.4 CHT 在越南的優勢

- Viettel-CHT 合資 **13+ 年**，是 CHT 在東南亞最成熟據點
- Viettel 是越南最大電信商（軍方背景），有直接合作通道
- 雲端/IDC 服務已建立，河內 + 胡志明市都有資料中心
- 2021 年簽署公有雲合作、2023 年共同創立越南智慧城市聯盟（VSCC）

（來源：[BusinessWire - CHT Viettel Cloud](https://www.businesswire.com/news/home/20211114005315/en/)；[BusinessWire - CHT joins VSCC](https://www.businesswire.com/news/home/20230221005951/en/)）

### 4.5 越南主要風險

- **英語能力低**（EF EPI 第 63 名 vs 馬來西亞第 24 名），商務溝通需翻譯（[EF EPI 2025](https://www.humanresourcesonline.net/2025-ranking-english-proficiency-levels-around-asia)）
- **Tier 2-3 SME 生態系統不成熟**——半導體供應鏈仍以外資 FDI 主導，缺乏檳城那樣的本地供應商網絡
- 75% 製造業勞工缺乏工業 4.0 技能
- Viettel 軍方背景在部分外資企業資安審查中可能是負面因素
- Viettel-CHT 的智慧製造合作**停留在 MOU 層級**，無公開的工廠 IoT 部署案例

### 4.6 越南結論

**適合作為 Phase 2 重點，但不適合當主戰場：**
- CHT 基礎設施最深，但缺乏 SME 目標客戶密度
- 半導體生態系統快速成長中，2–3 年後可能更成熟
- 建議定位：利用 Viettel-CHT 基礎，鎖定 Amkor/Hana Micron 供應鏈

---

## 5. 新加坡市場評估

### 5.1 法規環境

- **外資電信限制：無。** 外國公司可 100% 持有電信牌照（[IMDA](https://www.imda.gov.sg/)）
- **PDPA：** 主要規範個人資料；工廠機器數據/設備感測數據**不受 PDPA 直接約束**
- **跨境傳輸：最寬鬆。** 無強制資料在地化，合約約束即可
- 已加入 **APEC CBPR** 跨境隱私規則體系
- IMDA 開放企業申請**私有 5G 頻譜**（3.5GHz + mmWave），是三國中唯一真正可行的 5G 私網環境

### 5.2 半導體產業

- 全球約 **11% 的晶圓產能**位於新加坡
- 主要是**前段製造**（晶圓代工），非後段封測
- 關鍵業者：GlobalFoundries、Micron（3 座晶圓廠）、UMC、STMicroelectronics、SSMC（NXP/TSMC 合資）
- Tier 2-3 SME 僅 **200–400 家**（vs 檳城 4,000+）
- SME 偏向高附加價值（設計、IP、測試方案），非勞力密集型

（來源：[ASEAN-BAC - SEA Semiconductor Supply Chain](https://asean-bac.org/news-and-press-releases/how-vietnam-malaysia-and-singapore-are-shaping-asean-s-semiconductor-supply-chain-potential)）

### 5.3 政府補貼（對 ChainSight 客戶有利）

| 計畫 | 內容 | 對 ChainSight 的意義 |
|------|------|---------------------|
| **PSG（Productivity Solutions Grant）** | 補貼最高 **50%** 數位化方案費用 | 可申請成為預批准方案，降低 SME 導入門檻 |
| **EDG（Enterprise Development Grant）** | 企業升級轉型補助 | 客戶可申請資助導入 IoT 平台 |
| **RIC（Research & Innovation Credit）** | 設備和研發補貼最高 50% | |
| **EIS（Enterprise Innovation Scheme）** | 首 SGD 40 萬研發支出享 **400% 稅扣** | |
| **5G Innovation Programme** | 5G 企業應用試驗 | 可申請 5G + IoT 場域 PoC |

（來源：[EY - Incentives in ASEAN 2025](https://www.ey.com/content/dam/ey-unified-site/ey-com/en-sg/services/tax/documents/ey-sg-incentives-in-asean-07-2025.pdf)）

### 5.4 新加坡結論

**適合作為「展示窗口 + 區域總部」，不適合當營收主力：**
- SME 太少（200–400 家），市場規模不支撐
- 但法規最友善、補貼最高、可做燈塔案例
- 建議：與 1–2 家大廠（GlobalFoundries、Micron）做 PoC，作為向檳城客戶展示的背書
- 營運成本極高（人力、租金為三國中最高）

---

## 6. 三國比較總表

| 面向 | 馬來西亞（檳城） | 越南 | 新加坡 |
|------|----------------|------|--------|
| **半導體 SME 數量** | **4,000+** | 較少，生態系建構中 | 200–400 |
| **工業 4.0 採用率** | **僅 18%（最大痛點）** | ~36% 用 IoT，75% 缺技能 | 大廠成熟，SME 仍在 2.0–3.0 |
| **CHT 據點規模** | 10–30 人（最新、最小） | **100–200 人（最成熟）** | 30–60 人 |
| **CHT 合作電信商** | ❌ 無 | ✅ Viettel（13 年合資） | 有 Singtel 互連 |
| **5G 專網可行性** | ❌ 無頻譜、DNB 混亂 | ⚠️ 僅 30MHz、審批繁複 | ✅ IMDA 開放申請 |
| **資料跨境傳輸** | 趨嚴（PDPA 修正案） | 條件式在地化，趨嚴 | **最寬鬆** |
| **英語能力** | **亞洲最高（EF #24）** | 低（EF #63） | 母語級 |
| **營運成本** | 中等 | **最低** | 最高 |
| **政策對齊** | **NIMP 2030 × 新南向** | 半導體國家策略 2030 | SIRI + National AI 2.0 |
| **營商便利度** | 中上 | B-READY #17 | **B-READY #1** |
| **政府補貼** | NIF + ICT 加速扣除 | 稅務假期 | **PSG 50% + EIS 400%** |
| **建議定位** | **Phase 1 主力營收** | **Phase 2 重點擴展** | **燈塔展示 + 區域 HQ** |

---

## 7. 5G 必要性分析

### 7.1 ChainSight 三模組的連線需求

| 模組 | 功能 | 數據特性 | 實際需要的連線 | 需要 5G 嗎？ |
|------|------|---------|--------------|------------|
| **Pulse** | 即時 OEE、機台狀態分類 | 感測器時序數據，每秒幾 KB | 工廠內網 Wi-Fi 6 / 有線 | ❌ |
| **Predict** | 預測性維護、交期預測 | 歷史數據批次訓練 + Edge 推論 | 不需要即時連線 | ❌ |
| **Comply** | 合規報表自動生成 | 文件處理，非即時 | 一般網路 | ❌ |
| **跨境傳輸** | 台灣總部監控海外廠 | 彙總指標，非原始數據 | CHT SD-WAN / MPLS | ❌ |

### 7.2 5G 的真正優勢場景 vs ChainSight 場景

| 5G 優勢 | 適用場景 | ChainSight 需要嗎？ |
|---------|---------|-------------------|
| 超低延遲（<1ms） | 自駕車、遠端手術、即時機器人控制 | ❌ 感測器上傳不需 1ms |
| 大量設備同時連線 | 智慧城市萬物互聯 | ⚠️ 單一 SME 工廠設備數有限，Wi-Fi 6 可承載 |
| 高頻寬 | 8K 影像即時傳輸、AR/VR | ❌ OEE 數據量極小 |

### 7.3 5G 在提案中造成的問題

1. **可行性破口：** 馬來西亞/越南都拿不到頻譜，評審會直接質疑
2. **搶焦點：** 評審搞不清你到底是賣 5G 還是賣 AI
3. **成本過高：** SME 裝不起 5G 設備，與「B 端免費部署」的商業模式矛盾
4. **CHT 無法交付：** 在東南亞沒有 5G 頻譜和基站部署能力

### 7.4 建議的連線架構

```
工廠內（SME 端）          跨境傳輸                台灣總部（A 端）
┌────────────────┐      ┌──────────────┐      ┌──────────────┐
│ Wi-Fi 6/6E     │      │ CHT SD-WAN   │      │ ChainSight   │
│ + Edge Gateway │ ───→ │ + 海底電纜    │ ───→ │ Dashboard    │
│ （研華硬體）    │      │ （CHT 獨佔）  │      │ （雲端/IDC） │
└────────────────┘      └──────────────┘      └──────────────┘
                                                     ↑
                                              CHT 台灣 IDC
                                              30+ 座機房
```

> **5G 在提案中的正確位置：** 僅作為一句話提及——「Phase 3 當合作電信商到位後，可升級為 5G 專網以支援更高密度部署」。

---

## 8. CHT 真正的護城河與能力缺口

### 8.1 不可替代的優勢

| 優勢 | 為什麼別人做不到 |
|------|----------------|
| **14+ 條海底電纜** | 遠傳/台哥大無自有海纜；NTT/Singtel 沒有台灣端最後一哩 |
| **台商信任關係** | 台灣 50%+ 企業已是 CHT 客戶，語言/文化/合約連續性 |
| **台灣端網路品質** | 國際專線從台灣出發，CHT 端到端 SLA 最優 |
| **資安認證** | 台灣最完整的 SOC + 政府核定資安服務資格 |
| **東南亞唯一台灣電信商** | 遠傳和台哥大沒有東南亞據點 |

### 8.2 明確的能力缺口

| 缺口 | 影響 | 解法 |
|------|------|------|
| **工廠 OT 整合**（PLC/SCADA/MES） | CHT 是 IT 公司，非 OT 公司 | 與**研華 Advantech** 合作（已有台灣合作基礎） |
| **製造業 AI** | 無現成產品 | 自建或與 AI 新創合作；這正是提案要提出的新價值 |
| **馬來西亞本地部署** | 團隊僅 10–30 人 | 需與當地 SI 或電信商（CelcomDigi/TM）合作 |
| **非台商客戶關係** | 碰不到 Intel/Infineon | **A 端鎖定台商（ASE/力成/京元電）而非外商** |
| **iEN 的工廠適用性** | iEN 是建築 BEMS，非工廠平台 | 不要在提案中宣稱 iEN 是工廠解決方案 |

### 8.3 競爭態勢

| 競爭者 | 優勢 | 劣勢 | 威脅程度 |
|--------|------|------|---------|
| **NTT** | 全球規模、成熟 IoT 平台、SEA 完整據點 | 對台商理解不如 CHT | 🔴 高 |
| **Singtel** | SEA 本地基礎設施最完整 | 不專注台商、不熟台灣半導體 | 🟡 中 |
| **PTC / Siemens** | 工業 IoT 平台技術最深 | 不提供網路連線 | 🟡 中（互補） |
| **AWS IoT / Azure IoT** | 雲原生平台、全球覆蓋 | 無台灣端優勢、無電信基礎設施 | 🔴 高（長期） |
| **遠傳 / 台哥大** | 台灣市場有競爭力 | **無東南亞據點** | 🟢 低 |

---

## 9. 對提案的具體修訂建議

### 9.1 核心定位修正

| 項目 | ❌ 原本 | ✅ 建議改為 |
|------|--------|-----------|
| 標題定位 | 「AI 原生 5G」 | 「AI 驅動的跨境供應鏈可視化」 |
| CHT 角色 | 「5G 專網 + iEN IoT 平台」 | 「跨境安全網路（海纜 + SD-WAN）+ AI 數據中台」 |
| A 端客戶 | Intel、Infineon 等外商 | **在檳城設廠的台商（ASE、力成、京元電、台達）** |
| 連線方案 | 5G 專網 | Wi-Fi 6/6E + Edge（廠內）+ CHT SD-WAN（跨境） |
| 不可替代性 | 5G 頻譜 + iEN | 14 條海纜 + 台商唯一跨境 ICT 夥伴 + 資安 |
| 合作模式 | CHT 獨立交付 | CHT（網路+資安）× 研華（Edge/IoT）× AI 夥伴 |

### 9.2 最強故事線

> 台灣半導體大廠南向設廠（ASE 檳城、力成檳城...），需要即時掌握海外 3,000+ 家 SME 供應商的生產狀態。CHT 是**唯一在東南亞有據點、有 14 條海底電纜、有台商信任基礎的台灣電信商**。ChainSight 不是從零建 5G 網路，而是在 CHT 已有的跨境網路上加 AI 層，讓台灣總部即時看到檳城工廠的供應鏈。**台商南向的數位臍帶。**

### 9.3 市場策略

```
Phase 1 (M1–12)   → 馬來西亞檳城（主力營收，4,000+ SME，台商 A 端）
Phase 2 (M10–18)  → 越南（Viettel-CHT 基礎，鎖定 Amkor/Hana Micron 供應鏈）
Phase 2 同步       → 新加坡（1–2 燈塔案例，PSG 補貼，區域 HQ）
Phase 3 (M18+)    → 泰國/柔佛/吉打（複製 playbook）
```

---

## 10. 研究組員分工建議

基於以上研究，以下是建議的研究優先級和分工：

### 🔴 最高優先（直接影響提案能否站住腳）

#### 任務 A：馬來西亞台商封測廠調查
**為什麼重要：** A 端客戶從 Intel 改為台商後，需要確認檳城到底有哪些台商封測廠、規模多大、他們管理 SME 供應商的現狀。

**需要查的：**
- 日月光 ASE 檳城廠的規模（員工數、產能、供應商數量）
- 力成、京元電、南茂在檳城的具體據點
- 這些台商目前怎麼管理當地 SME 供應商（用什麼系統？人工？email？）
- 他們在台灣是否已經用 CHT 的企業服務

#### 任務 B：Wi-Fi 6 + Edge 的工廠 IoT 架構可行性
**為什麼重要：** 拿掉 5G 後，需要證明 Wi-Fi 6 + Edge 完全能滿足 ChainSight 的需求。

**需要查的：**
- Wi-Fi 6/6E 在工廠環境的實際部署案例（特別是半導體封測廠）
- Edge Gateway 設備選型（研華有哪些產品適用？成本？）
- 與 5G 方案的具體成本比較
- 有沒有 Wi-Fi 6 在 SME 工廠的成功案例可引用

#### 任務 C：量化 A 端 ROI
**為什麼重要：** 這是 "待解決問題與風險盤點" #4 指出的核心問題——大廠為什麼要掏錢。

**需要查的：**
- 半導體封測業的供應鏈中斷成本（一次交期延遲 = 多少錢？）
- 人工追蹤 vs 即時可視化的效率差異（有沒有產業報告？）
- 類似解決方案的 ROI 案例（如 Flex、Jabil 的供應鏈數位化成效）
- 馬來西亞工程師薪資（量化「AI 取代人工追蹤」的節省）

### 🟡 次高優先（讓提案更有深度）

#### 任務 D：AI 模組冷啟動方案
**為什麼重要：** "待解決問題與風險盤點" #5 指出 AI 價值主張太模糊，評審一定會問「初期沒有歷史數據怎麼做 AI？」

**需要查的：**
- 預測性維護的開源數據集或遷移學習方案
- 類似場景的冷啟動策略（rule-based → ML 漸進式）
- 具體的模型選型與準確率參考文獻

#### 任務 E：CHT × 研華合作可能性
**為什麼重要：** CHT 缺乏工廠 OT 能力，研華（Advantech）是最自然的合作夥伴。

**需要查的：**
- CHT 和研華現有的合作關係（台灣有哪些共同案例）
- 研華在東南亞的據點和工廠 IoT 產品線
- 研華的 Edge Gateway / WISE-PaaS 平台與 ChainSight 的整合可能

#### 任務 F：競品分析
**為什麼重要：** 評審會問「市場上有沒有類似的東西？你跟他們有什麼不同？」

**需要查的：**
- Flex/Jabil 的供應鏈可視化系統
- SAP Ariba / SAP IBP 在半導體供應鏈的應用
- 東南亞有沒有本地的供應鏈可視化新創
- PTC ThingWorx / Siemens MindSphere 在封測廠的部署

### 🟢 加分項（時間允許再做）

#### 任務 G：ESG/合規法規細節
- RBA（Responsible Business Alliance）對半導體供應商的具體要求
- CSRD（歐盟企業永續報告指令）對東南亞供應鏈的影響時程
- 馬來西亞 OSH Act 的工廠合規要求

#### 任務 H：越南/新加坡的 Phase 2 具體規劃
- Amkor 北寧廠的供應鏈結構
- 新加坡 PSG 申請流程和時間表

### 建議人力分配

| 組員 | 建議負責 | 理由 |
|------|---------|------|
| **組員 1** | 任務 A + E（台商調查 + 研華合作） | 需要查台灣企業資訊，可能需要中文資源 |
| **組員 2** | 任務 B + D（技術架構 + AI 冷啟動） | 需要技術背景 |
| **組員 3** | 任務 C + F（ROI 量化 + 競品分析） | 需要商業分析能力 |
| **全員協作** | 任務 G + H | 在主要任務完成後一起做 |

> ⚠️ **不建議花大量時間研究越南或新加坡的細節。** Phase 1 聚焦馬來西亞，如果馬來西亞的故事說不通，Phase 2-3 更不可能成立。先把任務 A/B/C 做好。
