---
tags: [症狀, 科別/心臟內科, 科別/腎臟內科, 科別/一般內科]
aliases: [Edema, 水腫, 浮腫]
type: symptom
status: 🌱seedling
sources_reviewed: 2026-07-03
---
# Edema（水腫）

> [!danger] 🚨 紅旗警訊（must-not-miss，先排除致命病因再想常見病）
> **助記「腫要看：單側、臉、喘、快」**
> 1. **單側下肢急性腫痛** → [[Deep Vein Thrombosis(深部靜脈栓塞)]]（可脫落 → 致命 [[Pulmonary Embolism(肺栓塞)]]）
> 2. **顏面 / 口唇 / 舌腫（angioedema）** → 呼吸道阻塞、[[Anaphylaxis(過敏性休克)]]，可致命窒息（尤其 ACEi 相關）
> 3. **雙側水腫 + 端坐呼吸 / 夜間陣發呼吸困難 / rales** → 急性失代償 [[Congestive Heart Failure(鬱血性心臟病)]] → [[Pulmonary Edema(肺水腫)]]
> 4. **眼周水腫 + 高血壓 + 血尿（茶色尿）** → 急性腎炎症候群（腎絲球腎炎）
> 5. **快速全身性水腫（anasarca）+ 泡泡尿** → [[Nephrotic syndrome(腎病症候群)]]（合併高凝、感染風險）
>
> ⚡ **單側 vs 雙側是第一個分岔**：單側先想局部（DVT / 蜂窩組織炎 / 淋巴阻塞）；雙側先想全身（心 / 肝 / 腎 / 甲狀腺 / 藥物）

## 🔀 鑑別診斷 DDx（值班從這裡連到疾病）
| 疾病 | 支持特徵 | rule-out 線索 |
| --- | --- | --- |
| [[Deep Vein Thrombosis(深部靜脈栓塞)]] | 單側、急性、腫痛熱、Homans、小腿周徑差 >3 cm、癌症/臥床/術後 | Wells 低 + D-dimer(-)；雙側對稱不像 |
| [[Congestive Heart Failure(鬱血性心臟病)]] | 雙側凹陷、頸靜脈怒張、端坐呼吸、rales、肝腫大、NT-proBNP↑ | BNP 正常 + 無頸靜脈怒張/rales |
| [[Liver Cirrhosis(肝硬化)]] / [[Liver failure(肝衰竭)]] | 腹水、黃疸、spider angioma、caput medusae、白蛋白↓ | 肝功能/凝血正常、無門脈高壓徵象 |
| [[Nephrotic syndrome(腎病症候群)]] | 泡泡尿、眼周晨腫、重度蛋白尿(>3.5 g/day)、低白蛋白、高血脂 | 尿蛋白(-)、白蛋白正常 |
| [[Hypothyroidism(甲狀腺機能低下)]]（myxedema） | **non-pitting**、怕冷、體重增加、心跳慢、TSH↑ | pitting edema、TSH 正常 |
| 淋巴水腫 lymphedema | non-pitting、術後清淋巴結/放療、[[Elephantiasis(象皮病)]]（絲蟲）、Stemmer sign(+) | 凹陷性、有全身病因 |
| 藥物性 | [[Calcium Channel Blocker(CCB)]]（precapillary sphincter 擴張）、[[NSAID]]、[[Steroid(類固醇)]]、[[Estrogen]]、pioglitazone | 停藥後改善、無器官功能異常 |
| 慢性靜脈功能不全 | 雙側、久站惡化、色素沉著、靜脈曲張 | 急性單側不像 |

> [!warning] 血管性水腫（angioedema，尤其舌/喉）與心因/腎因水腫機轉完全不同 — 前者是**呼吸道急症**，見到先評估 airway，不要當一般水腫觀察。

## ❓ 問診 / 身體檢查重點
- **單側 or 雙側？** 這決定整個思路（局部 vs 全身）
- **時間**：急性（DVT / angioedema / 蜂窩組織炎）vs 慢性（心 / 肝 / 腎 / 靜脈）
- **凹陷 or 非凹陷（pitting vs non-pitting）**：non-pitting → 甲狀腺 myxedema / 淋巴水腫
- **系統回顧**：呼吸困難、端坐呼吸、腹脹、泡泡尿、體重變化、藥物史（CCB / NSAID / 荷爾蒙）、癌症 / 臥床 / 近期手術
- **關鍵理學**：頸靜脈壓、rales、肝脾腫大、腹水（shifting dullness）、Stemmer sign、皮膚色素/傷口、雙側 vs 單側對稱性

## 🩺 初步 workup（該開的檢查 / 影像）
> [!note] 黃金第一步：**先分「單側 vs 雙側」+ 量生命徵象** — 單側急性腫痛先排 DVT（Wells + doppler），雙側先找全身器官病因。
- **基本抽血**：CBC、肝腎功能、albumin、NT-proBNP、TSH
- **尿液**：尿蛋白 / Pro-Cr ratio 或 24h 尿蛋白（找腎病 / 腎炎）、尿沉渣看紅血球圓柱
- **影像**：CXR（心臟大小 / 肺水腫）、心電圖；懷疑 DVT → **下肢靜脈 doppler 超音波** + 凝血
- **無明顯病因**：查癌症、protein C/S、antiphospholipid syndrome
- **懷疑甲狀腺**：thyroid panel + autoantibody

