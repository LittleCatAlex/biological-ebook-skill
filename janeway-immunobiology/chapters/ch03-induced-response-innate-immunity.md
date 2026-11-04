# Chapter 3: The Induced Response of Innate Immunity (先天免疫的誘導反應)

> **Part**: Part I — An Introduction to Immunobiology and Innate Immunity (免疫生物學導論與先天免疫)

## Core Idea
當病原體突破第一道屏障，巨噬細胞與樹突細胞透過細胞表面（TLR4/2）、內體腔（TLR3/7/9）及細胞質溶膠（NLR、RLR、cGAS-STING）四維 PRR 感應陣列辨識病原核酸與結構成分；活化 NF-κB、AP-1 與 IRF 轉錄因子釋放促炎因子（TNF-α、IL-1β、IL-6）與 I 型干擾素，引導白血球依序滾動、活化、牢固黏附並穿過血管內皮浸潤發炎病灶，協同 NK 細胞消除被感染細胞。

## Sections Outline
- **3.1 Pattern recognition receptors (PRRs) (模式識別受體超家族：TLRs、NLRs、RLRs 與 cGAS-STING)**
- **3.2 Inflammatory cytokines and chemokines (發炎細胞激素、趨化因子與白血球血管外滲四步曲)**
- **3.3 Innate lymphoid cells and Natural Killer (NK) cells (先天淋巴球 (ILCs) 與自然殺手細胞 (NK cells) 的活化與缺失自我辨識)**

## Frameworks Introduced
### PRR Subcellular Architecture & Signaling Highway (模式識別受體亞細胞拓撲與信號網絡)
> **目的**：依據病原體化學本質與感染定位分析特異 PRR 活化途徑

1. **細胞表面 TLRs (辨識胞外病原表面分子)**：
   - **TLR4 (MD-2/CD14 輔助)**：專一辨識革蘭氏陰性菌外膜 **LPS (脂多醣)**。
   - **TLR2/TLR1 異二聚體**：辨識三醯基脂胜肽；**TLR2/TLR6**：辨識雙醯基脂胜肽與酵母多醣。
   - **TLR5**：辨識細菌鞭毛蛋白 (Flagellin)。
2. **內體腔 TLRs (辨識被內吞病原之外源核酸)**：
   - **TLR3**：辨識病毒 **雙股 RNA (dsRNA)** $\to$ 經 **TRIF** 轉接蛋白活化 **IRF3**，誘導表現 **I 型干擾素 (IFN-α/β)**。
   - **TLR7 / TLR8**：辨識病毒 **單股富含 U/G 之 RNA (ssRNA)** $\to$ 經 MyD88 活化 IRF7 與 NF-κB。
   - **TLR9**：辨識未甲基化之細菌與病毒 **CpG DNA** $\to$ 經 MyD88 活化。
3. **細胞質溶膠感應器 (監控突破進入胞漿之隱匿感染)**：
   - **cGAS-STING 途徑**：cGAS 感應胞漿異常雙股 DNA $\to$ 催化合成非典型環二核苷酸 **2'3'-cGAMP** $\to$ 結合內質網膜受體 **STING** $\to$ TBK1 磷酸化 **IRF3**，強烈爆發 I 型干擾素抗病毒反應。
   - **RIG-I / MDA5 (RLRs)**：RIG-I 辨識帶有 5'-三磷酸 (5'-ppp) 的短雙股 RNA；MDA5 辨識長 dsRNA $\to$ 經線粒體外膜 **MAVS** 活化 IRF3 與 NF-κB。
   - **NLRP3 發炎體 (Inflammasome)**：感應鉀離子外流、活性氧或尿酸結晶 $\to$ 招募 ASC 與 Procaspase-1 組裝發炎體輪狀複合體 $\to$ 切割活化 **Caspase-1** $\to$ 將前驅物 pro-IL-1β 與 pro-IL-18 剪切為成熟活性促炎因子，並裂解 Gasdermin D 誘發細胞焦亡 (Pyroptosis)。

