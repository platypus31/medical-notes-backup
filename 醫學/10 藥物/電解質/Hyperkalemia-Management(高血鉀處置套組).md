---
tags: [藥理, 系統/電解質, 急救/高血鉀, 值班/救命卡]
aliases: [Hyperkalemia, 高血鉀, 高鉀血症, K+ high, 高血鉀處置, hyperK]
type: drug
class: 電解質急症整合處置卡（穩膜 → 移鉀入細胞 → 排鉀）
status: 🌱seedling
sources_reviewed: 2026-07-04
---
# Hyperkalemia Management（高血鉀處置套組）

> [!abstract] 一句話：**高血鉀是值班最常被 call 又最會致命的電解質急症**。處置三步驟（背下來）：**① 穩膜（Calcium）② 移鉀入細胞（Insulin+D50 / β-agonist / NaHCO3）③ 排鉀（利尿劑 / 陽離子交換樹脂 / 透析）**。前兩步是暫時性（分鐘～小時內把 K 藏起來、保護心臟），**只有第三步真正把鉀排出體外**。第一件事永遠是「看 EKG + 給鈣穩膜」，不是等抽血複驗。

> [!danger] 🚨 值班紅旗（接到高血鉀先想這 5 件事）
> 1. **先做 12 導程 EKG + 給鈣穩膜，不要空等複驗**：有 EKG 變化或 K ≥ 6.5 就當急症處理。Calcium **不降鉀**，只保護心肌 30–60 分鐘，爭取時間讓移鉀/排鉀起效。
> 2. **假性高血鉀（pseudohyperkalemia）先排除**：溶血檢體、握拳採血、檢體延遲送驗、血小板/白血球極高、抽血從打點滴那隻手抽到 KCl。**病人沒症狀 + EKG 正常 + 數字很高 → 重抽一管（不綁壓脈帶、不握拳、快速送驗）再說**，但別因此延誤真高血鉀的救命。
> 3. **Insulin 給了一定要跟 D50 並給並追蹤血糖**：低血糖是 insulin-glucose 降鉀最常見且危險的併發症，給藥後 1、2、4、6 小時測 BS（腎衰竭病人 insulin 清除慢，遲發低血糖可拖到數小時後）。
> 4. **Calcium 不可與 NaHCO3 走同一條 IV line**：會形成碳酸鈣沉澱。分開管路或中間沖洗。含鈣輸液遇 ceftriaxone 也會沉澱。
> 5. **Kayexalate（SPS）有腸壞死爭議**：尤其**術後、腸阻塞、腸蠕動差、與 sorbitol 併用**者，FDA 黑框警告腸道壞死。起效慢（數小時），**不是急救藥**；真正危急該走透析。腎衰竭無尿病人終極解方是**血液透析**。

## 🩺 決策流程（發現 K↑ → 怎麼一步步壓）

```
接到 K↑ 報告
   │
   ├─ 第一步：立刻做 12 導程 EKG ＋ 評估症狀（肌肉無力、心悸）
   │
   ├─ EKG 高血鉀進展（越後面越致命）：
   │     帳篷狀 T 波 (peaked T)     ← 最早
   │        ↓
   │     PR 延長、P 波變平/消失
   │        ↓
   │     QRS 增寬
   │        ↓
   │     QRS 與 T 融合 → 正弦波 (sine wave)  ← 瀕臨心室顫動/停搏
   │        ↓
   │     VF / asystole（心跳停止）
   │
   ├─ 有 EKG 變化 或 K ≥ 6.5 → 「急症」立即三步走：
   │
   │   ① 穩膜（心臟保護，最優先）：
   │       Calcium gluconate 10% 10 mL IV 慢推 2–3 分（心電監測下）
   │       ─ 若已 sine wave / 血流動力不穩 → 可用 Calcium chloride（含鈣多3x，需中央靜脈）
   │       ─ 5–10 分無改善可重複一次
   │
   │   ② 移鉀入細胞（暫時性，10–30 分起效）：
   │       Regular insulin 10 U IV ＋ D50W 50 mL IV（BS<250 才配糖，>250 可只給 insulin）
   │       ＋ β2-agonist 噴霧 salbutamol 10–20 mg nebulized
   │       ＋（僅代謝性酸中毒時）NaHCO3
   │
   │   ③ 排鉀（真正移除，數小時～）：
   │       Loop diuretic（furosemide，尿量夠才有效）
   │       陽離子交換樹脂（Kayexalate/Calcium polystyrene / 新藥 patiromer, SZC）
   │       血液透析（無尿/腎衰/藥物無效 → 終極手段）
   │
   └─ K 5.5–6.4 無 EKG 變化 → 以移鉀＋排鉀為主，找病因、停含鉀藥物
```

