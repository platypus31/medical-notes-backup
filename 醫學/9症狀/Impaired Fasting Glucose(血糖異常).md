---
tags: [症狀, 科別/內分泌新陳代謝科, 科別/急診醫學科]
aliases: [Impaired Fasting Glucose, IFG, 血糖異常, 高血糖, 低血糖, Dysglycemia]
type: symptom
status: 🌱seedling
sources_reviewed: 2026-07-03
---
# Impaired Fasting Glucose（血糖異常）

> [!danger] 🚨 紅旗警訊（must-not-miss，血糖異常先分「危及生命的三急症」）
> **助記「高兩低一」**：高血糖兩大急症 + 低血糖神經急症
> 1. **DKA（糖尿病酮酸血症）** → 高血糖 + 陰離子間隙代謝性酸中毒 + 酮體；深快呼吸（Kussmaul）、腹痛、脫水、意識改變。第一型 DM 或感染/停藥誘發
> 2. **HHS（高滲透壓高血糖症）** → 血糖常 >600 mg/dL、血漿滲透壓 >320、**無明顯酮酸**、嚴重脫水 + 意識改變。多見於老年第二型 DM，死亡率高於 DKA
> 3. **嚴重低血糖（<54 mg/dL 或意識改變）** → 交感興奮（冒冷汗、心悸、手抖）→ 神經低糖（虛弱、意識改變、抽搐、昏迷）；**任何意識改變病人先 stick 血糖**
> 4. ⚠️ 併發誘因不可漏：**Sepsis / AMI / 中風 / 胰臟炎** 都可能以血糖劇烈波動表現
>
> ⚡ **昏迷/意識改變 + 不明原因 → 先 fingerstick 血糖，低糖先推糖（D50），不要等抽血結果**

## 🔀 鑑別診斷 DDx（值班從這裡連到疾病）
| 疾病 | 支持特徵 | rule-out 線索 |
| --- | --- | --- |
| [[Diabetic Ketoacidosis(糖尿病酮酸血症)]] | 血糖多 250–600、pH<7.3、HCO₃⁻↓、酮體(+)、AG↑、Kussmaul 呼吸、腹痛 | pH/HCO₃⁻ 正常 + 血酮/尿酮(-) |
| [[Hyperosmolar hyperglycemic syndrome(高滲透壓高血糖症)]] | 血糖>600、滲透壓>320、**無酮酸**、重度脫水、老人意識改變 | 滲透壓正常 + 血糖未達極高 |
| [[Hypoglycemia(低血糖)]] | 血糖<70（<54 明確）、Whipple 三徵、推糖後緩解 | 血糖正常且症狀不隨糖改善 |
| [[Hyperglycemia(高血糖)]]（單純未達急症） | 血糖↑但無酸中毒/高滲透壓、多尿多渴 | — |
| 應激性高血糖 / 類固醇誘發 | 急性病、感染、類固醇/升壓劑使用中 | 誘因移除後回穩 |
| 新診斷 [[Diabetes Mellitus(糖尿病)]] | HbA1c↑、慢性多尿多渴體重減輕 | HbA1c 正常 |

> [!warning] DKA 可發生在血糖不高（<250）時 → **euglycemic DKA**（SGLT2 抑制劑、懷孕、飢餓、酒精），別因血糖不高就排除酮酸

## ❓ 問診 / 身體檢查重點
- **病史**：DM 型別、用藥（胰島素/口服藥/**SGLT2i**/類固醇）、是否停藥或漏打、最近感染/發燒、飲食與飲酒、多尿多渴、體重變化、意識程度
- **低血糖三問**：最後一餐時間、降糖藥劑量與時機、是否運動/飲酒/腎功能惡化（藥物蓄積）
- **關鍵理學**：意識（GCS）、脫水徵象（黏膜、皮膚張力、姿勢性低血壓）、Kussmaul 呼吸、酮味、腹部壓痛、感染灶（肺/尿/皮膚/足）
- **系統回顧找誘因**：發燒、咳嗽、排尿灼痛、胸痛（AMI 可誘發 DKA/HHS）