### Leukocyte Extravasation Four-Step Cascade (白血球血管外滲四部曲模型)
> **目的**：解析發炎部位循環中性球與單核球精準穿透血管內皮的力學-化學級聯

1. **步驟 1：捕捉與低親和力滾動 (Capture & Rolling)**：
   - 局部 TNF-α 與 IL-1β 刺激血管內皮細胞將韋伯-帕拉德小體 (Weibel-Palade bodies) 中的 **P-selectin** 迅速轉位至管腔表面，隨後上調 **E-selectin**。
   - 選擇素結合中性球表面修飾有唾液酸化路易斯 X 抗原 (s-Lex) 的醣蛋白配體。
   - 結合力弱於血流剪切力，細胞在內皮表面呈現翻滾減速運動。
2. **步驟 2：趨化活化與整合素親和力切換 (Activation)**：
   - 內皮表面固著的高濃度趨化因子 **CXCL8 (IL-8)** 結合中性球表面 GPCR 受體 (CXCR1/2)。
   - 觸發胞內 G 蛋白級聯進行「**Inside-Out 信號傳導**」，促使中性球表面整合素 **LFA-1 (αLβ2)** 構型展開，親和力飆升千倍。
3. **步驟 3：高親和力牢固黏附 (Firm Adhesion & Arrest)**：
   - 活化的高親和力 LFA-1 牢固結合發炎內皮表面大幅上調的 **ICAM-1**。
   - 中性球完全停止滾動，緊密貼附於血管壁上並變扁平。
4. **步驟 4：穿越內皮與化學趨化導航 (Diapedesis / Transmigration)**：
   - 經由 PECAM-1 (CD31) 與 JAM 分子引導，中性球穿過相鄰內皮細胞之間的連接縫隙。
   - 釋放基質金屬蛋白酶 (MMPs) 消化血管基底膜，沿組織間隙中 CXCL8、C5a 與 fMLF 形成的濃度梯度爬向感染靶心執行吞噬。

### NK Cell Missing-Self Discrimination Engine (自然殺手細胞缺失自我辨識引擎)
> **目的**：分析 NK 細胞如何在健康細胞與被病毒感染或癌變細胞間做出殺傷決策

1. 雙受體制衡架構：
   - **活化性受體 (Activating Receptors)**：如 NKG2D，辨識因 DNA 損傷或應激在細胞表面過量表現的應激配體 (MIC-A, MIC-B, ULBPs)；胞內帶有 ITAM 基序。
   - **抑制性受體 (Inhibitory Receptors)**：如 KIR 家族或 CD94:NKG2A，專一性辨識正常自體細胞表面表現的 **自身古典 MHC-I 類分子 (HLA-A, B, C)**；胞內帶有 **ITIM 基序**。
2. 生理耐受狀態：健康細胞表面表現豐富的自體 MHC-I 類分子，抑制性受體與 MHC-I 結合引發 ITIM 酪胺酸磷酸化，招募磷酸酶 **SHP-1**，強力去磷酸化阻斷活化性受體下游信號，**殺傷被完全鎖定關閉**。
3. 病理「缺失自我 (Missing-Self)」觸發：許多病毒（為逃避 CD8+ CTL 殺傷）或腫瘤細胞下調或徹底丟失 MHC-I 類分子表現 $\to$ 抑制性信號完全消失 $\to$ 活化性受體 (NKG2D) 信號佔絕對優勢 $\to$ NK 細胞極化釋放穿孔素 (Perforin) 與顆粒酶 (Granzyme)，迅速誘發標靶細胞凋亡。