## 💊 適應症（處理哪種狀況）
- **急性高血鉀症**（K⁺ > 5.5 mmol/L，尤其 ≥ 6.5 或有 EKG 變化）
- 常見病因：**急/慢性腎衰竭（最常見）**、少尿/無尿、代謝性酸中毒（DKA）、橫紋肌溶解、腫瘤溶解症候群、大量輸血/溶血、藥物（ACEi/ARB、保鉀利尿劑 spironolactone、NSAID、trimethoprim、heparin）、腎上腺功能不全（Addison）
- 血流動力不穩、心律不整合併 K↑ → 依 ACLS 同步處理

## 📏 劑量 / 用法（成人）

| 步驟 | 藥物 | 劑量 / 用法 | 起效 / 持續 | 備註 |
| --- | --- | --- | --- | --- |
| ① 穩膜 | **Calcium gluconate 10%** | **10 mL IV** 慢推 2–3 分，心電監測；5–10 分可重複 | 1–3 分 / 30–60 分 | **不降鉀**，只保護心肌。周邊 IV 可用 |
| ① 穩膜 | Calcium chloride 10% | 5–10 mL IV（含元素鈣約 3 倍）需中央靜脈 | 同上 | 外滲會組織壞死，危急/CPR 才用 |
| ② 移鉀 | **Regular insulin** | **10 U IV** ＋ **D50W 50 mL IV** | 10–20 分 / 4–6 h | 降 K 約 0.5–1；⚠️追蹤血糖防低血糖 |
| ② 移鉀 | **Salbutamol（β2）** | **10–20 mg nebulized**（劑量遠高於氣喘常規） | 30 分 / 2 h | 降 K 約 0.5–1；心律快者慎用 |
| ② 移鉀 | NaHCO3 | 依酸鹼；**僅代謝性酸中毒**才給 | 慢 | 單獨降鉀效果差，勿與鈣同管 |
| ③ 排鉀 | **Furosemide** | 40 mg IV（依腎功能/尿量調整） | 需有尿量才有效 | 促尿排鉀 |
| ③ 排鉀 | **Calcium/Sodium polystyrene sulfonate（Kayexalate）** | 15–30 g PO / 30–60 g 灌腸 | 數小時（慢） | ⚠️腸壞死風險，非急救藥 |
| ③ 排鉀 | Patiromer / SZC（新型結合劑） | 依藥品仿單 | 較慢，慢性用 | 腸壞死風險較低，非急性首選 |
| ③ 排鉀 | **血液透析** | — | 最快最徹底 | 無尿/腎衰/藥物無效的終極手段 |

- **停掉所有升鉀來源**：KCl 點滴、含鉀輸液、ACEi/ARB、spironolactone、NSAID、trimethoprim、β-blocker（非選擇性）。
- **DKA 引起的高血鉀**：治療 DKA 本身（insulin + 補液）即會降鉀，且**補液後總體鉀常偏低**，需警覺後續低血鉀。