## ⚡ 值班即時處置（穩定 vs 不穩定分流）
```mermaid
flowchart TD
    A["水腫病人"] --> B{"生命徵象穩定?"}
    B -->|不穩定| C["ABC；喉頭 angioedema → 保護呼吸道<br/>急性肺水腫 → 坐起、O2、利尿、硝酸鹽"]
    B -->|穩定| D{"單側 or 雙側?"}
    D -->|單側急性腫痛| E["Wells DVT 分層<br/>→ doppler / D-dimer"]
    D -->|雙側/全身| F["找器官病因<br/>心(BNP/CXR) 肝(LFT/albumin)<br/>腎(尿蛋白) 甲狀腺(TSH)"]
    E -->|DVT(+)| G["抗凝（依院內指引）"]
    F --> H["針對病因治療<br/>+ 限鈉/利尿為輔"]
```
- **不穩定線**：喉頭 angioedema → 保護呼吸道（必要時插管）+ 依院內指引處置過敏；急性肺水腫 → 坐起、給氧、利尿劑、硝酸鹽
- **穩定線**：先分單/雙側 → 對應 workup；利尿是「症狀控制」，**病因治療才是根本**
- ⚠️ 低白蛋白 / 肝硬化的水腫，過度利尿易致腎前性腎衰 + 電解質失衡

## 📊 臨床評分 / 風險分層（scoring）★單側下肢水腫核心
> 單側下肢水腫最怕漏 DVT。**Wells DVT score** 決定要不要直接做超音波 / 加驗 D-dimer。

### Wells Score for DVT（每項計分）
| 項目 | 分數 |
| --- | --- |
| 活動性癌症（治療中 / 6 個月內 / 安寧） | +1 |
| 下肢癱瘓、麻痺，或近期石膏固定 | +1 |
| 近期臥床 ≥3 天，或 12 週內大手術 | +1 |
| 沿深靜脈走向的局部壓痛 | +1 |
| 整條腿腫脹 | +1 |
| 患側小腿周徑較對側大 >3 cm（脛骨粗隆下 10 cm 量） | +1 |
| 患側凹陷性水腫（局限於症狀側） | +1 |
| 非曲張的淺層側枝靜脈 | +1 |
| 曾有紀錄的 DVT | +1 |
| **有同樣可能或更可能的替代診斷** | **−2** |

| 總分 | 風險 | 處置分流 |
| --- | --- | --- |
| **≥3** | 高機率 | 直接 **下肢靜脈 doppler**；陰性也考慮重複 |
| **1–2** | 中機率 | 先驗 **高敏 D-dimer**，(+) 再 doppler |
| **≤0** | 低機率 | D-dimer(-) 可安全排除 DVT |

> 亦常用兩級版：**≥2 = DVT likely**（直接影像）、**<2 = unlikely**（先 D-dimer）。

## 🔗 相關
- 疾病：[[Deep Vein Thrombosis(深部靜脈栓塞)]]　[[Congestive Heart Failure(鬱血性心臟病)]]　[[Nephrotic syndrome(腎病症候群)]]　[[Liver Cirrhosis(肝硬化)]]　[[Hypothyroidism(甲狀腺機能低下)]]
- 症狀：[[Shortness of breath(喘氣)]]　[[Jaundice(黃疸)]]

## 📚 來源
[^1]: Wells PS et al. *Lancet* 1997；*NEJM* 2003（DVT 兩級分層 + D-dimer）
[^2]: 水腫四大機轉（靜水壓↑ / 膠體滲透壓↓ / 通透性↑ / 淋巴阻塞）— Starling forces 標準生理學
[^3]: Angioedema 呼吸道急症處置 — 值班急症共識

## 🎴 Flashcards & 自我測驗（Ollama qwen2.5:7b 自動生成 2026-07-03）
<!-- flashcard-gen:start -->

### 記憶卡（Spaced Repetition 相容 · `Q::A`）
單側急性下肢水腫需先排除何病？::深部靜脈栓塞（DVT）

哪種情況會考慮直接做下肢靜脈多普勒超音波？::Wells 分數 ≥3

急性雙側水腫需排除何病？::心力衰竭（CHF）

哪種情況會考慮先驗高敏 D-dimer？::Wells 分數 1–2

哪種水腫是非凹陷性？::甲狀腺機能低下引起的 myxedema

哪種水腫病人會考慮查癌症？::無明顯病因的雙側水腫

哪種水腫病人會考慮查蛋白 C/S 和抗磷脂綜合症？::無明顯病因的雙側水腫

哪種藥物可能引起單側急性下肢水腫？::深部靜脈栓塞（DVT）

哪種水腫病人會考慮查甲狀腺功能？::無明顯病因的雙側水腫

哪種水腫需要先排除呼吸道阻塞？::血管性水腫（angioedema，尤其舌/喉）

### 自我測驗（選擇題，答案摺疊）
**Q1.** 一患者主訴右下肢急性腫脹、疼痛，您首先應考慮哪種檢查？
- A. 下肢靜脈多普勒超音波
- B. 血液化驗（CBC, 肝腎功能）
- C. 尿蛋白/Pro-Cr ratio
- D. 心電圖

> [!success]- 答案
> **A** — 根據筆記，單側急性下肢水腫需先排除深部靜脈栓塞（DVT），因此首先應考慮做下肢靜脈多普勒超音波。

**Q2.** 一患者主訴雙側下肢凹陷性水腫，您下一步該如何進行評估？
- A. 查癌症
- B. 甲狀腺功能檢查
- C. 尿蛋白/Pro-Cr ratio
- D. 肝腎功能

> [!success]- 答案
> **A** — 根據筆記，雙側凹陷性水腫需考慮全身器官病因，因此首先應查癌症。

**Q3.** 一患者主訴單側下肢非凹陷性水腫，您應考慮哪種疾病？
- A. 深部靜脈栓塞
- B. 甲狀腺功能低下（甲狀腺機能低下）
- C. 肝硬化
- D. 心力衰竭

> [!success]- 答案
> **B** — 根據筆記，單側非凹陷性水腫提示可能是甲狀腺機能低下的 myxedema。

<!-- flashcard-gen:end -->