## Key Concepts & Vocabulary
- **TLR4 (Toll 樣受體 4)**：辨識革蘭氏陰性菌外膜 LPS 的核心受體，透過 MD-2 輔助二聚化，經 MyD88 途徑活化 NF-κB 驅動發炎，或經 TRIF 途徑誘導 I 型干擾素。
- **MyD88 (骨髓分化初級反應蛋白 88)**：除 TLR3 以外所有 TLRs 共用的核心胞質轉接蛋白，含有 TIR 結構域與死亡結構域 (DD)，招募 IRAK4/1 激酶激活 IKK 複合體驅動 NF-κB 入核。
- **cGAS-STING Pathway**：細胞質異常雙股 DNA 感應軸；cGAS 催化合成 2'3'-cGAMP 作為二級信使活化 STING，誘發 TBK1-IRF3 磷酸化並大量分泌 I 型干擾素。
- **NLRP3 Inflammasome (NLRP3 發炎體)**：由感測蛋白 NLRP3、接頭蛋白 ASC 與 Caspase-1 前驅物組裝的胞質多蛋白複合體，專職催化 IL-1β/IL-18 成熟及誘發焦亡。
- **Pyroptosis (細胞焦亡)**：由 Caspase-1 或 Caspase-11/4/5 剪切 Gasdermin D (GSDMD) 生成 N 端穿孔片段，在質膜形成大孔引發細胞吸水脹破並爆發性釋放發炎因子的促炎性死亡。
- **Proinflammatory Cytokines (三大核心促炎因子)**：IL-1β、TNF-α 與 IL-6；局部促進血管擴張滲透並活化白血球，全身引發下視丘發熱中樞致熱、誘導肝臟合成急性期蛋白 (CRP, MBL)。
- **Acute-Phase Response (急性期反應)**：肝臟在巨噬細胞釋放的 IL-6 刺激下，急劇上調分泌 C-反應蛋白 (CRP)、血清澱粉樣蛋白 A (SAA) 及纖維蛋白原的全身性適應性反應。
- **Type I Interferons (I 型干擾素, IFN-α/β)**：抗病毒防衛核心細胞激素；誘導感染與鄰近未感染細胞進入抗病毒狀態（活化 PKR 抑制轉譯、活化 2'-5' OAS 降解病毒 RNA）。
- **Respiratory Burst (呼吸爆發)**：吞噬細胞在吞噬病原後，質膜與吞噬體膜上的 NADPH 氧化酶複合體組裝，大量消耗氧氣生成超氧陰離子 ($O_2^{\bullet-}$)、$H_2O_2$ 與次氯酸 (HOCl) 殺滅病原。
- **Chronic Granulomatous Disease (CGD, 慢性肉芽腫病)**：因編碼 NADPH 氧化酶次單元（如 gp91phox）突變導致吞噬細胞呼吸爆發功能完全喪失，無法產生活性氧，反覆發生嚴重細菌感染並形成廣泛慢性肉芽腫。

## Mental Models & Analogies
### Think of the PRR Surveillance as a Layered Security Alarm System (將 PRR 監控視為四重立體安檢防盜警報)
門口（細胞表面 TLR4/2）攔截隨身危險品（LPS/胜肽）；拆包室（內體腔 TLR3/7/9）透視被扣押行李內的隱藏暗號（外源核酸）；內室大廳（細胞質 cGAS/RIG-I）監控翻牆潛入的破壞者；地下室（NLRP3 發炎體）感應到打碎玻璃（離子外流）立刻拉響滅火噴淋並引爆炸藥（焦亡）。

### Think of Leukocyte Extravasation as an Airplane Landing on an Aircraft Carrier (將白血球外滲視為艦載機在航母甲板著艦)
選擇素如減速齒輪引導飛機在甲板滑行滾動；趨化因子信號如著艦指示燈點燃抓鉤系統（整合素高親和力展開）；抓鉤死死咬住阻攔索（LFA-1 鎖定 ICAM-1）瞬間完全制動；最後滑入機庫（穿透血管內皮進入組織）。