## ⚠️ 副作用（處置本身的風險）
- **Insulin + glucose**：**低血糖**（最常見、可遲發，尤其腎衰）→ 全程追 BS。
- **β2-agonist**：心悸、心搏過速、震顫；缺血性心臟病/心律不整慎用。
- **Calcium**：外滲組織壞死（CaCl 尤甚）、快推致心搏過緩/低血壓；洋地黃（digoxin）中毒者給鈣可能加重（傳統「stone heart」顧慮，現多認為 gluconate 慢推可接受，但需警覺）。
- **Kayexalate**：便秘、腸壞死（黑框）、低鉀、低鈣、低鎂、鈉負荷（Na 型）加重心衰/水腫。
- **NaHCO3**：鈉/容積負荷、代謝性鹼中毒、低血鈣（游離鈣下降）、與鈣沉澱。

## 🚫 禁忌 / 特別注意
- **假性高血鉀**未排除又病人穩定 → 先重抽，避免不必要的積極處置。
- **Digoxin 中毒併高血鉀**：給鈣需謹慎（傳統顧慮心肌僵直），此情境高血鉀本身反映毒性嚴重度，處置以 digoxin-specific antibody（Digibind）為主。
- **Kayexalate**：腸阻塞、術後腸蠕動未恢復、新生兒、與 sorbitol 併用 → 避免。
- **NaHCO3**：容積過載/嚴重心衰、代謝性鹼中毒、低血鈣時慎用；且**單獨降鉀證據弱**，只在酸中毒時輔助。

## 🔍 監測 / 交互作用 / 孕哺
- **監測**：連續心電圖（處置期間）、每 1–2 小時追 K⁺、insulin 後追血糖（1/2/4/6 h）、腎功能、尿量、酸鹼與其他電解質（Ca/Mg）。
- **交互作用（升鉀藥物）**：ACEi/ARB、spironolactone/eplerenone、amiloride、NSAID、trimethoprim（TMP-SMX）、heparin、非選擇性 β-blocker、tacrolimus/cyclosporine、digoxin（減鉀入細胞）。
- **孕哺**：處置藥物（鈣、insulin、glucose、β-agonist、透析）孕期皆可視情況使用；Kayexalate 孕期資料有限，急症以救命為先。

## 🔗 相關
- 組成藥物：[[Calcium Gluconate(葡萄糖酸鈣)]]、[[Potassium Chloride(氯化鉀KCl)]]（相反的低血鉀補充，警惕誤給）、[[Magnesium Sulfate(硫酸鎂)]]（常併存電解質異常）、[[Sodium-Bicarbonate-Acidosis(碳酸氫鈉-代謝性酸中毒)]]
- 排鉀相關：[[Furosemide(呋塞米)]]（若存在）
- 疾病：[[Acute Kidney Injury(急性腎損傷)]]、[[Diabetic Ketoacidosis(糖尿病酮酸中毒)]]、[[Tumor Lysis Syndrome(腫瘤溶解症候群)]]
- 對照：低血鉀（hypokalemia）處置

## 📚 來源
[^1]: UpToDate — Treatment and prevention of hyperkalemia in adults
[^2]: 2020 AHA ACLS — Life-threatening electrolyte abnormalities（高血鉀 stepwise 處置）
[^3]: FDA Boxed Warning — Sodium polystyrene sulfonate (Kayexalate) intestinal necrosis
[^4]: KDIGO / 內科學電解質章（EKG 進展序列：peaked T → wide QRS → sine wave）

## 🎴 Flashcards & 自我測驗
<!-- flashcard-gen:start -->

### 記憶卡（Spaced Repetition 相容 · `Q::A`）

高血鉀處置的三大步驟依序是什麼？::① 穩膜（Calcium）② 移鉀入細胞（Insulin+D50 / β-agonist / NaHCO3）③ 排鉀（利尿劑 / 陽離子交換樹脂 / 透析）

接到高血鉀報告的第一件事該做什麼？::立刻做 12 導程 EKG 並評估症狀；有變化或 K≥6.5 立即給鈣穩膜，不空等複驗

Calcium gluconate 在高血鉀的作用與劑量？::穩定心肌細胞膜、對抗心律不整（**不降鉀**）；10% 10 mL IV 慢推 2–3 分，心電監測下，5–10 分可重複；起效 1–3 分、持續約 30–60 分

