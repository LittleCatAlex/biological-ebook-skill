# Chapter 20: Cancer (癌症分子生物學)

> **Part**: Part IV — Cell Regulation (細胞調控機制)

## Core Idea
癌症是基因體驅動突變與達爾文克隆演化造就的惡性增殖疾病：原癌基因經顯性點突變、放大或易位化身為致癌基因（如 Ras、Myc、Bcr-Abl），抑癌基因經隱性雙重打擊失活（如 Rb、p53、PTEN）；現代精準腫瘤學利用致癌基因成癮發展小分子激酶抑制劑（Imatinib），並藉由阻斷 PD-1/CTLA-4 免疫檢查點重新解放自體 T 細胞殺傷腫瘤。

## Sections Outline
- **20.1 The Development and Causes of Cancer (癌症特性、多階段腫瘤演化、瓦伯格效應與致癌因子)**
- **20.2 Oncogenes (反轉錄病毒致癌基因、原癌基因顯性活化機制（點突變、擴增、易位）)**
- **20.3 Tumor Suppressor Genes (抑癌基因雙重打擊假說、Rb 守門員、p53 守護者與 PTEN 剎車)**
- **20.4 Molecular Approaches to Cancer Treatment (分子標靶治療（Imatinib、Herceptin）與免疫檢查點抑制劑（PD-1/CTLA-4）)**

## Frameworks Introduced
### Hallmarks of Cancer Functional Framework (癌症核心惡性特徵功能架構)
- **When to use**: Hanahan & Weinberg 癌症標誌體系，評估腫瘤細胞擺脫生理生長束縛的分子能力
- **How to apply**:
1. 自給自足增殖信號 (Sustaining proliferative signaling)：自泌生長因子或 RTK-Ras-MAPK 途徑持續性組成型突變活化。
2. 逃避生長抑制 (Evading growth suppressors)：失活 Rb 守門員蛋白與 TGF-β 抑制途徑，跨越限制點不受控增殖。
3. 抵抗細胞凋亡 (Resisting cell death)：過量表現抗凋亡蛋白 Bcl-2，失活 p53 阻止 DNA 損傷誘發之 MOMP 與 Caspase 活化。
4. 無限複製潛能 (Enabling replicative immortality)：90% 腫瘤重啟端粒酶 (TERT) 表現，維持端粒長度突破海佛烈克極限。
5. 誘導血管新生 (Inducing angiogenesis)：缺氧誘導因子 HIF-1α 穩定累積，高分泌 VEGF 誘導新生毛細血管網供應養分。
6. 活化侵襲與轉移 (Activating invasion and metastasis)：下調 E-cadherin 啟動 EMT 轉化，分泌 MMPs 切割降解基底膜膠原。
7. 重編程能量代謝 (Reprogramming energy metabolism / Warburg Effect)：在氧氣充足條件下依然高達 85% 依賴無氧糖解生成乳酸，大量分流碳骨架合成核酸與脂質。
8. 逃避免疫摧毀 (Evading immune destruction)：高表現 PD-L1 結合細胞毒性 T 細胞表面 PD-1，關閉免疫抗腫瘤殺傷。

### Proto-Oncogene Dominant Activation Mechanics (原癌基因顯性活化三大多樣性分子機制)
- **When to use**: 分析單一對偶基因功能獲得性 (Gain-of-Function) 突變如何引發致癌性失控表現
- **How to apply**:
1. 點突變 (Point Mutation，改變蛋白質結構與催化活性)：
   - *Ras* 基因家族 (*KRAS, NRAS, HRAS*)：在第 12、13 或 61 位密碼子發生單鹼基錯義突變（如 Gly12Val）。
   - 阻礙了內在 GTPase 活性與 GAP 蛋白水解催化，Ras 永久卡死於 Ras-GTP 活化態，持續驅動 MAPK 級聯。
