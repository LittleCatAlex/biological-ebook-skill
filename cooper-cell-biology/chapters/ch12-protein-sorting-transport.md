# Chapter 12: Protein Sorting and Transport (蛋白質分選與囊泡運輸)

> **Part**: Part III — Cell Structure and Function (細胞結構與功能)

## Core Idea
分泌蛋白與膜蛋白透過信號胜肽經 SRP 導引至內質網執行共轉譯轉位，在腔內經分子伴侶與 Calnexin 循環嚴密監控折疊；成熟蛋白質包被於 COPII 囊泡運抵高基氏體歷經醣鏈修飾與分選，經由被囊蛋白、Rab GTPase 與 SNARE 複合體四螺旋束介導精準膜融合，最終定向分流至溶體、質膜或分泌至胞外。

## Sections Outline
- **12.1 The Endoplasmic Reticulum (內質網構造、共轉譯轉位、摺疊品質管制與脂質合成)**
- **12.2 The Golgi Apparatus (高基氏體極性組織、醣基化修飾與蛋白質分選)**
- **12.3 The Mechanism of Vesicular Transport (囊泡運輸機制：被囊蛋白、Rab GTPase 與 SNARE 膜融合)**
- **12.4 Lysosomes (溶體酸性水解酶、M6P 靶向、內吞途徑與自噬作用)**

## Frameworks Introduced
### Signal Hypothesis & ER Translocation Engine (信號假說與內質網轉位引擎模型)
- **When to use**: 分析分泌蛋白與穿膜蛋白進入分泌途徑的第一道共轉譯閘門
- **How to apply**:
1. 信號胜肽露頭與暫停：游離核醣體轉譯出新生多胜肽鏈 N 端疏水信號胜肽（約 16-30 個胺基酸，核心含 8 個以上疏水殘基）。
2. SRP 鎖定：信號辨識顆粒 (SRP，由 7SL RNA 與 6 個蛋白質亞基組成) 結合信號胜肽，並插入核醣體延伸因子結合位點，**暫停多胜肽鏈轉譯延伸**，防止未摺疊蛋白在細胞質過早釋放。
3. 靶向對接：SRP 導引整個核醣體複合體至內質網膜表面，與 **SRP 受體 (SR)** 結合；兩者相互刺激內在 GTP 水解，SRP 解離釋放。
4. Sec61 易位子通道開通：核醣體緊密對接到內質網膜的 **Sec61 異三聚體易位子 (Translocon)** 上，轉譯重啟，新生胜肽以環狀插入 (Loop insertion) 形式穿入中央親水孔道。
5. 切割與拓撲形成：
   - 分泌性可溶蛋白：內質網腔面的 **信號胜肽酶 (Signal Peptidase)** 切斷信號胜肽，蛋白質完全釋放至內質網腔。
   - 穿膜膜蛋白：疏水性穿膜結構域作為「終止轉移序列 (Stop-transfer)」或「內部起始轉移信號 (Internal start-transfer)」，促使 Sec61 通道側向閘門 (Lateral gate) 打開，將 α-螺旋穿膜段排入膜磷脂質雙層中鎖定方向拓撲。

### Calnexin/Calreticulin Quality Control & ERAD Pathway (內質網品質管制循環與 ERAD 降解途徑)
- **When to use**: 評估內質網腔內醣蛋白摺疊監控、重修飾與終極銷毀機制
- **How to apply**:
1. 核心醣鏈前驅物轉移：在粗糙內質網中，由寡糖轉移酶 (OST) 將預先在多萜醇 (Dolichol) 載體上合成的 14 醣核心 ($Glc_3Man_9GlcNAc_2$) 一次性共價轉移至受質的 $Asn-X-Ser/Thr$ 位點。
2. 葡萄糖修整：葡萄糖苷酶 I 與 II 連續切除外層兩分子葡萄糖，留下帶有**單一末端葡萄糖**的 $Glc_1Man_9GlcNAc_2$ 構型。
3. 伴侶蛋白咬合摺疊：膜結合型 **Calnexin** 或可溶型 **Calreticulin**（鈣依賴性凝集素伴侶）特異結合單葡萄糖殘基，並協同二硫鍵異構酶 ERp57 協助多胜肽折疊。
4. 判定與分支：
   - 葡萄糖苷酶 II 切除最後一顆葡萄糖，使其自 Calnexin 解離。
   - 若折疊正確天然：送入 COPII 囊泡，運往高基氏體。
   - 若仍未完全折疊：**UGGT (UDP-葡萄糖:醣蛋白葡萄糖轉移酶)** 作為摺疊感應器，專一辨識暴露之疏水斑塊，重新給該醣鏈加上一顆葡萄糖（轉回 $Glc_1Man_9GlcNAc_2$），送回 Calnexin 再次折疊。