高血鉀 EKG 變化由早到晚的順序？::帳篷狀 T 波 (peaked T) → PR 延長、P 波變平/消失 → QRS 增寬 → 正弦波 (sine wave) → VF/asystole

Insulin 降鉀為什麼一定要配 D50 並追血糖？::insulin 把鉀驅入細胞但會造成低血糖（腎衰病人清除慢可遲發），故配 D50W 並於 1/2/4/6 小時追蹤血糖

高血鉀用的 β2-agonist 是哪個、劑量特點？::salbutamol 10–20 mg nebulized，劑量遠高於氣喘常規；降 K 約 0.5–1，心搏過速者慎用

哪一步驟才是「真正把鉀排出體外」？::第三步排鉀 — 利尿劑（需有尿量）、陽離子交換樹脂（Kayexalate/patiromer/SZC）、血液透析；前兩步只是暫時穩膜與藏鉀

NaHCO3 在高血鉀什麼時候才用、有何限制？::僅在合併代謝性酸中毒時輔助使用；單獨降鉀效果差，且不可與鈣走同一條 IV line（會沉澱）

Kayexalate 的主要安全疑慮是什麼？::腸道壞死（FDA 黑框警告），尤其術後/腸阻塞/與 sorbitol 併用；起效慢非急救藥

無尿或腎衰竭且藥物無效的高血鉀終極解方？::血液透析（最快最徹底移除鉀）

如何懷疑假性高血鉀、該怎麼處理？::病人無症狀、EKG 正常但數字很高，常因溶血/握拳採血/檢體延遲/白血球血小板極高；重抽一管（不綁壓脈帶、快速送驗）確認，但勿延誤真高血鉀急救

高血鉀要停掉哪些常見升鉀藥物？::ACEi/ARB、spironolactone、NSAID、trimethoprim(TMP-SMX)、heparin、非選擇性 β-blocker，以及含鉀點滴/KCl

### 自我測驗（選擇題，答案摺疊）

**Q1.** 值班接到血鉀 7.2、EKG 顯示 QRS 增寬的病人。下列第一步處置最正確？
- A. 立刻靜脈輸注 KCl 稀釋
- B. 先給 Calcium gluconate 10% 10 mL IV 穩膜保護心臟
- C. 只口服 Kayexalate 等它排鉀
- D. 等 30 分鐘複驗血鉀再決定

> [!success]- 答案
> **B** — 有 EKG 變化屬心臟急症，第一優先是給鈣穩膜（1–3 分起效保護心肌），再接續 insulin+D50、β-agonist 移鉀與後續排鉀。A 是致命錯誤（KCl 會升鉀），C/D 會延誤救命。

**Q2.** 關於 insulin + glucose 降鉀，何者正確？
- A. Insulin 把鉀排出體外
- B. 給 insulin 後不需追蹤血糖
- C. Insulin 使鉀移入細胞，屬暫時性，須配 D50 並追血糖防低血糖（腎衰者可遲發）
- D. 只能用長效 insulin

> [!success]- 答案
> **C** — Regular insulin 10 U IV 使鉀移入細胞（暫時、約 4–6 小時），本身不排鉀；須配 D50W 並於數小時內追血糖，腎衰竭病人 insulin 清除慢易遲發低血糖。

**Q3.** 一名腸阻塞術後病人血鉀 6.8、無尿（急性腎衰）。下列處置何者最恰當？
- A. 首選 Kayexalate 灌腸
- B. 大量 furosemide 利尿
- C. 給鈣穩膜 + insulin/D50 + β-agonist 暫時穩住，安排緊急血液透析
- D. 只給 NaHCO3 一項即可

> [!success]- 答案
> **C** — 無尿病人利尿劑無效（B 錯），術後腸阻塞用 Kayexalate 有腸壞死高風險（A 錯），NaHCO3 單獨降鉀弱（D 錯）；正解是暫時措施穩住後，以血液透析作為終極移鉀手段。

<!-- flashcard-gen:end -->
