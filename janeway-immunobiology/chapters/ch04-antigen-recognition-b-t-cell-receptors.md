# Chapter 4: Antigen Recognition by B-cell and T-cell Receptors (B細胞與T細胞受體的抗原辨識)

> **Part**: Part II — The Recognition of Antigen (抗原辨識)

## Core Idea
B 細胞受體（抗體）與 T 細胞受體以模組化免疫球蛋白結構域（Ig domain）建構抗原辨識界面：抗體由兩條重鏈與兩條輕鏈藉雙硫鍵連接成 Y 型分子，其可變區的三個高變環（CDR1/2/3）直接辨識天然構型抗原表位；TCR（α:β 異二聚體）則專一辨識被自身 MHC 分子呈遞的變性胜肽短鏈，結合 CD4 或 CD8 共受體共同維繫 MHC 限制性辨識。

## Sections Outline
- **4.1 The structure of a typical antibody molecule (典型抗體分子的 Y 型四鏈結構、結構域與鉸鏈區)**
- **4.2 The interaction of the antibody molecule with specific antigen (抗體超變區 (CDRs)、表位結合特異性與非共價結合力)**
- **4.3 Antigen recognition by T cells (T 細胞受體 (TCR) 結構、MHC 限制性與肽-MHC 複合物結合)**
- **4.4 Structural variation in immunoglobulin constant regions (免疫球蛋白五大同種型 (IgM, IgD, IgG, IgA, IgE) 之結構差異與效應特化)**

## Frameworks Introduced
### Antibody Architecture & Enzymatic Cleavage Fragmentation Model (抗體幾何結構與酵素水解片段化模型)
> **目的**：分析免疫球蛋白結構域、鉸鏈區柔性及蛋白質水解片段特徵

1. 基本四鏈構造：兩條相同重鏈 (Heavy chain, H, ~50 kDa) 與兩條相同輕鏈 (Light chain, L, ~25 kDa) 透過鏈間二硫鍵共價偶聯成 Y 型單體（總分子量 ~150 kDa）。
   - 輕鏈：包含一個可變結構域 ($V_L$) 與一個恆定結構域 ($C_L$)；分為 $\kappa$ 鏈與 $\lambda$ 鏈。
   - 重鏈：包含一個可變結構域 ($V_H$) 與三個（IgG, IgA, IgD 為 $C_H1, C_H2, C_H3$）或四個（IgM, IgE 含有額外 $C_H4$ 且缺乏鉸鏈區）恆定結構域。
2. 鉸鏈區 (Hinge Region) 柔性：位於 $C_H1$ 與 $C_H2$ 之間，富含脯胺酸 (Pro) 與半胱胺酸 (Cys)；賦予兩隻 Fab 手臂自由擺動旋轉角度（$0^\circ - 180^\circ$），以最佳距離同時咬合兩個不同間隔之抗原決定基。
3. 經典酵素水解裂解特徵：
   - **木瓜蛋白酶 (Papain) 水解**：在鉸鏈區二硫鍵的**氨基端 (N-端)** 剪切 $\to$ 產生 **2 個單價的 Fab 片段** (Fragment antigen-binding, 各含完整抗原結合位點，可結合抗原但無法交聯沉澱) + **1 個結晶片段 Fc** (Fragment crystallizable, 結合補體 C1q 與細胞 Fc 受體)。
   - **胃蛋白酶 (Pepsin) 水解**：在鉸鏈區二硫鍵的**羧基端 (C-端)** 剪切 $\to$ 保留重鏈間雙硫鍵，產生 **1 個雙價的 $F(ab')_2$ 片段** (具雙價交聯凝集能力) + 碎裂的 Fc 胜肽段 ($pFc'$)。

### CDR Complementarity & Noncovalent Binding Topology (互補決定區 CDRs 與抗原結合化學力拓撲)
> **目的**：解析抗體與 TCR 如何在三維立體構型中以極高親和力結合特定抗原決定基 (Epitope)

1. 高變區與骨架區排布：可變結構域（$V_H$ 與 $V_L$）由 9 條反平行 $\beta$-摺疊股構成 Ig 摺疊桶狀骨架，股間連接的 3 個外露柔性環狀結構具備極端變異的胺基酸序列，稱為 **高變區 (Hypervariable regions)** 或 **互補決定區 (CDRs)**。
2. 抗原結合位點組裝：
   - 每個抗原結合手腕由 $V_H$ 的 CDR1, CDR2, CDR3 與 $V_L$ 的 CDR1, CDR2, CDR3 共 **6 個 CDR 環** 在三維空間匯聚排布而成。
   - **CDR3 是多樣性最高、最具決定性的抗原接觸中心**（由 V-D-J 連接點多樣性直接決定）。