5. ERAD 降解 (內質網關聯降解)：若蛋白質長期無法折疊，內質網甘露糖苷酶慢速切除特定甘露糖生成 $Man_8$ 構型（作為時間超時死亡標籤），被 EDEM 凝集素辨識，經逆向易位通道 (Dislocon) 排入細胞質，被 E3 連接酶多聚泛素化，由 26S 蛋白酶體完全粉碎。

### Vesicular Trafficking Coat, Rab & SNARE Fusion Machinery (囊泡被囊選擇、Rab 導航與 SNARE 融合引擎)
- **When to use**: 解析胞內膜泡出芽、定向導航與雙層脂質融合的物理化學架構
- **How to apply**:
1. 被囊蛋白出芽分選：
   - **COPII**：介導內質網 $\to$ 順面高基氏體之順向運輸 (Anterograde)。由 Sar1 GTPase 活化招募 Sec23/24 (抓取貨物受體) 與 Sec13/31 (組裝外籠架出芽)。
   - **COPI**：介導高基氏體 $\to$ 內質網之逆向回收 (Retrograde) 及高基氏體囊間逆運。由 Arf1 GTPase 活化招募 Coatomer，辨識可溶性 ER 蛋白的 **KDEL** 回收信號或膜蛋白的 **KKXX** 信號。
   - **Clathrin (網格蛋白)**：介導反面高基氏體 (TGN) $\to$ 內體/溶體，以及質膜受體介導胞吞作用。由 AP-1/AP-2/AP-3 轉接蛋白招募三腳蛋白複合體 (Triskelion) 組裝成六邊形/五邊形網格，由 **Dynamin** 大 GTPase 藉由 GTP 水解在囊泡頸部緊縮掐斷出芽。
2. Rab GTPase 導航繫留：囊泡脫去外被蛋白後，膜表面特異 **Rab GTPase**（如 Rab5 標記早期內體，Rab7 標記晚期內體/溶體）特異結合靶膜表面相應的巨分子繫留因子 (Tethering factors)，實現初始特異對接。
3. SNARE 假說與膜融合：
   - 囊泡膜上的單鏈 **v-SNARE (如 Synaptobrevin/VAMP)** 與標靶膜上的三鏈 **t-SNARE (如 Syntaxin 與 SNAP-25)** 相互纏繞，自發組裝形成極其堅固的平行 **四螺旋束 (trans-SNARE 複合體 / 融合圈)**。
   - 四螺旋捲縮釋放龐大機械自由能，強行排擠出兩膜接觸面之間的水化水分子層，將兩膜拉近至 $<1.5\text{ nm}$，驅動外小葉融合（半融合 Hemifusion）進而孔道完全開通實現內容物釋放。
   - 融合後處於 cis 構型的無活性 SNARE 複合體，由 **NSF** 與 **α-SNAP** 消耗 ATP 水解強行解開，回收到囊泡循環再利用。

## Key Concepts
- **SRP (信號辨識顆粒)**: 由 7SL 小胞質 RNA 與 6 個蛋白質次單元組裝而成的核糖核蛋白顆粒，專一辨識新生鏈疏水信號胜肽並短暫停滯轉譯。
- **Sec61 Translocon (Sec61 易位子通道)**: 內質網膜上的核心蛋白質轉位親水通道複合體，含有環狀孔道與可側向打開的側門，引導胜肽穿膜或側向滑入膜脂質。
- **KDEL Sequence (KDEL 回收序列)**: 可溶性內質網駐留蛋白（如 BiP, PDI）C 端的四肽信號 Lys-Asp-Glu-Leu；若不慎隨囊泡流至高基氏體，被高基氏體順面的 KDEL 受體於微酸環境中高親和力結合，由 COPI 囊泡打包逆向送回內質網。
- **UGGT**: 內質網品質監控的核心感應酵素，特異辨識未完全折疊蛋白質暴露的疏水基團，重新加上葡萄糖引導其重新進入 Calnexin 摺疊循環。
- **Mannose-6-Phosphate (M6P, 甘露糖-6-磷酸)**: 靶向溶體酸性水解酶的專一性分選標籤，於順面高基氏體由 GlcNAc-磷酸轉移酶辨識特定信號斑點並加上 M6P 標記。
- **I-Cell Disease (包涵體細胞病 / 黏脂質沉積症 II)**: 因 GlcNAc-磷酸轉移酶基因突變導致溶體水解酶缺乏 M6P 標籤，所有水解酶全數錯誤分泌至細胞外血液，溶體內因缺乏消化酵素形成大量巨大未消化包涵體。
- **Dynamin (甘露蛋白大 GTPase)**: 在網格蛋白包被小凹 (Clathrin-coated pit) 出芽末期在囊泡頸部組裝成螺旋聚合物，水解 GTP 產生機械力掐斷膜囊泡。
- **Synaptobrevin & Syntaxin (突觸小泡蛋白與突觸融合蛋白)**: 神經突觸神經傳導物質釋放的經典 SNARE 對：Synaptobrevin (v-SNARE) 與 Syntaxin/SNAP-25 (t-SNARE) 介導突觸囊泡與突觸前膜毫秒級極速融合。
- **Tetanus & Botulinum Toxins (破傷風毒素與肉毒桿菌毒素)**: 具備高度專一性鋅內肽酶活性的神經毒素，專一性裂解切斷 Synaptobrevin、Syntaxin 或 SNAP-25 等 SNARE 蛋白，阻斷神經傳導物質胞吐釋放。
- **Gaucher Disease (高雪氏症)**: 最常見的溶體儲積症，因編碼葡萄糖腦苷脂酶 (*GBA*) 基因突變導致葡萄糖腦苷脂在巨噬細胞溶體內異常蓄積，引發肝脾腫大與骨痛。