2. 基因放大 (Gene Amplification，增加基因拷貝數與表現量)：
   - *ERBB2 / HER2 (Neu)* 酪胺酸受體基因在 20-30% 侵襲性乳癌中擴增數十至數百拷貝，受體密度過高引發配體非依賴性自發二聚化自身磷酸化。
   - *MYCN* 基因在兒童神經母細胞瘤中擴增為微雙體 (Double minutes) 或均質染色區 (HSR)，預示極度不良預後。
3. 染色體易位 (Chromosomal Translocation，重組強啟動子或生成嵌合癌蛋白)：
   - **調控區易位 (如 Burkitt 淋巴瘤)**：染色體 $t(8;14)(q24;q32)$ 易位，將 8 號染色體上的 *c-MYC* 原癌基因置於 14 號染色體免疫球蛋白重鏈 (*IGH*) 強增強子控制下，導致 Myc 轉錄因子在 B 細胞中異常持續暴增表現。
   - **嵌合融合蛋白生成 (如慢性骨髓性白血病 CML 費城染色體)**：$t(9;22)(q34;q11)$ 相互易位，將 9 號染色體 *c-ABL* 酪胺酸激酶基因與 22 號染色體 *BCR* 基因頭尾融合，生成 **Bcr-Abl 嵌合融合蛋白**。Bcr 區段促使 Abl 激酶結構域組成型自發寡聚化，喪失自抑制，在細胞質持續高活性磷酸化下游 STAT5 與 Akt，惡性驅動粒細胞無限克隆擴增。

### Two-Hit Hypothesis & Tumor Suppressor Circuitry (雙重打擊假說與抑癌基因失活網絡)
- **When to use**: Knudson 統計遺傳學假說，解析隱性功能喪失 (Loss-of-Function) 在家族性與散發性腫瘤中的生化本質
- **How to apply**:
1. 雙重打擊假說 (Two-Hit Hypothesis)：抑癌基因在雜合狀態下（帶有一個突變對偶基因）通常維持正常表型；必須經歷兩次獨立突變打擊，使**兩個對偶基因均發生失活突變或雜合性缺失 (LOH, Loss of Heterozygosity)**，抑癌剎車完全失靈方誘發腫瘤。
   - 家族遺傳性視網膜母細胞瘤：患兒生殖系已遺傳「第一擊（一個突變 *Rb*）」；視網膜發育中數百萬細胞只要任何一顆體細胞發生隨機「第二擊」，即迅速發展為雙側多發性腫瘤。
   - 散發性視網膜母細胞瘤：正常體細胞必須在同一顆細胞中相繼獨立發生極其罕見的兩次隨機突變打擊，通常發病極晚且為單側單發。
2. 守門員 (Gatekeeper) 與守護者 (Caretaker) 分類：
   - **守門員 (Gatekeepers)**：直接控制細胞週期進程與分化凋亡剎車（如 *RB1, TP53, APC, PTEN, CDKN2A/p16*）。
   - **守護者 (Caretakers)**：負責 DNA 修復與維護基因組保真度，失活後導致基因體突變率飆升數百倍（如 MMR 基因 *MSH2/MLH1*, *BRCA1/2*, *ATM, XP* 基因群）。

