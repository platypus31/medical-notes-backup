---
tags: [疾病, 心臟內科, CV, 值班]
aliases: [Pacemaker, 心律調節器, PPM, TPM]
type: disease
status: 🌿growing
sources_reviewed: 2026-07-06
---
# Pacemaker（心律調節器）

> [!abstract] 一句話：以電極導線持續監測心律、在心跳過慢時放電**奪獲（capture）**心肌的植入式裝置。值班最關鍵：看到 pacing spike 要判斷「有沒有 capture、有沒有 sense」，並記得 **magnet 一放上去就變固定頻率 asynchronous 起搏**。

> [!danger] 🚨 值班紅旗
> 1. **Pacemaker 病人心搏過慢／暈厥** → 先看 ECG 有無 **failure to capture**（有 spike 無 QRS）或 **failure to sense**（該抑制卻放電）；battery/lead 問題會致命性心搏過緩。
> 2. **依賴起搏器（pacemaker-dependent）的病人要進行電燒／電刀手術或 MRI** → 需先廠商程控改為 asynchronous 模式或放 magnet，否則電磁干擾（EMI）被誤 sense → **抑制放電 → asystole**。
> 3. **床邊急救放 magnet**：magnet 讓幾乎所有 PPM 轉為 **VOO/DOO 固定頻率 asynchronous**（不再 sense），可救「EMI 抑制 / oversensing 造成的停搏」；但對 **ICD** 放 magnet 是「**暫停抗心搏過速電擊治療**」而非改起搏模式——別搞混。
> 4. **Pacemaker syndrome**（VVI 起搏、房室不同步）→ 頸部搏動感、疲倦、低血壓，需升級為雙腔（DDD）。
> 5. 新植入後**突發胸痛＋低血壓＋頸靜脈怒張** → 疑 lead 穿孔造成 **心包填塞**，做床邊 echo。

## 📖 定義 / 病生理（這是什麼）
- **原理**：脈衝產生器（脈衝＋電池）＋導線電極，感知（sense）自身心律，於低於設定頻率時放電**起搏（pace）**心肌去極化。
- **NBG 起搏碼（前三碼最常用）**：

  | 第 I 碼 起搏腔 | 第 II 碼 感知腔 | 第 III 碼 反應 |
  | --- | --- | --- |
  | O 無 / A 心房 / V 心室 / D 雙腔 | O / A / V / D | O 無 / T 觸發 / I 抑制 / D（T+I） |

  - **VVI**：只起搏並感知心室，感知到自身心跳則抑制（適用永久性 AF 併心搏過緩）。
  - **DDD**：房室雙腔感知與起搏，維持房室同步（適用竇房結病變＋房室阻滯）。
  - **AAI**：只起搏心房（適用單純竇房結功能不良、房室傳導正常）。
- **暫時性 vs 永久性**：
  - **暫時性（TPM）**：經靜脈或**體外經皮（transcutaneous）**，用於可逆性心搏過緩、橋接（如急性心肌梗塞併房室阻滯、藥物中毒）。
  - **永久性（PPM）**：長期植入。

## 🩺 臨床表現（症狀 / 徵象）
> 連症狀卡 [[Syncope(昏厥)]]、[[Bradycardia(心搏過緩)]]
- 植入前：心搏過緩相關症狀——暈厥、頭暈、運動不耐、疲倦。
- 起搏器功能異常：暈厥復發、心搏過緩、心悸（起搏介導心搏過速 PMT）、Pacemaker syndrome（房室不同步之疲倦低血壓）。

## 🔬 診斷（診斷標準 / 要開的檢查影像）
> 檢查 [[ECG(心電圖)]]、[[Pacemaker interrogation(起搏器程控)]]　影像 [[CXR(胸部X光)]]、[[Echocardiography(心臟超音波)]]
- **ECG**：找 **pacing spike**；spike 後接寬 QRS（心室起搏，典型 LBBB 形態）或 P 波（心房起搏）。
  - **Failure to capture**：有 spike 但其後無對應 QRS/P。
  - **Failure to sense（undersensing）**：不該放電時放電（spike 落在自身 QRS/T 上）。
  - **Oversensing**：把 T 波或雜訊誤當心跳 → 該放電卻抑制 → 停搏。
- **CXR**：確認導線位置、有無移位／斷裂、氣胸。
- **裝置程控（interrogation）**：讀電池電量、閾值、lead 阻抗、心律事件記錄——功能異常標準做法。

## ⭐ 特徵 / 注意（pearls & pitfalls，易漏易考）
- **看到規律寬 QRS 前有小 spike** → 心室起搏心律，勿誤判為室速。
- **心室起搏 ECG 呈 LBBB 形態** → 此時判讀心肌缺血要用 **Sgarbossa criteria**（同一般 LBBB）。
- **Magnet 效應**：PPM 放 magnet → asynchronous 固定頻率起搏；ICD 放 magnet → 暫停抗心搏過速治療（不影響起搏）。手術電刀前務必分清病人是 PPM 還是 ICD。
- **MRI**：僅「MRI-conditional」裝置且完成程控才可進，否則屬禁忌。