### Think of the NK Cell Missing-Self as a Passport Control with Diplomatic Immunity (將 NK 細胞缺失自我視為外交通行護照審查)
健康體細胞出示有效外交護照（MHC-I 類分子），護照一刷抑制性受體（KIR）立刻亮綠燈放行；病毒若為自保把護照銷毀（下調 MHC-I），NK 警衛發現查無護照，當場擊斃清除。

## Common Pitfalls & Anti-Patterns
- ❌ **常見盲點**：混淆 MyD88 依賴途徑與 TRIF 依賴途徑的受體對應關係：**TLR3 是唯一完全不依賴 MyD88、嚴格專職使用 TRIF 的 TLR**（誘導 IFN-β）；而 TLR4 具備雙重性（表面經 MyD88 活化 NF-κB，內吞入內體後切換為 TRIF 誘導干擾素）；其餘所有 TLRs 均絕對依賴 MyD88。
  - ✅ **正確觀念**：在 TLR 訊息傳導網絡圖中將 TLR3 誤連至 MyD88。
- ❌ **常見盲點**：誤以為白血球外滲時整合素親和力提升是由胞外機械摩擦力引起的：LFA-1 的高親和力構型展開是由趨化因子結合中性球表面 GPCR 觸發的**胞內「由內向外 (Inside-Out)」信號轉導驅動**（涉及 Rap1 GTPase 與 Talin 結合整合素胞質尾部），而非被動物理拉伸。
  - ✅ **正確觀念**：在血管內皮黏附力學機制題中遺漏趨化信號驅動力。
- ❌ **常見盲點**：將慢性肉芽腫病 (CGD) 的生化缺陷誤認為溶酶體水解酶缺乏：CGD 的分子缺陷在於 **NADPH 氧化酶 (gp91phox 等次單元) 基因突變**，導致呼吸爆發無法產生超氧自由基活性氧，溶體水解酶本身完全正常，但因缺乏過氧化氫等強氧化劑殺菌而引發慢性肉芽腫。
  - ✅ **正確觀念**：在先天免疫遺傳病分類題中將 CGD 誤歸為溶體儲積症。

## Reference Tables
| 模式識別受體 (PRR) 家族 | 次細胞空間分佈 | 主要辨識之配體 (PAMP / DAMP) | 關鍵轉接蛋白與信號激酶 | 最終引發之細胞應答與效應分子 |
| :--- | :--- | :--- | :--- | :--- |
| **TLR4 (配合 MD-2)** | 細胞質膜表面 | 革蘭氏陰性菌 **LPS (脂多醣)** | MyD88 (早期) / **TRIF** (內吞後) | **NF-κB** $\to$ 促炎因子 (TNF-α, IL-6); **IRF3** $\to$ IFN-β |
| **TLR3** | 內體 (Endosome) 腔面 | 病毒 **雙股 RNA (dsRNA)** | **TRIF** (唯一不使用 MyD88 的 TLR) | **IRF3** $\to$ 強烈分泌 **I 型干擾素 (IFN-α/β)** |
| **TLR7 / TLR8 / TLR9** | 內體腔面 | 病毒 ssRNA (TLR7/8), 未甲基化 CpG DNA (TLR9) | **MyD88** 複合體 (IRAK4/1, TRAF6) | **IRF7** $\to$ pDC 大量分泌 IFN-α; NF-κB $\to$ 發炎反應 |
| **cGAS-STING** | 細胞質溶膠 (Cytosol) | 異常胞漿 **雙股 DNA (dsDNA)** | **2'3'-cGAMP** (第二信使) $\to$ STING | **TBK1-IRF3** $\to$ 抗病毒 I 型干擾素爆發 |
| **RIG-I / MDA5 (RLRs)** | 細胞質溶膠 | 病毒 5'-ppp-RNA (RIG-I), 長 dsRNA (MDA5) | 線粒體外膜 **MAVS** 蛋白複合體 | **TBK1-IRF3** 與 **NF-κB** 協同活化抗病毒應答 |
| **NLRP3 發炎體** | 細胞質溶膠 | $K^+$ 外流、線粒體 ROS、尿酸結晶、膽固醇 | 接頭蛋白 **ASC** 招募 **Procaspase-1** | 活化 **Caspase-1** $\to$ 成熟分泌 **IL-1β/IL-18** + 誘導 **焦亡** |