## Key Concepts
- **Warburg Effect (瓦伯格效應 / 有氧糖解)**: 奧托·瓦伯格 (Otto Warburg) 發現，即使在氧氣極其充裕條件下，癌細胞依然優先將高達 85% 的葡萄糖轉化為乳酸，以提供大量生化合成前驅物並酸化微環境。
- **Proto-Oncogene vs Oncogene (原癌基因與致癌基因)**: 原癌基因是細胞內正常參與生長分化信號的生理基因；當發生功能獲得性顯性突變、放大或易位後，轉變為驅動惡性轉化的致癌基因。
- **Philadelphia Chromosome (費城染色體)**: 人類白血病中首個被鑑定的特異性染色體異常：染色體 $t(9;22)$ 易位生成的微小 22 號染色體，編碼高致癌性 Bcr-Abl 嵌合酪胺酸激酶。
- **Loss of Heterozygosity (LOH, 雜合性缺失)**: 體細胞中原本帶有一野生型對偶基因與一突變對偶基因的雜合狀態，因染色體不分離、有絲分裂重組或基因缺失，導致野生型對偶基因丟失的現象。
- **p53 ('Guardian of the Genome')**: 四聚體轉錄因子，感應 DNA 損傷、缺氧與致癌壓力，啟動 p21 停滯週期或激活 Bax/Puma 凋亡；>50% 人類腫瘤存在 *TP53* 突變失活。
- **Imatinib / Gleevec (伊馬替尼 / 基利克)**: 小分子標靶藥物先驅，高專一性競爭結合 Bcr-Abl 酪胺酸激酶的非活化態 ATP 結合口袋，將致死性 CML 的 5 年存活率由 30% 提高至 >90%。
- **Trastuzumab / Herceptin (曲妥珠單抗 / 賀疾妥)**: 針對 HER2 受體胞外結構域的人源化單株抗體，阻斷 HER2 二聚化並誘導受體內吞降解，治療 HER2 陽性乳癌。
- **Immune Checkpoint Blockade (免疫檢查點阻斷療法)**: Allison & Honjo 2018 諾貝爾獎療法：使用抗體阻斷 T 細胞抑制性受體 **PD-1** 或 **CTLA-4**，解除腫瘤微環境對細胞毒性 T 淋巴細胞的免疫剎車，喚醒自體抗腫瘤免疫。
- **CAR-T Therapy (嵌合抗原受體 T 細胞療法)**: 體外基因工程將單株抗體 scFv 結合域與 T 細胞 CD3ζ 及共刺激結構域 (CD28/4-1BB) 融合，改造成標靶 CD19 的人工抗原受體 T 細胞，用於根除血液腫瘤。
- **Oncogene Addiction (致癌基因成癮)**: 某些惡性腫瘤細胞雖然累積海量突變，但其存活與增殖極度依賴某單一致癌路徑的持續信號；一旦該關鍵靶點被特異藥物阻斷，整座腫瘤大廈隨之崩塌凋亡。

## Mental Models
- **Think of Proto-Oncogenes and Tumor Suppressors as a Car's Accelerator and Brakes (將原癌基因與抑癌基因視為汽車油門與剎車)**: 原癌基因是正常油門；致癌突變如同油門踏板被強力膠死死踩到底卡死（顯性功能獲得，一個油門卡死車就暴衝）；抑癌基因是雙迴路剎車（左腳剎車與手剎車），必須兩個剎車均被剪斷（隱性雙重打擊），汽車才徹底失控墜入懸崖。
- **Think of Imatinib as Chewing Gum Stuffed into a Specific Keyhole (將伊馬替尼視為塞入特定鑰匙孔的口香糖)**: Bcr-Abl 像一把狂暴旋轉的發電機鑰匙；伊馬替尼分子如同一小塊精確塑型的口香糖，嚴絲合縫塞進其 ATP 結合插孔，發電機瞬間斷電熄火。
- **Think of PD-1/PD-L1 as a Secret Handshake Disarming a Guard (將 PD-1/PD-L1 視為繳械警衛的假通行暗號)**: 腫瘤細胞在表面掛上 PD-L1 偽裝吊牌，T 細胞警衛的 PD-1 掃描到暗號誤以為是自家人，自動放下武器（免疫耐受）；抗 PD-1 抗體如同遮住警衛眼睛的墨鏡，拆穿偽裝，T 細胞立即開火殲滅癌細胞。