## 🩺 初步 workup（該開的檢查 / 影像）
> [!note] 黃金第一步：**fingerstick 血糖 + 靜脈血糖**，意識改變同步查血酮/血氣，別讓「等抽血」延誤推糖
- **血糖**（fingerstick + venous）、**血酮（β-hydroxybutyrate）或尿酮**
- **VBG/ABG**：pH、HCO₃⁻ → 判 DKA 酸中毒程度
- **電解質**：Na（校正）、**K（治療前後必追）**、AG 計算；BUN/Cr、血漿滲透壓
- **感染 workup**：CBC/DC、U/A、CXR、血/尿培養（找誘因）
- **ECG + Troponin**：K 異常心電圖變化 + 排除誘發性 AMI
- HbA1c（分辨急慢性）；懷疑胰臟炎加 lipase

## ⚡ 值班即時處置（穩定 vs 不穩定分流）
```mermaid
flowchart TD
    A["血糖異常病人"] --> B{"意識/生命徵象?"}
    B -->|意識改變/低糖| C["fingerstick 血糖"]
    C -->|低糖 <70| C1["清醒→口服糖<br/>意識差→D50 IV 或 glucagon<br/>15min 複測"]
    C -->|高糖| D{"酮酸 or 高滲透壓?"}
    D -->|DKA pH<7.3 酮(+)| E["IV fluid → 補 K(K≥3.3才給胰島素)<br/>→ regular insulin 輸注<br/>找誘因治療"]
    D -->|HHS 滲透壓>320 無酮酸| F["大量 IV fluid 為主<br/>緩慢降糖降滲透壓<br/>低劑量胰島素"]
    B -->|穩定 單純高糖| G["查誘因 + 依院內指引調糖<br/>HbA1c 評估慢性控制"]
```
- **低血糖**：清醒給 15g 口服糖（15-15 rule）；意識差/無法吞 → **D50W 20-50 mL IV** 或 glucagon 1 mg IM，15 min 複測；找根因（藥物蓄積、腎衰、飲酒、敗血症）
- **DKA**：① 先大量生理食鹽水；② **補 K**（K<3.3 先不給胰島素，否則致命性低血鉀）；③ regular insulin 輸注；④ 血糖降至 ~200 加葡萄糖續打胰島素直到 AG 關閉；⑤ 治療誘因
- **HHS**：以**輸液**為主軸、緩慢矯正（避免腦水腫/滲透壓驟降）、低劑量胰島素、補 K
- ⚠️ DKA/HHS 胰島素**劑量依院內指引**；別在低血鉀時給胰島素

## 📊 臨床評分 / 診斷分級（criteria）★本卡核心
> 高血糖急症靠「酸中毒 + 酮體 + 滲透壓」三軸定性與分級，不靠血糖絕對值

### ① DKA 嚴重度分級（ADA）
| 指標 | 輕度 | 中度 | 重度 |
| --- | --- | --- | --- |
| 動脈 pH | 7.25–7.30 | 7.00–7.24 | <7.00 |
| 血清 HCO₃⁻ (mEq/L) | 15–18 | 10–<15 | <10 |
| 陰離子間隙 AG | >10 | >12 | >12 |
| 血酮/尿酮 | (+) | (+) | (+) |
| 意識狀態 | 清醒 | 清醒/嗜睡 | 木僵/昏迷 |

> DKA 三要件：**血糖↑（多 >250，euglycemic 除外）＋ AG 代謝性酸中毒 ＋ 酮體(+)**

### ② DKA vs HHS 對照
| 項目 | DKA | HHS |
| --- | --- | --- |
| 血糖 | 多 250–600 | 常 >600 |
| pH / HCO₃⁻ | <7.3 / <18 | >7.3 / >18 |
| 血酮 | 中～大量 | 微量/無 |
| 有效滲透壓 | 變異 | **>320 mOsm/kg** |
| 意識 | 依酸中毒 | 常見明顯改變 |
| 典型族群 | 第一型/年輕、停藥感染 | 老年第二型、脫水 |

