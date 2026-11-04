# Chapter 5: Genomics, Proteomics, and Systems Biology (基因體學、蛋白質體學與系統生物學)

> **Part**: Part I — Fundamentals and Foundations (基礎與基石)

## Core Idea
生物學研究已從單一分子解析躍升至系統整合維度：利用次世代定序、RNA-seq 與高解析質譜儀全面解析全基因體、轉錄體與蛋白質體（Interactome），並透過計算生物網絡動態與合成生物學迴路設計，揭示生命系統的湧現特性（Emergent properties）。

## Sections Outline
- **5.1 Genomes and Transcriptomes (基因體與轉錄體學)**
- **5.2 Proteomics (蛋白質體學與交互作用網絡)**
- **5.3 Systems Biology (系統生物學與合成生物學)**

## Frameworks Introduced
### High-Throughput Sequencing & Transcriptomics Architecture (高通量定序與轉錄體分析架構)
- **When to use**: 全基因體變異、轉錄本定量與可變剪接全景掃描時使用
- **How to apply**:
1. 次世代定序 (NGS - Illumina 平台)：DNA 斷裂化 $\to$ 兩端接上銜接子 (Adapters) $\to$ 流通槽表面橋式 PCR 擴增形成分子簇 (Clustering) $\to$ 螢光標定可逆終止雙去氧核苷酸進行邊合成邊定序 (Sequencing by Synthesis, SBS)。
2. 第三代長片段定序 (PacBio SMRT / Oxford Nanopore)：單分子即時定序，無需 PCR 擴增，可讀取數十 kb 長度，精確解析高度重複序列區與結構變異 (Structural variants)。
3. RNA-seq 工作流程：總 RNA 抽取 $\to$ 寡聚 dT 磁珠純化 Poly(A)+ mRNA $\to$ 逆轉錄合成雙股 cDNA $\to$ 建庫並定序 $\to$ 比對至參考基因體 $\to$ 利用 RPKM/FPKM/TPM 標準化轉錄本豐度，精準定量基因表現倍率與偵測全新剪接異構物。

### Mass Spectrometry Proteomics Identification Pipeline (質譜蛋白質體鑑定工作流)
- **When to use**: 全蛋白組定性定量、轉譯後修飾 (PTM) 測繪與蛋白質複合體成分鑑定時使用
- **How to apply**:
1. 樣品製備：蛋白質混合物提取 $\to$ 雙硫鍵還原與烷基化 $\to$ 胰蛋白酶 (Trypsin) 專一性酵素水解（於 Lys/Arg C 端切割）生成胜肽段。
2. 液相層析串聯質譜 (LC-MS/MS)：
   - 一級質譜 (MS1)：胜肽段經電灑游離 (ESI) 帶電，測量前驅離子之質荷比 (m/z) 與豐度峰。
   - 碰撞誘發解離 (CID/HCD)：高能碰撞將選定前驅胜肽於胜肽骨架斷裂，生成 b-離子與 y-離子碎片。
   - 二級質譜 (MS2)：記錄碎片離子譜峰，透過資料庫搜尋引擎比對胜肽序列標籤，拼接確定蛋白質身分。
3. 定量蛋白質體學：無標記定量 (Label-free, LFQ) 或穩定同位素化學標記 (TMT / iTRAQ / SILAC)。

### Network Topology & Systems Circuit Framework (網絡拓撲與系統生物迴路框架)
- **When to use**: 分析分子交互作用網絡強健性、訊號前饋延遲與合成基因調控迴路時使用
- **How to apply**:
1. 無尺度網絡拓撲 (Scale-Free Network)：網絡節點連接度分佈服從冪律定律（Power law），少數高度連接的樞紐蛋白（Hub proteins，如 p53, Ras）與大量低連接度周邊節點相連。特性：對隨機突變具強健容錯性 (Robustness)，但對針對 Hub 的精準打擊極度脆弱。
2. 前饋迴路動態 (Feedforward Loops, FFL)：
   - 相干型前饋迴路 (Coherent FFL)：轉錄因子 X 活化 Y，且 X 與 Y 共同活化 Z（具 AND 門邏輯時），可過濾短暫瞬時雜訊，僅對持續性刺激產生延遲活化。
   - 不相干型前饋迴路 (Incoherent FFL)：X 活化 Z，但 X 同時活化 Z 的阻遏蛋白 Y，可產生適應性脈衝反應 (Pulse generation) 或加速反應關閉。
3. 合成生物學模組：基因開關 (Genetic Toggle Switch)、抑制振盪器 (Repressilator) 以及工程化酵母菌生產青蒿素 (Artemisinin) 代謝途徑重整。

