# Chapter 4: Fundamentals of Molecular Biology (分子生物學基礎)

> **Part**: Part I — Fundamentals and Foundations (基礎與基石)

## Core Idea
分子生物學以 DNA 雙螺旋半保留複製與中心法則（DNA $\to$ RNA $\to$ 蛋白質）為核心架構；現代研究工具透過 PCR、重組載體選殖、免疫偵測，演進至 Cre/loxP 條件剔除、RNA 干擾與 CRISPR/Cas9 精準基因編輯，實現對生命基因功能的分子級因果驗證。

## Sections Outline
- **4.1 Heredity, Genes, and DNA (遺傳、基因與 DNA 構造)**
- **4.2 Expression of Genetic Information (遺傳訊息的表現與中心法則)**
- **4.3 Recombinant DNA (重組 DNA 與基因選殖技術)**
- **4.4 Detection of Nucleic Acids and Proteins (核酸與蛋白質之分子檢測技術)**
- **4.5 Gene Function in Eukaryotes (真核生物基因功能解析與基因編輯)**

## Frameworks Introduced
### Central Dogma & Exceptions Framework (中心法則與擴展修訂架構)
- **When to use**: 分析遺傳訊息流向與非常規轉錄機制時使用
- **How to apply**:
1. 經典中心法則 (Francis Crick)：DNA 經半保留複製維護遺傳訊息，經由轉錄生成 mRNA，mRNA 經核醣體轉譯為功能性多胜肽鏈蛋白質（訊息不可由蛋白質逆流至核酸）。
2. 現代擴展修正：
   - 反轉錄 (Reverse Transcription)：RNA 腫瘤病毒與反轉錄病毒（Temin & Baltimore 1970）利用反轉錄酶以單股 RNA 為模板合成互補雙股 DNA (cDNA)。
   - RNA 自我複製：RNA 病毒（如脊髓灰質炎病毒、冠狀病毒）利用 RNA 依賴性 RNA 聚合酶 (RdRP) 直接以 RNA 為模板複製 RNA。
   - 普里昂蛋白構型傳遞 (Prions)：PrPSc 誘發正常 PrPC 蛋白質構型改變引發海綿狀腦病，不牽涉核酸序列改變。

### Molecular Cloning & Expression Vector Design (分子選殖與表現載體工程框架)
- **When to use**: 建構真核目標蛋白質在原核或真核宿主內高效表現之工程設計
- **How to apply**:
1. 載體骨架要素：複製起點 (ori)、抗藥性篩選標記 (如 Ampicillin / Kanamycin 阻抗基因)、多重選殖位點 (MCS)。
2. 轉錄驅動要素：宿主專一性強啟動子（原核 lac / T7 啟動子；真核 CMV / EF1α 啟動子）、轉錄終止與 Poly(A) 訊號。
3. 轉譯調控要素：原核 Shine-Dalgarno 序列 (RBS)；真核 Kozak 共有序列 (GCCACC**AUG**G) 及起始密碼子。
4. 純化標籤 (Epitope Tag)：N 端或 C 端融合 His-tag (6×His 經鎳管柱固定化金屬親和層析 IMAC 純化)、FLAG-tag、GST-tag 或 GFP 螢光報導蛋白。

### Gene Knockout & Editing Decision Framework (基因破壞與精準編輯決策框架)
- **When to use**: 依據功能喪失驗證需求選擇暫態降解、永久破壞或組織專一性基因敲除
- **How to apply**:
1. 暫態轉錄後基因靜默：RNA 干擾 (RNAi) — 外源 dsRNA / siRNA 經 Dicer 剪切裝載入 RISC 複合體，透過完全互補配對降解 mRNA，或 miRNA 不完全配對抑制轉譯（高通量篩選快，但具脫靶與非完全敲除特性）。
2. 永久基因體破壞與精準編輯：CRISPR/Cas9 — 由 sgRNA 引導 Cas9 核酸內切酶在特定基因體位點產生雙股斷裂 (DSB)。
   - NHEJ (非同源末端連接)：易錯修復，產生小片段插入/缺失 (Indels)，導致轉譯讀框移碼突變 (Frameshift) 實現基因剔除 (Knockout)。
   - HDR (同源重組修復)：提供外源供體 DNA 模板，進行精準核苷酸修復或特定序列敲入 (Knock-in)。
3. 組織／發育時期專一性剔除：Cre/loxP 系統 — 組織專一啟動子驅動 Cre 重組酶表現，特異切除夾在兩個同向 loxP 位點之間的目標外顯子，避免胚胎致死性。