## Worked Example
**分子免疫學案例推導：敗血性休克 (Septic Shock) 中 LPS-TLR4 暴走與全身性毛細血管滲漏機制**

1. **局部感染 vs 全身血行感染之 TNF-α 雙刃劍效應**：
   - **局部組織感染**：巨噬細胞表面 TLR4 結合少量 LPS，分泌生理劑量 TNF-α $\to$ 局部血管擴張、內皮黏附分子上調、滲出纖維蛋白原形成血栓封鎖感染病灶防止病原擴散，白血球湧入清除病原，具有高度保護性。
   - **全身菌血症 (革蘭氏陰性菌血行感染)**：數十億細菌外膜游離 LPS 大規模湧入血液循環，血中單核球與脾臟/肝臟枯否細胞表面 TLR4 全面被激發。
2. **全身性細胞激素風暴 (Cytokine Storm) 爆發**：
   - 巨噬細胞在數小時內向循環系統傾瀉天文數字量的 **TNF-α、IL-1β 與 IL-6**。
   - 全身微血管內皮細胞受到高濃度 TNF-α 刺激，**全身毛細血管平滑肌劇烈擴張且內皮細胞間隙全面解離散開**。
   - **毛細血管通透性惡性暴增**：海量血漿液體與血漿白蛋白滲漏至周邊組織間隙，引發全身體液失衡。
3. **多器官衰竭病理推導**：
   - **血管內有效循環血容量斷崖式崩潰** $\implies$ 系統動脈血壓急劇暴跌（休克狀態，對升壓藥無反應）。
   - **全身微血栓形成 (DIC, 瀰漫性血管內凝血)**：TNF-α 誘導血管內皮暴露組織因子 (Tissue Factor) 並下調抗凝血酶，觸發全身微循環廣泛微血栓組裝，消耗全部血小板與凝血因子，引發廣泛組織缺血壞死與後續不可控大出血。
   - 肺部毛細血管滲漏導致肺泡積水，引發急性呼吸窘迫症候群 (ARDS)；腎臟微循環衰竭致無尿，最終死於不可逆多器官功能衰竭 (MODS)。

## Key Takeaways
1. PRRs 四維分工：細胞表面（TLR4/2）、內體（TLR3/7/9）與細胞質溶膠（cGAS-STING, RLRs, NLRP3）監控不同感染定位。
2. TLR3 專職透過 TRIF 途徑誘導 I 型干擾素，TLR4 具備 MyD88（促炎）與 TRIF（干擾素）雙重偶聯，其餘主要使用 MyD88。
3. NLRP3 發炎體感應細胞應激組裝活化 Caspase-1，剪切產生活性 IL-1β/IL-18 並裂解 GSDMD 誘發促炎性細胞焦亡。
4. 白血球外滲經歷滾動（選擇素）、活化（趨化因子 GPCR）、牢固黏附（LFA-1 鎖定 ICAM-1）與穿出四步力學級聯。
5. NK 細胞透過抑制性受體（KIR 辨識自體 MHC-I 產生 ITIM 抑制）與活化性受體（NKG2D 辨識應激配體）的制衡執行缺失自我殺傷。

## Connects To
- **Ch 2 Innate Immunity**: 比對補體 C3a/C5a 過敏毒素與促炎細胞激素在引導白血球血管外滲中的協同效應。
- **Ch 7 Lymphocyte Receptor Signaling**: 深入 ITAM（活化）與 ITIM（招募 SHP-1 磷酸酶抑制）基序在受體信號轉導中的生化對抗。
- **Ch 11 Integrated Dynamics**: 銜接樹突細胞被 PRR 活化後如何上調 CCR7 遷移至淋巴結引導適應性 T 細胞分化。