3. 抗原表位類型：
   - **構型表位 (Conformational / Discontinuous epitope)**：由蛋白質一級序列中相距遙遠但經天然立體折疊靠攏在一起的殘基構成；蛋白質變性後結合能力徹底喪失（**抗體辨識的絕大多數抗原為構型表位**）。
   - **線性表位 (Linear / Continuous epitope)**：由連續 6-10 個相鄰胺基酸短鏈構成；變性後結合不受影響（TCR 辨識之胜肽抗原均為線性表位）。
4. 結合力本質：抗體與抗原之間完全不形成共價鍵，純粹仰賴四種微弱非共價作用力的協同疊加：靜電吸引力（鹽橋）、氫鍵、凡得瓦力與疏水交互作用（最重要驅動力）。

### TCR Dual-Recognition & Co-receptor Ligation Architecture (TCR 雙重特異性辨識與共受體偶聯架構)
> **目的**：解析 T 細胞受體如何同時辨識「外源外來抗原胜肽」與「自體 MHC 分子」

1. TCR 幾何構造：由 α 鏈與 β 鏈（約 95% 循環 T 細胞）或 γ 鏈與 δ 鏈經雙硫鍵連接組裝成單價跨膜異二聚體；每條鏈包含一個可變結構域 (V) 與一個恆定結構域 (C)。
2. 結合拓撲幾何學 (Diagonal Binding Orientation)：
   - TCR 橫跨對接於 MHC 分子頂部抗原結合溝槽之上，呈現約 **$45^\circ$ 的對角線交叉咬合構型**。
   - **CDR1 與 CDR2 環**（由生殖系 V 基因直接編碼）：主要定位接觸於 **自身 MHC 分子的 α-螺旋壁**，確立 MHC 限制性（辨識自體身份標記）。
   - **CDR3 環**（跨越 V-D-J 剪接連接區，多樣性最高）：直接垂入溝槽中央，特異性深鎖結合 **外源胜肽的核心殘基**，辨識抗原特異性。
3. 共受體 (Co-receptors CD4 vs CD8) 錨定穩定：
   - **CD4**：單鏈四結構域分子 (D1-D4)，其 D1 結構域特異結合 **MHC-II 類的 $\beta_2$ 結構域**；限制 CD4+ T 細胞專一性辨識 MHC-II。
   - **CD8**：$\alpha\beta$ 異二聚體，特異結合 **MHC-I 類的 $\alpha_3$ 結構域**；限制 CD8+ T 細胞專一辨識 MHC-I。
   - 胞內偶聯：CD4 與 CD8 胞內短尾部均牢固結合酪胺酸激酶 **Lck**，將 Lck 拉至 TCR-CD3 複合體旁啟動後續磷酸化級聯。

## Key Concepts & Vocabulary
- **Immunoglobulin Domain (免疫球蛋白結構域, Ig domain)**：約 110 個胺基酸構成的經典三維蛋白質模組，由兩層反平行 $\beta$-摺疊夾心形成三明治狀結構，中央由單一保守二硫鍵緊扣。
- **Fab vs Fc Fragment (Fab 與 Fc 片段)**：Fab 為包含完整抗原結合位點的抗體手臂（含 $V_L, C_L, V_H, C_H1$）；Fc 片段為重鏈恆定區二聚體（含 $C_H2, C_H3$），媒介效應功能。
- **Complementarity-Determining Regions (CDRs, 互補決定區)**：抗體與 TCR 可變結構域中胺基酸序列變異性最高的三個環狀結構 (CDR1, CDR2, CDR3)，直接參與抗原接觸。
- **Epitope / Antigenic Determinant (抗原決定基 / 表位)**：抗原分子表面被抗體或抗原受體特異性結合識別的具體化學結構微區段（長約 5-8 個胺基酸或單醣）。
- **Affinity vs Avidity (親和力與親合力/結合力)**：Affinity 為單一抗原結合位點與單一表位之間的固有熱力學結合強度 ($K_a = 1/K_d$)；Avidity 為多價抗體（如十價 IgM）與多價抗原所有結合位點協同作用的總體功能性結合強度。
- **Isotypes (同種型)**：同一物種所有健康個體均具備的免疫球蛋白恆定區分類（五大類：IgM, IgD, IgG, IgA, IgE），由重鏈 $C_H$ 基因決定。
- **J Chain (J 鏈 / 接合鏈)**：15 kDa 富含半胱胺酸的蛋白質，催化分泌型五聚體 IgM 與二聚體 IgA 的多聚化共價組裝，並作為 Poly-Ig 受體跨上皮轉運的辨識標籤。
- **MHC Restriction (MHC 限制性)**：Zinkernagel & Doherty 1996 諾貝爾獎發現：特異性 T 細胞只能辨識與自身初級發育胸腺中相同 MHC 等位基因分子結合呈遞的特定抗原胜肽。
- **Gamma:Delta T Cells (γ:δ T 細胞)**：由 γ 與 δ 鏈組裝 TCR 的少數特化 T 細胞族群，富集於腸道與上皮黏膜，不嚴格依賴經典 MHC 限制性，可直接辨識非胜肽抗原（如磷酸化抗原、脂質）。
- **Cross-Reactivity (交叉反應)**：某抗體除了能結合其原始誘導抗原外，因幾何立體形狀相似性，亦能以較低或相當親和力結合結構高度同源的非同源抗原的現象。