## 💊 治療（Acute / Chronic）
> 用藥 [[Atropine]]、[[Isoproterenol]]（等待起搏時的橋接）
- 適應症
> [!PDF|yellow] [[長庚銀蛋口袋書(印).pdf#page=99&selection=124,0,150,7&color=yellow|長庚銀蛋口袋書(印), p.99]]
> > 下列病人應該裝心律調節器：
> > 第三級（完全）[[醫學/11心電圖判讀/AtrioVentricular Block(房室傳導阻滯疾病)]] 
> > 有症狀的第二級[[醫學/11心電圖判讀/AtrioVentricular Block(房室傳導阻滯疾病)]]（Mobitz type II）
> > 有症狀的[[醫學/11心電圖判讀/Sinus Bradycardia(竇性心搏過緩)]]（[[Sick sinus syndrome(病竇症候群)]]） 
> > [[Acute Myocardial infarction(急性心肌梗塞)]]的病人，突然發生各種[[醫學/11心電圖判讀/AtrioVentricular Block(房室傳導阻滯疾病)]]或[[醫學/11心電圖判讀/Bundle Branch Block(束支傳導阻滯)]]（只需暫時性的心律調節器）
> > 反覆發作的[[醫學/11心電圖判讀/Sinus Tachycardia(竇性心搏過速)]]

### 永久性起搏器（PPM）主要適應症（2018 ACC/AHA/HRS）
- **完全性（三度）房室阻滯**（症狀性或逸搏過慢）。
- **有症狀的 Mobitz II 型二度房室阻滯**。
- **有症狀的病竇症候群（sick sinus syndrome）**、症狀性竇性心搏過緩、tachy-brady 症候群。
- **CRT（雙心室起搏）**：HFrEF（EF ≤35%）＋LBBB＋QRS ≥150 ms 且藥物治療下仍有症狀。

### 急性心搏過緩橋接（等植入時）
- **Atropine 0.5 mg IV**，每 3–5 分鐘可重複（max 3 mg）——對房室結以下阻滯（Mobitz II、三度）效果差。
- **Transcutaneous（經皮）pacing** 或 **Isoproterenol／dopamine／epinephrine 輸注**維持心率。

## ⚠️ 併發症
- **植入相關**：氣胸、血胸、導線移位、**心臟穿孔／心包填塞**、囊袋血腫、感染（裝置相關心內膜炎）。
- **長期**：lead 斷裂／絕緣破損、閾值上升、**Pacemaker syndrome**、**起搏器介導心搏過速（PMT）**、鎖骨下靜脈栓塞、Twiddler 症候群（病人玩弄脈衝產生器致導線移位）。
- **裝置感染**：常需完整移除整套系統。

## 📊 嚴重度評分 / 風險分層（scoring）
> 起搏器本身無評分；適應症決策依房室阻滯分級與 CRT 條件（EF/QRS/LBBB）
| 評分 / 分層 | 用途 | 意義 |
| --- | --- | --- |
| AV block 分級（I / Mobitz I / Mobitz II / 三度） | 判斷是否需 PPM | Mobitz II 與三度→需 PPM |
| CRT 條件（EF ≤35% + LBBB + QRS ≥150 ms） | 判斷雙心室起搏適應症 | 條件齊全獲益最大 |

## 🔗 相關
- 適應症疾病：[[AtrioVentricular Block(房室傳導阻滯疾病)]]、[[Sick sinus syndrome(病竇症候群)]]、[[Sinus Bradycardia(竇性心搏過緩)]]、[[Heart Failure(心臟衰竭)]]
- 相關裝置：[[ICD(植入式去顫器)]]、[[CRT(心臟再同步治療)]]
- 併發：[[Cardiac tamponade(心包膜填塞)]]、[[Infective Endocarditis(感染性心內膜炎)]]、[[Pneumothorax(氣胸)]]
- 急救用藥：[[Atropine]]、[[Isoproterenol]]

## 📚 來源
[^1]: Kusumoto FM, et al. **2018 ACC/AHA/HRS Guideline on the Evaluation and Management of Patients With Bradycardia and Cardiac Conduction Delay.** *Circulation.* 2019;140(8):e382–e482. PMID: 30586772
[^2]: Glikson M, et al. **2021 ESC Guidelines on cardiac pacing and cardiac resynchronization therapy.** *Eur Heart J.* 2021;42(35):3427–3520. PMID: 34455430
[^3]: 長庚銀蛋口袋書(印), p.99（起搏器適應症原始摘錄）