### ③ 低血糖 — Whipple 三徵（診斷成立需三項齊備）
| 項目 | 內容 |
| --- | --- |
| ① 症狀 | 交感（冒汗、心悸、手抖、飢餓）→ 神經低糖（意識改變、抽搐） |
| ② 低血糖值 | 記錄到血漿血糖偏低（<70；<54 明確有意義） |
| ③ 給糖緩解 | 血糖回升後症狀改善 |

## 🔗 相關
- 疾病：[[Diabetic Ketoacidosis(糖尿病酮酸血症)]]　[[Hyperosmolar hyperglycemic syndrome(高滲透壓高血糖症)]]　[[Hypoglycemia(低血糖)]]　[[Hyperglycemia(高血糖)]]　[[Diabetes Mellitus(糖尿病)]]
- 檢查：[[Blood Glucose(血糖)]]　[[Arterial Blood Gas(動脈血氣)]]　[[HbA1c(糖化血色素)]]
- 症狀：[[Altered Mental Status(意識改變)]]

## 📚 來源
[^1]: ADA Standards of Care — Hyperglycemic Crises in Adults（DKA/HHS diagnostic & severity criteria）
[^2]: Kitabchi AE et al. *Diabetes Care* — Hyperglycemic Crises in Adult Patients with Diabetes
[^3]: Whipple's triad — Endocrine Society Hypoglycemia guideline；Euglycemic DKA & SGLT2i — FDA/ADA warning

## 🎴 Flashcards & 自我測驗（Ollama qwen2.5:7b 自動生成 2026-07-03）
<!-- flashcard-gen:start -->

### 記憶卡（Spaced Repetition 相容 · `Q::A`）
紅旗警訊中高血糖兩大急症是哪兩個？::DKA、HHS

昏迷或意識改變病人首先應該做什麼？::fingerstick 血糖

低血糖的 Whipple 三徵包含哪些內容？::交感（冒冷汗等）、低血糖值、給糖緩解

DKA 的 pH 規範是什麼？::<7.3

HHS 的血漿滲透壓通常超過多少？::>320 mOsm/kg

DKA 和 HHS 在血糖上的區別是？::DKA 一般 <600，HHS 常 >600

DKA 的治療首選為何？::大量生理食鹽水

低血鉀時是否可以給胰島素？::不可以

HHS 治療中補液的目的是什麼？::緩慢矯正滲透壓，避免腦水腫

DKA 重度分級的 pH 下限是多少？::<7.00

### 自我測驗（選擇題，答案摺疊）
**Q1.** 患者血糖為 54 mg/dL，出現意識模糊，您首先應該做什麼？
- A. 立即靜脈注射 D50W 20-50 mL
- B. 設定警覺度，等待血糖結果
- C. 檢查是否有酮體和尿素氮
- D. 開始補液治療

> [!success]- 答案
> **A** — 根據紅旗警訊，昏迷或意識改變病人首先應該先 fingerstick 血糖。低血糖的 Whipple 三徵之一是意識改變，因此應立即靜脈注射 D50W 20-50 mL 穩定病情。

**Q2.** 患者血糖為 450 mg/dL，pH 7.18，血酮體 (+)，您應該如何分類？
- A. DKA
- B. HHS
- C. 高血糖
- D. 視症狀而定

> [!success]- 答案
> **A** — 根據紅旗警訊和臨床評分，患者血糖高於 250 mg/dL，pH 小於 7.3，血酮體 (+)，符合 DKA 的標準。

**Q3.** 患者血糖為 680 mg/dL，pH 7.45，無酮體，出現嚴重脫水和意識模糊，您應該如何處理？
- A. 大量補液並緩慢降糖
- B. 立即靜脈注射 D50W 20-50 mL
- C. 設定警覺度，等待血糖結果
- D. 先治療誘因

> [!success]- 答案
> **A** — 根據紅旗警訊和臨床評分，患者血糖高於 600 mg/dL，無酮體，出現嚴重脫水和意識模糊，符合 HHS 的標準。因此應該以大量補液為主軸，緩慢降糖並矯正滲透壓。

<!-- flashcard-gen:end -->