## Key Concepts
- **C-Value Paradox (C 值悖論)**: 真核生物單倍體基因組 DNA 總量（C 值）與生物體的形態或演化複雜度並無直接正相關性，主要原因為非編碼 DNA 與重複序列含量差異極大。
- **Human Genome Project (人類基因體計畫)**: 國際跨國科研計畫，於 2001 年發表草圖、2003 年完成人類 3.2 Gb 基因組定序，揭示人類僅有約 20,000-21,000 個蛋白質編碼基因，僅佔基因組不到 1.5%。
- **Alternative Splicing (選擇性剪接 / 可變剪接)**: 同一前驅 pre-mRNA 透過外顯子跳躍、內含子保留或替代性剪接位點組合，轉譯出多種結構與功能相異的蛋白質異構物，大幅擴充蛋白質體多樣性。
- **GWAS (全基因體關聯分析)**: Genome-Wide Association Study；在群體水準比對數十萬至數百萬個單核苷酸多態性 (SNP) 與特定表型或疾病風險的統計學關聯。
- **Interactome (蛋白質交互作用網絡)**: 特定細胞或生物體內所有蛋白質分子間相互作用實體與物理連結的整體網絡拓撲圖。
- **Yeast Two-Hybrid (酵母菌雙雜合系統, Y2H)**: 將誘餌蛋白與 GAL4 DNA 結合結構域 (BD) 融合，獵物蛋白與轉錄活化結構域 (AD) 融合，若兩者直接相互作用則組裝完整轉錄因子驅動報導基因表現。
- **Hub Protein (樞紐蛋白)**: 在無尺度蛋白質交互作用網絡中，與數十或數百個蛋白質節點發生廣泛連接的關鍵節點蛋白，通常具備多結構域且對細胞存活至關重要。
- **ChIP-seq (染色質免疫沉澱定序)**: 結合特異性抗體富集轉錄因子或修飾組蛋白結合之 DNA 片段，經次世代定序在全基因體尺度精確定位染色質結合位點。
- **Synthetic Biology (合成生物學)**: 運用工程學原理（標準化元件、模組化、邏輯閘）重新設計並從頭人工合成具備特定生理功能的非天然生物迴路或人造生命系統。
- **Metabolic Engineering (代謝工程)**: 藉由定向改造細胞內特定生化反應途徑、過量表現瓶頸酵素或敲除競爭支路，引導前驅物通量最大化合成目標高價值化學分子（如青蒿酸）。

## Mental Models
- **Think of the Genome as the Encyclopedia and Transcriptome as the Daily Reading List (將基因體視為整套大英百科全書，轉錄體為每日閱讀清單)**: 每顆細胞皆擁有相同的完整百科全書（基因體），但神經元與肝細胞根據當下功能需求，僅翻開摘錄完全不同的章節頁碼（轉錄體與蛋白質體）。
- **Think of Hub Proteins in a Network as Major International Airport Hubs (將網絡樞紐蛋白視為國際樞紐機場)**: 東京或紐約機場（Hub）癱瘓將導致全球航網大亂（致死突變），而偏鄉小型跑道關閉對整體航運幾無衝擊（隨機多態性強健性）。
- **Think of MS/MS as Breaking a Lego Structure to Deduce Its Assembly (將串聯質譜視為敲碎樂高積木以推算組裝圖)**: MS1 秤量完整樂高車重，高能碰撞將其沿著積木接縫震碎為雙積木、三積木片段，MS2 秤量碎片質量差即可一步步逆推原序列。

## Anti-patterns
- **將基因數量等同於生物複雜性：線蟲約有 20,000 個基因，人類亦約有 21,000 個基因，兩者基因數量相近；人類的複雜度源於多層次的選擇性剪接（可產生 >100,000 種蛋白質）及精密的表觀遺傳與非編碼 RNA 調控網絡。**: 誤以為基因數目多等於生物高等。
- **忽視酵母菌雙雜合系統 (Y2H) 的偽陽性與偽陰性盲點：Y2H 發生在酵母菌細胞核內，真核膜蛋白往往無法正常摺疊，缺乏哺乳動物特異之轉譯後修飾（如酪胺酸磷酸化）會造成偽陰性；若誘餌蛋白自身具備非特異轉錄活化能力則會產生偽陽性。**: 在蛋白質互作實驗評估中過度信任單一技術。
- **混淆 RNA-seq 的 FPKM 與 TPM 標準化算法：FPKM 在不同樣品間比較時，總 FPKM 和可能不同；而 TPM (Transcripts Per Million) 保證了每個樣本中所有轉錄本的 TPM 總和恆為 $10^6$，跨樣品橫向比較相對豐度更具統計嚴謹性。**: 在轉錄體數據橫向比對中誤用標準化單位。