## Anti-patterns
- **混淆致癌基因 (Oncogene) 與抑癌基因 (Tumor Suppressor Gene) 的突變遺傳模式：致癌基因突變是 **顯性 (Dominant) 功能獲得 (Gain-of-Function)**，細胞內只要兩個對偶基因中有一方突變即可致癌；抑癌基因突變是 **隱性 (Recessive) 功能喪失 (Loss-of-Function)**，必須兩個對偶基因均失活（雙重打擊）才會失去抑癌效應。**: 在遺傳突變分類題目中顛倒顯隱性關係。
- **誤以為免疫檢查點抑制劑（如抗 PD-1 抗體）是直接毒殺腫瘤細胞：抗 PD-1/PD-L1 抗體本身完全沒有細胞毒性，也不直接結合殺傷腫瘤細胞；其作用機制是**阻斷腫瘤細胞向 T 細胞傳遞的負向免疫抑制信號，解除免疫耐受剎車，是由患者自身被喚醒的 CD8+ 細胞毒性 T 淋巴細胞行使殺傷**。**: 在腫瘤免疫治療機制題中誤答抗體直接介導腫瘤溶解。
- **忽視瓦伯格效應 (Warburg Effect) 中有氧糖解的真正進化優勢：無氧糖解每分子葡萄糖僅產生 2 ATP，看似極度浪費；但對於急速增殖的癌細胞，其瓶頸並非能量缺乏，而是**快速複製所需的碳骨架原料（核苷酸、胺基酸、脂質）**；劇烈維持高糖解通量能將大量磷酸己糖分流至戊糖磷酸途徑與生合成途徑，滿足分裂物質需求。**: 誤以為癌細胞糖解是因為粒線體氧化功能徹底損壞。

## Reference Tables
| 基因名稱 | 基因分類 (致癌/抑癌) | 正常生理功能 | 腫瘤中之突變形式與機制 | 關聯惡性腫瘤與標靶治療藥物 |
| :--- | :--- | :--- | :--- | :--- |
| ***RAS* (K/N/H)** | **致癌基因 (Oncogene)** | 偶聯 RTK 與 MAPK/PI3K 的分子開關 | 密碼子 12/13/61 點突變，喪失 GTPase 活性 | 胰腺癌 (>90%), 結腸直腸癌; Sotorasib (KRAS G12C) |
| ***MYC* (c-Myc)** | **致癌基因 (Oncogene)** | 促增殖與轉錄活化之鹼性螺旋-環-螺旋轉錄因子 | 染色體易位 $t(8;14)$ 增強子偶聯，或基因放大 | 伯基特淋巴瘤 (Burkitt), 肺癌, 乳癌 |
| ***BCR-ABL*** | **嵌合致癌基因** | Abl 為非受體酪胺酸激酶 | 染色體 $t(9;22)$ 易位生成費城染色體融合蛋白 | 慢性骨髓性白血病 (CML); **伊馬替尼 (Imatinib/Gleevec)** |
| ***ERBB2* (HER2)** | **致癌基因 (Oncogene)** | 表皮生長因子受體家族 RTK | 基因局灶性高度拷貝數放大 (Amplification) | 侵襲性乳癌, 胃癌; **曲妥珠單抗 (Trastuzumab/Herceptin)** |
| ***RB1* (Rb)** | **抑癌基因 (TSG)** | 結合 E2F 抑制轉錄，維護 G1 限制點 | 雙對偶基因缺失或失活點突變 (雙重打擊) | 視網膜母細胞瘤, 骨肉瘤, 小細胞肺癌 |
| ***TP53* (p53)** | **抑癌基因 (TSG)** | 感應 DNA 損傷與應激，誘導 p21 阻滯或促凋亡 | DNA 結合結構域錯義突變 (常伴顯性負效應) | >50% 人類所有實體腫瘤; Li-Fraumeni 症候群 |
| ***PTEN*** | **抑癌基因 (TSG)** | 脂質磷酸酶，水解 $PIP_3$ 阻斷 PI3K-Akt 軸 | 雙對偶基因缺失突變、啟動子高甲基化 | 前列腺癌, 子宮內膜癌, 膠質母細胞瘤 |
| ***APC*** | **抑癌基因 (TSG)** | 骨架蛋白，組裝破壞複合體促進 $eta$-catenin 降解 | 截短無義突變導致破壞複合體瓦解 | 家族性腺瘤性息肉病 (FAP), 散發性結腸直腸癌 |