## Mental Models
- **Think of the Signal Peptide and SRP as an Uber Booking for the Ribosome (將信號胜肽與 SRP 視為核醣體的專車接送預約)**: 信號胜肽是一抬頭露出的叫車信號，SRP 專車接單後立即踩剎車（暫停轉譯），穩穩將核醣體送達內質網碼頭（Sec61 易位子）後才放行開工。
- **Think of KDEL Receptor as a Lost-and-Found Boomerang (將 KDEL 受體視為失物招領迴力鏢)**: 本該留在內質網的家政工（BiP）若不小心隨人流漂到高基氏體，高基氏體順面的 KDEL 門禁刷到條碼，立刻用 COPI 回收膠囊將其彈回內質網老家。
- **Think of SNAREs as a Molecular Zipper Squeezing Water Out (將 SNARE 複合體視為拉合擠水的分子拉鍊)**: v-SNARE 與 t-SNARE 就像拉鍊兩排鋸齒，一旦咬合就順向一拉到底，強大的拉力將兩層膜中間的水分子硬生生擠出，強迫兩片膜脂質融為一體。

## Anti-patterns
- **混淆 COPI 與 COPII 囊泡的運輸方向：**COPII 是順向**（從內質網到高基氏體，Forward）；**COPI 是逆向**（從高基氏體回收到內質網，以及高基氏體囊泡間逆運，Backward）。**: 在分泌運輸抑制劑考題中顛倒兩種被囊方向。
- **誤以為神經毒素（肉毒毒素與破傷風毒素）是破壞離子通道：肉毒毒素與破傷風毒素的真正分子標靶是 **SNARE 複合體蛋白（裂解 Synaptobrevin, SNAP-25 或 Syntaxin）**，阻斷突觸小泡與突觸前膜的對接融合，導致乙醯膽鹼或抑制性遞質無法胞吐釋放。**: 在神經毒理學分子機制題目中誤答受體或通道阻斷。
- **忽視 I-cell disease 患者血清中溶體酵素濃度異常偏高的反常現象：病患組織細胞溶體內雖然極度缺乏水解酶，但其血清中各類水解酶濃度反而**異常飆高**，因為缺乏 M6P 標籤的酵素並未被破壞，而是全部沿默認的構成型分泌途徑被「傾倒出細胞外」。**: 在臨床生化診斷推理中誤判酵素合成停止。