## Key Concepts
- **Okazaki Fragments (岡崎片段)**: DNA 複製叉上滯後股 (Lagging strand) 因 DNA 聚合酶僅能由 5' 向 3' 方向合成而產生的不連續短鏈 DNA 片段，由引子酶合成 RNA 引子引導。
- **Reverse Transcriptase (反轉錄酶)**: 以 RNA 為模板合成單股 cDNA，具備 RNA 依賴性 DNA 聚合酶、RNase H 與 DNA 依賴性 DNA 聚合酶三種催化活性。
- **Type II Restriction Enzyme (第二型限制酶)**: 辨識特定 4-8 bp 雙向對稱回文序列 (Palindromic sequence)，並在辨識位點內精準剪切磷酸二酯鍵產生黏狀末端 (Sticky ends) 或鈍端 (Blunt ends)。
- **cDNA Library (互補 DNA 基因庫)**: 以成熟 mRNA 為模板經反轉錄合成的 DNA 片段庫，僅包含表現外顯子序列且不含內含子，可直接於原核細胞中表現真核蛋白質。
- **Taq DNA Polymerase (Taq 耐熱 DNA 聚合酶)**: 分離自嗜熱水生菌 (Thermus aquaticus) 的耐熱性 DNA 聚合酶，能耐受 PCR 變性步驟之 95°C 高溫而無需每輪重新添加。
- **Real-Time qPCR (即時定量 PCR)**: 利用螢光染劑 (SYBR Green) 或螢光探針 (TaqMan)，在 PCR 擴增過程中即時監控螢光訊號累積，藉由閾值循環數 (Ct 值) 定量初始模板拷貝數。
- **Monoclonal Antibody (單株抗體)**: 由單一 B 淋巴細胞與骨髓瘤細胞融合形成之融合瘤 (Hybridoma) 分泌，針對單一特定抗原決定基 (Epitope) 具均一親和力與高度專一性的抗體。
- **Western Blotting (西方墨點法)**: 利用 SDS-PAGE 依分子量分離蛋白質變性多胜肽，轉移至固相膜 (PVDF/NC) 後利用專一性一級抗體與酵素標定二級抗體化學發光定量標靶蛋白質。
- **RNAi & RISC (RNA 干擾與 RNA 誘導靜默複合體)**: 雙股 RNA 經 Dicer 酶加工為 21-23 nt siRNA，與 Argonaute 等蛋白組裝成 RISC，專一性辨識並降解標靶 mRNA。
- **CRISPR/Cas9 (規律間隔成簇短回文重複序列/Cas9)**: 源於細菌後天免疫防禦噬菌體入侵的核酸酵素系統，由 sgRNA 引導 Cas9 於 PAM 序列 (NGG) 上游切割 DNA 雙股斷裂。

## Mental Models
- **Think of Type II Restriction Enzymes as Molecular Scissors with Specific Barcodes (將第二型限制酶視為帶有特定條碼辨識的分子剪刀)**: 只在讀到精確對稱的回文密碼時才下剪，切口留下具自黏性的懸垂單股，提供 DNA 連接酶精確拼接的黏著點。
- **Think of Real-Time PCR Ct Value as Golf Scores (將即時定量 PCR 之 Ct 值視為高爾夫球桿數)**: 桿數（Ct 值）愈少，代表初始實力（起始模板濃度）愈強；Ct 值每提早 1 個循環，代表起始模板濃度高出一倍（$2^{\Delta Ct}$）。
- **Think of CRISPR/Cas9 as a Molecular Word Processor's Find-and-Replace (將 CRISPR/Cas9 視為文書處理器的尋找與取代)**: sgRNA 是長達 20 鹼基的精準搜尋文字框，Cas9 是游標切斷鍵，外源修復模板則是取代內容。

## Anti-patterns
- **混淆原核基因表現與真核基因選殖：直接將真核基因組 DNA 放入大腸桿菌表現會失敗，因為原核生物缺乏切除內含子 (Introns) 的剪接體機制，必須使用反轉錄產生的 cDNA。**: 選殖實驗設計時誤用帶有巨長內含子的基因體 DNA。
- **忽視 CRISPR/Cas9 的 PAM (Protospacer Adjacent Motif) 限制：sgRNA 雖然能自由設計 20 nt 導向序列，但目標基因體位點的 3' 端必須緊鄰特異 PAM 序列（化膿性鏈球菌 SpCas9 需為 5'-NGG-3'），否則 Cas9 完全無法結合解旋下刀。**: 在基因編輯靶點設計中遺漏 PAM 檢驗。
- **誤認全身性基因剔除小鼠 (Conventional Knockout) 一定能觀察到成年組織表型：許多關鍵發育基因若在胚胎期完全缺失會導致早期致死 (Embryonic lethality)，無法研究成體功能；此時必須改用組織專一性或誘導型 Cre/loxP 條件式基因剔除。**: 在動物實驗設計中忽視胚胎致死性風險。