## Reference Tables
| 體學技術層次 | 主要分析目標 | 關鍵檢測平台 | 數據產出與特徵指標 | 經典分析工具 / 演算法 |
| :--- | :--- | :--- | :--- | :--- |
| **基因體學 (Genomics)** | 全 DNA 序列、結構變異、CNV、SNP | Illumina NovaSeq, PacBio, Nanopore | 鹼基序列、覆蓋深度 (Coverage)、變異頻率 | BWA (序列比對), GATK (變異偵測) |
| **轉錄體學 (Transcriptomics)** | 總 RNA 轉錄本豐度、可變剪接、ncRNA | RNA-seq, 單細胞 RNA-seq (scRNA-seq) | 讀段計數 (Read Counts), TPM, 差異表現倍數 | STAR, DESeq2, Seurat (單細胞降維聚類) |
| **蛋白質體學 (Proteomics)** | 蛋白質組定性、相對/絕對定量、PTM 修飾 | 液相層析串聯質譜 (LC-MS/MS), Orbitrap | 胜肽譜圖比對 (PSM), 質荷比 (m/z), 峰面積 | MaxQuant, Proteome Discoverer |
| **交互作用體學 (Interactomics)** | 蛋白質-蛋白質、蛋白質-核酸實體關聯 | Y2H, Co-IP-MS, BioID (鄰近標定), ChIP-seq | 相互作用分數 (Confidence Score), 網絡邊 (Edges) | Cytoscape (網絡視覺化), STRING 資料庫 |
| **系統生物學 (Systems Biology)** | 動態調節迴路、信號網絡拓撲、通量平衡 | 計算建模 (ODE 常微分方程), 代謝通量分析 | 節點中心度 (Degree), 前饋/回饋動態曲線 | COPASI, MATLAB SimBiology, COBRA Toolbox |

## Worked Example
**系統生物學動態網絡分析：相干型前饋迴路 (Coherent FFL) 雜訊過濾機能推導**

考慮一個三節點前饋迴路，其中轉錄因子 X 直接活化基因 Z，X 同時活化轉錄因子 Y，而 Y 亦活化基因 Z。設啟動子 Z 為「AND 邏輯門」（必須同時有活化態的 X 與活化態的 Y 結合方能啟動轉錄）。

1. **動態推導**：
   - 當輸入訊號刺激使 X 瞬時活化，X 立即結合 Z 啟動子。
   - 但此時 Y 的蛋白質濃度尚未累積，需經歷 Y 基因轉錄、轉譯與活化過程，存在時間延遲 $\tau$。
   - 若輸入刺激僅為持續時間 $t < \tau$ 的瞬時脈衝雜訊，在 Y 濃度達到閾值前 X 訊號已消退，則 Z 啟動子始終無法滿足 AND 門條件，**Z 表現量維持為零**。
   - 僅當輸入刺激為持續時間 $t \gg \tau$ 的穩定信號時，Y 濃度跨越閾值，Z 方能被有效轉錄表現。
2. **生物學意義結論**：此種相干型前饋迴路在發育與免疫應答中扮演「訊號持續時間感應器 (Persistence Detector)」，精確過濾胞外微環境中隨機生化擾動產生的虛假短暫訊號，確保重大命運決定指令的絕對可靠性。

## Key Takeaways
1. 人類基因體定序揭示蛋白質編碼基因僅約 21,000 個，選擇性剪接與多層次轉譯後修飾是造就高度複雜蛋白質體的多樣性泉源。
2. 次世代定序 (NGS) 與單細胞 RNA-seq (scRNA-seq) 以前所未有的解析度在單細胞層級揭示轉錄異質性與細胞狀態躍遷。
3. 串聯質譜 (LC-MS/MS) 透過高能碰撞胜肽骨架產生之碎裂譜峰，成為全蛋白組身分鑑定與化學修飾測繪的定量金標準。
4. 蛋白質交互作用網絡呈現無尺度拓撲特性，高度連接的樞紐蛋白 (Hubs) 維繫著細胞系統的結構完整度與信號整合樞紐。
5. 系統生物學融合實驗體學數據與計算建模，合成生物學則運用標準化基因元件人工重構生物邏輯電路與高價值代謝工廠。

## Connects To
- **Ch 4 Fundamentals of Molecular Biology**: 從單一基因的選殖檢測躍升為全基因組尺度的大數據分析技術。
- **Ch 9 Transcriptional Regulation and Epigenetics**: 銜接 ChIP-seq 描繪全基因體組蛋白修飾圖譜與轉錄因子網絡動態。
- **Ch 17 Cell Signaling**: 將無尺度網絡與前饋迴路原理應用於多重激酶級聯訊號轉導途徑的串擾與反饋調控。