## Worked Example
**癌症精準免疫腫瘤學推導：微衛星不穩定性 (MSI-H) 與 PD-1 阻斷療法超常敏感性機制**

1. **遺傳缺陷與新抗原累積**：
   - 錯配修復缺陷 (dMMR，如 MLH1, MSH2 突變) 導致細胞喪失複製錯配修復能力，引發微衛星序列高頻突變 (MSI-H)。
   - **高腫瘤突變負荷 (TMB-High)**：dMMR 腫瘤每百萬鹼基累積數百個體細胞體外編碼移碼突變 (Frameshifts)，產生大量非自體的多胜肽讀框改變片段。
   - 這些異常外源胜肽經由蛋白酶體處理，由 MHC-I 類分子呈遞於腫瘤質膜表面，形成海量具有極強免疫原性的 **腫瘤新抗原 (Neoantigens)**。
2. **免疫浸潤與適應性免疫抵抗**：
   - 海量新抗原強烈吸引患者自體 **CD8+ 細胞毒性 T 淋巴細胞 (TILs)** 大規模浸潤腫瘤病灶。
   - 浸潤的 T 細胞分泌干擾素-γ (IFN-γ) 試圖殺傷腫瘤；然而腫瘤細胞受到 IFN-γ 刺激後，啟動負反饋適應性保護，表面暴露出高密度的 **PD-L1** 蛋白。
   - PD-L1 與浸潤 T 細胞表面的 **PD-1** 受體結合，向 T 細胞注入強烈去磷酸化抑制信號，使 T 細胞進入「功能耗竭態 (Exhaustion)」，腫瘤得以逃脫清除。
3. **抗 PD-1 免疫檢查點抑制劑 (Pembrolizumab) 介入效果**：
   - 抗 PD-1 單株抗體高親和力結合 T 細胞表面 PD-1，**徹底阻斷了 PD-1 與 PD-L1 的抑制性接觸**。
   - 耗竭 T 細胞如釋重負，迅速逆轉耗竭狀態，恢復穿孔素 (Perforin) 與顆粒酶 (Granzyme) 的分泌能力。
   - 由於腫瘤表面充滿了高密度的外源新抗原，被喚醒的 CD8+ T 細胞展開毀滅性精準打擊，在臨床上創造了高達 40-60% 的客觀腫瘤持久緩解率，促使 FDA 批准了史上第一個不限腫瘤組織來源（組織不可知 Tissue-agnostic）的抗癌標靶標誌物！

## Key Takeaways
1. 癌症具備持續增殖、逃避凋亡、端粒酶無限複製、血管新生、轉移浸潤與瓦伯格有氧糖解等核心特徵。
2. 原癌基因透過顯性點突變（Ras）、拷貝數放大（HER2）或染色體易位（Myc, Bcr-Abl）獲得持續致癌活性。
3. 抑癌基因遵循 Knudson 雙重打擊假說，Rb 守門員控制 G1 限制點，p53 守護者感應損傷介導停滯與凋亡。
4. 分子標靶治療（如標靶 Bcr-Abl 的伊馬替尼）針對致癌基因成癮弱點，將惡性白血病轉化為可控慢性病。
5. 免疫檢查點阻斷（抗 PD-1/CTLA-4）解除腫瘤微環境對 T 細胞的抑制剎車，在高突變負荷 (MSI-H) 腫瘤中展現強大根除療效。

## Connects To
- **Ch 7 Replication, Maintenance, and Rearrangements**: 回顧錯配修復 (MMR) 與同源重組 (HR) 缺陷如何驅動腫瘤基因組不穩定性。
- **Ch 17 Cell Signaling**: 銜接 RTK-Ras-MAPK、PI3K-Akt 與 Wnt-β-catenin 等致癌信號級聯通路。
- **Ch 18 The Cell Cycle**: 對接 Rb 磷酸化開關、CDK4/6 抑制劑及 p53-p21 週期檢查點阻滯機制。