## Reference Tables
| 分子技術 | 分析標的 | 分離原理 / 關鍵機制 | 訊號讀取方式 | 典型應用場景 |
| :--- | :--- | :--- | :--- | :--- |
| **Southern Blotting** | 基因體 DNA | 限制酶切段 + 瓊脂糖電泳 | 放射性或地高辛標定 DNA 探針雜合 | 偵測基因重排、特定基因拷貝數、限制酶切片段長度多態性 (RFLP) |
| **Northern Blotting** | RNA (主要是 mRNA) | 甲醛變性瓊脂糖凝膠電泳 | 標定之互補核酸探針雜合 | 測定特定基因之 mRNA 表現量與轉錄本分子大小 (Alternative splicing) |
| **Western Blotting** | 蛋白質 | SDS-PAGE (依分子量變性分離) | 專一性抗體 + HRP 酵素化學發光 (ECL) | 定量組織或細胞中特定蛋白質表現量、轉譯後修飾 (磷酸化狀態) |
| **RT-qPCR** | mRNA 轉錄本 | 反轉錄 cDNA + 聚合酶連鎖反應 | SYBR Green 螢光或 TaqMan 探針 (Ct 值) | 高靈敏度即時定量特定基因轉錄表現倍數差異 |
| **ChIP (染色質免疫沉澱)** | DNA-蛋白質交互作用 | 甲醛交聯 + 超音波破碎 + 特異抗體拉下 | 產物進行 qPCR 或高通量定序 (ChIP-seq) | 鑑定轉錄因子或組蛋白修飾在全基因體的結合位點圖譜 |
| **Co-IP (共同免疫沉澱)** | 蛋白質-蛋白質複合體 | 溫和非變性裂解 + 特異抗體結合 Protein A/G | 沉澱物經 Western Blot 或質譜儀分析 | 驗證生理狀態下兩種或多種蛋白質是否存在於同一分子複合體內 |

## Worked Example
**分子檢測綜合分析：如何區分某突變是導致蛋白質「轉錄停止」、「蛋白質轉譯缺陷」還是「轉譯後快速降解」？**

1. **實驗步驟設計**：
   - **步驟 1 (RT-qPCR / Northern Blot)**：檢測該基因之 mRNA 水平。
     - 若突變株 mRNA 幾乎為零 $\implies$ 屬於**轉錄停止**（啟動子突變或轉錄延伸受阻）。
     - 若突變株 mRNA 水平與野生型相同 $\implies$ 進入步驟 2。
   - **步驟 2 (Western Blot)**：檢測該蛋白質穩態總量。
     - 若蛋白質為零，但 mRNA 正常 $\implies$ 存在轉譯障礙或轉譯後極端不穩定。進入步驟 3。
   - **步驟 3 (MG132 蛋白酶體抑制劑處理 / 放射性脈衝追蹤 Pulse-Chase)**：
     - 加入蛋白酶體抑制劑 MG132 後，若突變蛋白質大量積聚恢復野生型水平 $\implies$ 證明蛋白質轉譯正常，但因摺疊錯誤被泛素-蛋白酶體系統**轉譯後快速降解**。
     - 若加入 MG132 後蛋白質依然完全偵測不到，且脈衝追蹤實驗在早期時間點未測得標定新生鏈 $\implies$ 確定為**蛋白質轉譯缺陷**（如起始密碼子突變、核醣體停滯或讀框提早終止）。

## Key Takeaways
1. 中心法則建立了遺傳訊息從 DNA 到 RNA 再到蛋白質的不可逆流向基石，反轉錄現象則拓展了 RNA 反向流動至 DNA 的認知邊界。
2. 第二型限制酶與 DNA 連接酶構成重組 DNA 工程的剪刀與膠水，表現載體整合啟動子、RBS/Kozak 與標籤序列實現異源蛋白質合成。
3. PCR 藉由耐熱 DNA 聚合酶實現百萬倍體外指數級核酸擴增，RT-qPCR 則利用螢光動力學提供精確的轉錄本定量金標準。
4. Southern、Northern 與 Western 墨點法分別針對 DNA、RNA 與蛋白質，藉由大小分離與專一性探針／抗體達成高專一性檢測。
5. CRISPR/Cas9 技術由 sgRNA 導向 Cas9 誘發 DSB，藉由易錯的 NHEJ 途徑達成基因破壞，或藉 HDR 途徑實現單鹼基精準基因修正。

## Connects To
- **Ch 1 Introduction to Cells and Cell Research**: 結合模式生物的遺傳特質，評估分子選殖與轉殖基因小鼠的實施可行性。
- **Ch 5 Genomics, Proteomics, and Systems Biology**: 由單一基因選殖檢測邁向全基因體定序、RNA-seq 轉錄體與質譜蛋白質體學。
- **Ch 8 RNA Synthesis and Processing**: 深入探討轉錄反應本質與真核成熟 mRNA 5' 端加帽、剪接及 3' Poly(A) 尾加工機制。