## Mental Models & Analogies
### Think of the Antibody as a Flexible Grabber Tool (將抗體視為自帶彈簧雙鉸鏈的雙手夾物器)
Fc 是粗壯握把（插入底座機關發動各類效應引擎）；鉸鏈是萬向彈性關節；兩隻 Fab 手臂端點鑲嵌六個橡膠指腹（CDRs），能自由張合跨越不同間隔緊抓目標。

### Think of Papain vs Pepsin Cleavage as Cutting Above or Below the Wrist (將木瓜蛋白酶與胃蛋白酶切割視為手腕上下下刀)
木瓜蛋白酶在手腕鏈結（二硫鍵）上方剪一刀，兩隻手掌（Fab）各自分開飄散，無法雙手交聯抗原；胃蛋白酶在手腕鏈結下方剪一刀，雙手依然十指相扣（$F(ab')_2$），依然能牢牢把抗原交聯凝整合團。

### Think of TCR Recognition as Reading a Hot Dog in a Bun (將 TCR 辨識視為咬合大亨堡的麵包與熱狗)
自身的 MHC 分子是長條麵包槽（TCR CDR1/2 接觸麵包邊緣，確保這是自家的麵包）；夾在中間的變性胜肽是熱狗肉（TCR CDR3 直接咬緊肉餡，檢驗是否為有毒外國熱狗）。

## Common Pitfalls & Anti-Patterns
- ❌ **常見盲點**：混淆抗體 Fab 片段與 $F(ab')_2$ 片段在抗原凝集實驗中的表現：**Fab 片段是單價的 (Monovalent)**，雖然能特異結合可溶性抗原，但**絕對無法形成網狀晶格引發抗原沉澱或紅血球凝集**；而 **$F(ab')_2$ 片段是雙價的 (Bivalent)**，保留了雙臂交聯能力，能正常引發沉澱與凝集反應。
  - ✅ **正確觀念**：在免疫化學檢測與片段功能考題中錯判凝集能力。
- ❌ **常見盲點**：誤以為 T 細胞受體 (TCR) 可以像抗體那樣直接結合游離的天然可溶性蛋白質抗原：**經典 α:β TCR 絕對無法辨識天然球狀可溶蛋白質**；TCR 只能辨識經過 APC 細胞內加工變性、剪切成 8-20 個胺基酸短胜肽，並裝載嵌入自身 MHC 分子槽內的「胜肽-MHC 複合物 (pMHC)」。
  - ✅ **正確觀念**：在抗原辨識本質概念題中將抗體與 TCR 機制混為一談。
- ❌ **常見盲點**：忽略五聚體 IgM 的「親和力 (Affinity)」與「親合力 (Avidity)」的巨大差異：單一 IgM 單體的結合位點親和力通常很低（因為分泌於未成熟體細胞超突變前）；但由於其擁有 10 個抗原結合位點，多價協同作用使其**總體親合力 (Avidity) 極端巨大**，特別適合在感染早期超高效激活補體 C1q。
  - ✅ **正確觀念**：在生化平衡與抗體結合力評估題中混淆兩者定義。

## Reference Tables
| 免疫球蛋白同種型 | 重鏈類型與分子量 | 血清中聚體狀態與 J 鏈 | 胎盤跨膜轉運能力 | 補體經典途徑激活強度 | 主要效應特化與生理定位 |
| :--- | :--- | :--- | :--- | :--- | :--- |
| **IgM** | **μ (微米鏈)**, 含有 $C_H1-4$, ~70 kDa | **五聚體** (Pentamer, 含 J 鏈), 900 kDa | **完全不能** (分子量過大) | **極強** (單一五聚體即可激活 C1q) | 初次免疫應答第一抗體、B 細胞膜受體 BCR、血型凝集素 |
| **IgD** | **δ 鏈**, 含有 $C_H1-3$ + 長鉸鏈, ~65 kDa | **單體** (Monomer), 180 kDa | **不能** | **無活性** | 與 IgM 共表現於成熟初始 B 細胞表面，作為發育分化標記 |
| **IgG (1–4)** | **γ 鏈**, 含有 $C_H1-3$ + 鉸鏈, ~50 kDa | **單體** (Monomer), 150 kDa | **唯一能穿透胎盤** (經 FcRn 載體) | **強** (IgG3 > IgG1 > IgG2, IgG4 無) | 血液與細胞外液主力抗體、調理吞噬、中和毒素、ADCC |
| **IgA (1–2)** | **α 鏈**, 含有 $C_H1-3$ + 鉸鏈, ~55 kDa | **二聚體** (含 J 鏈及分泌組分 SC), 385 kDa | **不能** (分泌至母乳初乳) | **極弱 / 替代途徑微弱** | 黏膜免疫絕對主力、阻斷病原黏附、淚液、唾液、腸道分泌 |
| **IgE** | **ε 鏈**, 含有 $C_H1-4$, ~72 kDa | **單體** (Monomer), 190 kDa | **不能** | **無活性** | 高親和力結合肥大細胞/嗜鹼性球 FcεRI、抗蠕蟲寄生蟲、介導 I 型過敏 |

## Worked Example
**結構免疫學計算與親和力超突變實驗分析**

某實驗室利用表面電漿共振 (Surface Plasmon Resonance, SPR) 測定抗白喉毒素單株抗體之結合動力學：
1. **原始未突變初次抗體 (Antibody Germline)** 測得：
   - 結合速率常數 (Association rate, $k_{on}$) = $1.0 \times 10^5\ \text{M}^{-1}\text{s}^{-1}$
   - 解離速率常數 (Dissociation rate, $k_{off}$) = $1.0 \times 10^{-2}\ \text{s}^{-1}$
2. **生發中心親和力成熟後之高親和力抗體 (Antibody Maturation)** 測得：
   - 結合速率常數 $k_{on}' = 2.0 \times 10^5\ \text{M}^{-1}\text{s}^{-1}$
   - 解離速率常數 $k_{off}' = 1.0 \times 10^{-5}\ \text{s}^{-1}$

**問題計算推導**：
1. **平衡解離常數 ($K_d = k_{off}/k_{on}$) 計算**：
   - 初始生殖系抗體：
     $$K_d = \frac{1.0 \times 10^{-2}}{1.0 \times 10^5} = 1.0 \times 10^{-7}\ \text{M} = \mathbf{100\text{ nM}}$$
   - 親和力成熟後抗體：
     $$K_d' = \frac{1.0 \times 10^{-5}}{2.0 \times 10^5} = 5.0 \times 10^{-11}\ \text{M} = \mathbf{0.05\text{ nM} = 50\text{ pM}}$$
2. **熱力學與生物學意義判定**：
   - 親和力提升倍數：$\frac{K_d}{K_d'} = \frac{100\text{ nM}}{0.05\text{ nM}} = \mathbf{2000\text{ 倍}}$！
   - 觀察動力學參數可以發現，親和力飆升 2000 倍的貢獻中，結合速率 ($k_{on}$) 僅微增 2 倍，**主要貢獻來自於解離速率 ($k_{off}$) 驟降了整整 1000 倍（由每秒解離 1% 降低至每十萬秒解離 1%）**。
   - 結構本質：體細胞超突變精確重塑了 CDR3 環的疏水堆積與氫鍵網絡，大幅降低了結合複合體的吉布斯自由能（$\Delta G^{\circ}$ 更負），使抗體如強力膠般牢固鎖死抗原，徹底杜絕毒素自抗體解離逃脫。

## Key Takeaways
1. 典型抗體由兩條重鏈與兩條輕鏈經雙硫鍵連接成 Y 型單體，木瓜蛋白酶切出 2 個單價 Fab 與 1 個 Fc，胃蛋白酶切出 1 個雙價 $F(ab')_2$。
2. 可變結構域中由骨架區支撐外露的 6 個 CDR 環（CDR1/2/3）組裝成抗原結合位點，CDR3 具有最高多樣性。
3. 抗體主要辨識天然未變性蛋白質的三維構型表位，依賴非共價力咬合；TCR 則嚴格辨識嵌入 MHC 分子槽內的線性變性胜肽短鏈。
4. TCR 以對角線方位跨接於 pMHC，CDR1/2 接觸自體 MHC 螺旋壁確立限制性，CDR3 接觸胜肽核心，CD4/CD8 共受體鎖定 MHC 恆定區並召募 Lck 激酶。
5. 五大類同種型各司其職：IgM 五聚體強效活化補體，IgG 單體穿透胎盤調理吞噬，IgA 二聚體守護黏膜分泌，IgE 單體介導肥大細胞抗寄生蟲與過敏。

## Connects To
- **Ch 1 Basic Concepts in Immunology**: 回顧抗體三大效應功能（中和、調理、補體激活）之結構基礎。
- **Ch 5 Generation of Lymphocyte Antigen Receptors**: 探討抗體與 TCR 可變區 V(D)J 體細胞基因重排之分子機制。
- **Ch 6 Antigen Presentation to T Lymphocytes**: 深入 MHC-I 與 MHC-II 分子結構及其胜肽抗原裝載生化途徑。