## Reference Tables
| 囊泡運輸系統 | 主要外被蛋白 (Coat) | 小 GTPase 分子開關 | 辨識之分選信號序列 | 典型起始供體膜與靶向接受膜 |
| :--- | :--- | :--- | :--- | :--- |
| **COPII 囊泡** | Sec23/Sec24 (內層), Sec13/Sec31 (外層) | **Sar1** (Sec12 介導 GEF 交換) | 雙酸性基序 (Asp-X-Glu / DXE) 等 | **內質網 (ER) $\to$ 順面高基氏體 (cis-Golgi)** (順向運輸) |
| **COPI 囊泡** | Coatomer ($\alpha, \beta, \beta', \gamma, \delta, \epsilon, \zeta$ 七聚體) | **Arf1** (高基氏體膜 GEF 活化) | **KDEL** (經受體), **KKXX** (穿膜尾) | **高基氏體 $\to$ 內質網**，及高基氏體囊間逆運 (逆向回收) |
| **Clathrin (AP-1)** | Clathrin 三腳蛋白 + AP-1 接頭蛋白複合體 | **Arf1** | 酪胺酸基序 (YXX$\Phi$), 雙白胺酸 | **反面高基氏體 (TGN) $\to$ 內體/溶體** (M6P 受體運輸) |
| **Clathrin (AP-2)** | Clathrin 三腳蛋白 + AP-2 接頭蛋白複合體 | 膜磷脂質 $PI(4,5)P_2$ 協同結合 | NPXY 基序 (如 LDL 受體尾部) | **質膜 $\to$ 早期內體** (受體介導胞吞作用) |
| **Clathrin (AP-3)** | Clathrin 相關 / 非典型 AP-3 複合體 | **Arf1** | 雙白胺酸基序 ([D/E]XXXL[L/I]) | **TGN 或早期內體 $\to$ 晚期內體/溶體/黑素體** |

## Worked Example
**分子遺傳病理案例：家族性高膽固醇血症 (FH) 之 LDL 受體突變分類推導**

1. **LDL 膽固醇顆粒受體介導胞吞途徑**：
   - LDL 顆粒外包被載脂蛋白 ApoB-100。
   - 質膜上 LDL 受體 (LDLR) 胞外域結合 ApoB-100，胞質尾部帶有 **NPXY (Asn-Pro-X-Tyr)** 轉位信號。
   - 轉接蛋白 AP-2 辨識 NPXY 信號，將 LDLR 富集於網格蛋白被囊小凹 (Clathrin-coated pits) 內。
   - 內吞後進入早期內體，內體微酸性環境 (pH ~6.0) 促使受體解離釋放 LDL 貨物；受體回收到質膜，LDL 送至溶體降解出游離膽固醇。
2. **Goldstein & Brown 經典突變品系分析 (Class 4 轉位缺陷型)**：
   - 某患童表現極端高膽固醇血症（血清膽固醇 $>800\text{ mg/dL}$），十歲前發生心肌梗塞。
   - **生化檢測**：病患成纖維細胞表現之 LDLR 數量與野生型相當，且與放射性 $^{125}I\text{-LDL}$ 的結合親和力 ($K_d$) 完全正常！
   - **螢光顯微成像**：結合的 $^{125}I\text{-LDL}$ 均勻彌散分佈於全細胞質膜表面，**完全無法聚集進入被囊小凹**，細胞亦無任何內吞攝入現象。
3. **基因定序與結論**：
   - 定序揭示其 *LDLR* 基因第 807 位胺基酸發生單一錯義突變：$$\text{Tyr (酪胺酸)} \to \text{Cys (半胱胺酸)}$$
   - 破壞了胞質尾部的 **NPXY** 結構基序，導致 AP-2 接頭蛋白無法識別抓取 LDLR，受體無法掛載進入網格蛋白包被小凹，徹底喪失內吞清除能力，直接證實胞內尾部短肽是引導膜蛋白進入特定囊泡的郵政編碼。

## Key Takeaways
1. 分泌蛋白與膜蛋白透過疏水信號胜肽經 SRP 引導至內質網 Sec61 易位子通道進行共轉譯轉位。
2. 內質網 Calnexin/Calreticulin 伴侶系統透過監控單葡萄糖 N-醣鏈指導蛋白質折疊，UGGT 作為折疊感測器決定再折疊或 ERAD 銷毀。
3. 囊泡出芽由 COPII（ER $	o$ 高基氏體順向）、COPI（高基氏體 $	o$ ER 逆向）與 Clathrin（TGN/質膜 $	o$ 內體胞吞）分工執行。
4. Rab GTPase 提供囊泡與靶膜的專一性對接繫留，SNARE 複合體四螺旋束緊縮克服水化斥力驅動雙層膜物理融合。
5. 溶體水解酶依賴順面高基氏體加上之 M6P 標籤進行專一分選，缺乏該標籤將引發嚴重的包涵體細胞病 (I-cell disease)。

## Connects To
- **Ch 10 Protein Synthesis, Processing, and Regulation**: 銜接核醣體轉譯延伸、N-醣基化核心轉移與泛素-蛋白酶體 (ERAD) 降解。
- **Ch 15 The Plasma Membrane**: 擴展質膜受體介導網格蛋白胞吞作用與 LDL 受體循環利用。
- **Ch 17 Cell Signaling**: 探討活化膜受體（如 EGFR）經由內吞進入溶體降解達成信號衰減鈍化。
