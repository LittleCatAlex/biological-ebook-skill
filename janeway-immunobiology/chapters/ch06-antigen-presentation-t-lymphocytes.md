# Chapter 6: Antigen Presentation to T Lymphocytes (向T淋巴球呈現抗原與MHC分子機制)

> **Part**: Part II — The Recognition of Antigen (抗原辨識)

## Core Idea
T 細胞專一性辨識與主要組織相容性複合體（MHC）分子結合的胜肽抗原：MHC-I 類分子裝載由胞漿蛋白酶體切割並經 TAP 泵入內質網的內源性胜肽（8-10 胺基酸），呈遞給 CD8+ 細胞毒性 T 細胞；MHC-II 類分子在內體溶體中經 HLA-DM 置換 CLIP 裝載外源性胜肽（13-17 胺基酸），呈遞給 CD4+ 輔助 T 細胞；樹突細胞特化的交叉呈遞則將胞外外源抗原改道裝載入 MHC-I，實現抗病毒抗腫瘤免疫初次啟動。

## Sections Outline
- **6.1 The generation of MHC class I and class II ligands (MHC-I 胞質溶膠蛋白酶體途徑與 MHC-II 內體溶體途徑)**
- **6.2 Antigen presentation by cross-presentation (樹突細胞交叉呈遞 (Cross-Presentation) 與 CD8+ T 細胞啟動)**
- **6.3 The major histocompatibility complex and its function (主要組織相容性複合體 (MHC/HLA) 基因多型性與多基因性)**

## Frameworks Introduced
### MHC Class I vs Class II Processing Pathways (MHC-I 與 MHC-II 抗原加工裝載雙軌模型)
> **目的**：依據抗原來源與感染定位分析抗原胜肽加工裝載之細胞生化途徑

1. **MHC-I 類內源途徑 (Cytosolic / Proteasomal Pathway)**：
   - 抗原來源：胞漿合成之病毒蛋白、胞內菌蛋白或異常腫瘤蛋白（DRiPs，缺陷性核醣體產物）。
   - 切割加工：經泛素化標記後，由 **免疫蛋白酶體 (Immunoproteasome)**（含 β1i, β2i, β5i 催化亞基，受 IFN-γ 誘導）水解為 8-10 胺基酸長度短胜肽，C 端偏好疏水或鹼性殘基。
   - 轉位入 ER：**TAP1/TAP2 異二聚體轉運蛋白** 利用 ATP 水解將胜肽由胞漿泵入內質網腔；ERAAP 胺肽酶在 ER 腔內修剪 N 端多餘殘基。
   - 伴侶與胜肽裝載複合體 (PLC)：新生 MHC-I 重鏈經 Calnexin 輔助折疊，結合 **$\beta_2$-微球蛋白 ($\beta_2m$)**；組裝 **PLC 複合體**（包含 **Calreticulin、ERp57、Tapasin 與 TAP**）。
   - 咬合與釋放：Tapasin 將未裝載的空 MHC-I 溝槽鎖定在開放構型並拉至 TAP 開口旁；高親和力胜肽嵌入溝槽後，構型閉鎖，PLC 解離，成熟 pMHC-I 經高基氏體囊泡輸送至質膜呈現給 **CD8+ T 細胞**。
2. **MHC-II 類外源途徑 (Endocytic / Lysosomal Pathway)**：
   - 抗原來源：胞吞、吞噬攝入之胞外細菌、毒素或自噬體內含物。
   - 內質網伴侶防護：新生 MHC-II 異二聚體（$\alpha$ 鏈與 $\beta$ 鏈）在 ER 腔內與 **不變鏈三聚體 (Invariant chain, Ii / CD74)** 結合；不變鏈的 **CLIP 結構域** 直接佔據封堵抗原結合溝槽，防止 ER 內未成熟內源胜肽提早誤入，並引導複合體進入內體。
   - 內體酸化水解：進入酸化內體後，組織蛋白酶 (Cathepsins) 逐步消化切除不變鏈，僅留下 **CLIP 胜肽** 殘留在溝槽中。
   - 胜肽交換：特化分子伴侶 **HLA-DM** 結合 MHC-II，催化構型微調促使 CLIP 脫落，允許內體溶體中被酸性蛋白酶消化出的外源胜肽嵌入溝槽。
   - 輸出呈現：成熟 pMHC-II 運抵質膜呈現給 **CD4+ T 細胞**。

### Cross-Presentation Mechanics (樹突細胞交叉呈遞特殊機制)
> **目的**：解釋外源性腫瘤抗原與不感染樹突細胞的病毒如何激活初級 CD8+ CTL 殺傷反應

1. 免疫學邏輯悖論：常規 MHC-I 途徑僅處理胞漿自身合成的內源抗原；但許多病毒（如肝炎病毒）不感染專業 APC（樹突細胞），且腫瘤細胞自身缺乏共刺激分子 CD80/CD86 無法有效啟動初始 T 細胞。若無旁路途徑，初始 CD8+ T 細胞將永久無法被激活。
2. 交叉呈遞 (Cross-Presentation) 核心主體：專一由常規 **CD8α+ / CD103+ 樹突細胞 (cDC1)** 執行。
3. 胞質分流途徑 (Cytosolic Pathway of Cross-Presentation)：
   - 樹突細胞吞噬死病毒碎片、凋亡腫瘤細胞或抗原-抗體複合體。
   - 內體/吞噬體膜上的逆向易位通道 (Sec61 或特定孔道) 將吞入之外源蛋白質「逆向漏入」樹突細胞自身的**細胞質溶膠**中。
   - 外源蛋白在胞漿中被樹突細胞自身的**蛋白酶體**降解為短胜肽。
   - 隨後胜肽經由 **TAP** 重新泵入內質網或內體腔，裝載至 **MHC-I 類分子** 上。
4. 生理效應：樹突細胞表面同時高表現外源抗原-MHC-I 複合物與共刺激分子 CD80/86，成功**初次啟動 (Cross-priming)** 初始 CD8+ T 細胞分化為活化的細胞毒性殺傷 T 細胞 (CTL)。

## Key Concepts & Vocabulary
- **MHC-I Molecule (主要組織相容性複合體 I 類分子)**：由一條多型性 $\alpha$ 重鏈 (44 kDa，含 $\alpha_1, \alpha_2, \alpha_3$ 結構域) 與一條非多型性、非 MHC 編碼的 **$\beta_2$-微球蛋白 ($\beta_2m$, 12 kDa)** 組裝而成的跨膜異二聚體；結合 8-10 胺基酸短胜肽，呈遞給 CD8+ T 細胞。
- **MHC-II Molecule (主要組織相容性複合體 II 類分子)**：由一條 $\alpha$ 鏈 (34 kDa) 與一條 $\beta$ 鏈 (29 kDa) 組成的跨膜異二聚體，兩鏈均具多型性；抗原槽兩端開放，結合 13-17 胺基酸較長胜肽，呈遞給 CD4+ T 細胞。
- **TAP (抗原加工相關轉運體, TAP1/TAP2)**：內質網膜上的 ABC 家族 ATP 依賴型異二聚體轉運蛋白，專一性將胞漿蛋白質降解胜肽泵入內質網腔供 MHC-I 裝載。
- **Tapasin (TAP 關聯糖蛋白)**：胜肽裝載複合體 (PLC) 核心橋樑蛋白，將空載 MHC-I 物理連接至 TAP 孔道旁，並編輯維持溝槽開放直至高親和力胜肽嵌入。
- **Invariant Chain (Ii / CD74 / 不變鏈)**：在內質網引導 MHC-II 摺疊並以 CLIP 胜肽封鎖其溝槽、防止內源胜肽結合併導引進入內體溶體通路的分子伴侶。
- **HLA-DM**：非經典 MHC-II 樣分子伴侶，催化移除 MHC-II 溝槽中的 CLIP 胜肽，促使高親和力外源抗原胜肽快速裝載。
- **Anchor Residues (錨定殘基)**：嵌入 MHC 分子結合溝槽特定深口袋 (Pockets) 的胜肽特定胺基酸（通常為特定位置的疏水或帶電側鏈），決定該胜肽能否與特定 MHC 等位基因結合。
- **MHC Polymorphism & Polygeny (MHC 多型性與多基因性)**：多基因性指個體基因組包含多個編碼不同 MHC 鏈的獨立基因座（HLA-A, B, C; HLA-DR, DP, DQ）；多型性指群體內每一基因座存在數百至數千種不同等位基因，為遺傳多樣性最高區域。
- **Bare Lymphocyte Syndrome Type I & II (裸淋巴球症候群 I 型與 II 型)**：BLS-I 因 TAP 基因突變導致 MHC-I 無法裝載胜肽而質膜缺失，CD8+ T 細胞極度匱乏；BLS-II 因 CIITA 等轉錄因子突變導致 MHC-II 完全缺失，CD4+ T 細胞無法發育引發重症複合型免疫缺乏。
- **Superantigen (超級抗原)**：細菌外毒素（如金葡菌腸毒素 SEB、中毒性休克毒素 TSST-1），不需經細胞內加工，直接在外部同時跨接 MHC-II 外側與 TCR Vβ 結構域，多株非特異性活化高達 20% 的周邊 T 細胞引發致死性細胞激素風暴。

## Mental Models & Analogies
### Think of MHC-I Groove as a Closed Trench and MHC-II as an Open Valley (將 MHC-I 溝槽視為兩端封閉的壕溝，MHC-II 視為兩端開闊的峽谷)
MHC-I 兩端有城牆封閉，胜肽兩端必須削足適履卡進城牆內（嚴格限制 8-10 個胺基酸）；MHC-II 兩端開放如同峽谷通道，更長的胜肽鏈（13-17 個胺基酸以上）兩頭可以自由伸出懸垂在外面。

### Think of the Invariant Chain (Ii) as a Guarded Pacifier with GPS (將不變鏈視為帶有 GPS 導航的安全奶嘴)
奶嘴頭（CLIP）緊緊塞住新生 MHC-II 的嘴巴（抗原結合槽），防止其在內質網亂吃自體胜肽；後座的 GPS 天線導航整車開往內體溶體工廠，抵達後才由技師（HLA-DM）把奶嘴拔掉換上真正外源零件。

### Think of Cross-Presentation as a Border Spy Tunneling Stolen Contraband into Internal Customs (將交叉呈遞視為將境外走私品偷運入內部海關檢驗)
正常的樹突細胞內部海關（MHC-I）只管國內出產的貨物（胞漿合成蛋白）；交叉呈遞如同挖了一條暗道（Sec61 孔道），把從境外繳獲的行李（外源吞入抗原）偷偷丟進國內輸送帶，讓 CD8+ 特警也能逮捕這批境外恐怖分子。

## Common Pitfalls & Anti-Patterns
- ❌ **常見盲點**：混淆 MHC-I 與 MHC-II 結合之抗原胜肽長度與來源：**MHC-I 結合 8-10 胺基酸短胜肽**，源自胞質溶膠蛋白酶體降解的內源抗原，兩端被封閉口袋錨定；**MHC-II 結合 13-17 胺基酸（甚至更長）胜肽**，源自酸性內體溶體降解的外源抗原，兩端自由伸出溝槽外部。
  - ✅ **正確觀念**：在抗原裝載生化參數對比中混淆胜肽長度與來源。
- ❌ **常見盲點**：誤以為紅血球表面也表現正常的 MHC-I 類分子：**哺乳動物成熟無核紅血球表面完全不表現 MHC-I 類分子**；因此紅血球無法被 CD8+ CTL 監控辨識，瘧原蟲寄生於紅血球內部即是利用其缺乏 MHC-I 的天然免疫盲區進行躲避。
  - ✅ **正確觀念**：在細胞表面標記分佈題中誤將紅血球納入 MHC-I 陽性。
- ❌ **常見盲點**：忽視超級抗原 (Superantigen) 的非傳統結合模式：超級抗原**絕對不需要被 APC 吞噬消化加工成胜肽**，它直接以完整的天然蛋白質形態，同時結合在 MHC-II 分子的外側面與 TCR 的 Vβ 鏈外側面，形成三分子橋接，完全跳過了抗原專一性辨識。
  - ✅ **正確觀念**：在抗原呈遞機制題中誤將超級抗原視為常規抗原加工呈遞。

## Reference Tables
| 特徵指標 / 生化維度 | MHC-I 類分子呈遞途徑 | MHC-II 類分子呈遞途徑 |
| :--- | :--- | :--- |
| **呈遞之目標 T 細胞** | **CD8+ 細胞毒性 T 細胞 (CTL)** | **CD4+ 輔助 T 細胞 (Th1, Th2, Th17, Tfh, Treg)** |
| **抗原來源與感染定位** | **胞質溶膠內源性** (病毒、胞內菌、腫瘤突變蛋白) | **胞吞/吞噬外源性** (胞外細菌、毒素、自噬胞外物) |
| **蛋白質降解核心機器** | 胞漿 **免疫蛋白酶體** (含 LMP2, LMP7 催化亞基) | 內體溶體酸性蛋白酶 (如 **Cathepsins 組織蛋白酶**) |
| **胜肽轉運與保護因子** | **TAP1 / TAP2** 轉位泵，ERAAP 腔內修剪 | **不變鏈 (Invariant chain / CD74)**，**CLIP 胜肽** |
| **胜肽交換催化分子** | **Tapasin** (胜肽裝載複合體 PLC 構型編輯) | **HLA-DM** (催化釋放 CLIP 並裝載外源胜肽) |
| **抗原結合槽幾何構造** | 由 $\alpha_1$ 與 $\alpha_2$ 圍成，**兩端封閉** | 由 $\alpha_1$ 與 $\beta_1$ 圍成，**兩端開放** |
| **裝載胜肽長度與特徵** | **8–10 個胺基酸**，兩端錨定口袋鎖定 | **13–17 個胺基酸** (可更長)，兩端自由伸出 |
| **組織表現分佈譜** | **幾乎全體有核細胞** (無核紅血球缺乏) | **專業抗原呈遞細胞 (APCs)**: 樹突細胞、巨噬細胞、B 細胞 |

## Worked Example
**臨床免疫遺傳學案例推導：僵直性脊椎炎 (Ankylosing Spondylitis) 與 HLA-B*27 關聯機制**

1. **強烈遺傳關聯性事實**：
   - 超過 90% 的僵直性脊椎炎病患攜帶特定的 MHC-I 等位基因 **HLA-B*27**。
   - 在一般健康高加索族群中，HLA-B*27 攜帶率僅約 8%（相對風險度 Relative Risk > 100）。
2. **分子機制假說推導 (關節滑膜炎與脊椎骨贅形成)**：
   - **假說 A：關節炎致病胜肽擬態 (Arthritogenic Peptide Hypothesis)**：
     - 腸道克雷伯氏肺炎桿菌 (*Klebsiella pneumoniae*) 或沙門氏菌感染後，其外膜蛋白被蛋白酶體降解。
     - 產生的細菌胜肽其錨定殘基恰好符合 HLA-B*27 的 B 口袋與 F 口袋特徵，高親和力裝載。
     - 活化的 CD8+ T 細胞在消滅細菌後，因該細菌胜肽與脊椎軟骨自體膠原蛋白胜肽具高度立體擬態，引發跨反應性攻擊脊椎關節軟骨。
   - **假說 B：HLA-B*27 重鏈折疊錯誤與內質網應激 (Misfolding & ER Stress)**：
     - HLA-B*27 重鏈在內質網與 $\beta_2m$ 及胜肽組裝時速率極慢，其 B 結合口袋的半胱胺酸 (Cys67) 極易在腔內形成異常同源二聚體或多聚體共價二硫鍵交聯。
     - 錯誤折疊產物無法輸出，在內質網腔大量沉積，觸發劇烈的 **未折疊蛋白反應 (UPR)**。
   - **病理級聯後果**：UPR 誘發巨噬細胞與樹突細胞過量分泌促炎因子 **IL-23** $\to$ 刺激韌帶骨附著點的 ILC3 與 Th17 細胞分泌大量 **IL-17A** $\to$ 引發局部慢性破骨吸收與繼發性異常成骨細胞過度增殖，導致脊椎椎體韌帶進行性骨化融合，形成標誌性「竹節狀脊椎 (Bamboo spine)」。

## Key Takeaways
1. MHC-I 與 MHC-II 構築了區分胞內與胞外病原體的雙軌呈遞體系，分別導向 CD8+ 與 CD4+ T 細胞。
2. MHC-I 途徑利用免疫蛋白酶體降解胞漿內源蛋白，經 TAP 泵入 ER 由 Tapasin 輔助裝載 8-10 胺基酸短胜肽。
3. MHC-II 途徑利用不變鏈與 CLIP 封閉溝槽導向內體，經組織蛋白酶消化與 HLA-DM 催化置換裝載 13-17 胺基酸外源胜肽。
4. 樹突細胞特化的交叉呈遞（Cross-presentation）將胞外抗原改道至胞漿蛋白酶體與 MHC-I，是啟動抗病毒與抗腫瘤 CD8+ CTL 的必備基石。
5. MHC 具備極大多基因性與群體多型性，賦予物種抵抗多樣病原侵襲的能力，但也構成了自體免疫易感性與器官移植排斥的主要屏障。

## Connects To
- **Ch 4 Antigen Recognition**: 銜接 TCR CDR1/2 接觸 MHC 螺旋壁與 CDR3 接觸溝槽胜肽的雙重辨識結構。
- **Ch 8 Development of Lymphocytes**: 深入胸腺正選擇中胸腺上皮細胞 MHC 如何挑選自身限制性 T 細胞。
- **Ch 9 T-cell-Mediated Immunity**: 對接成熟 CD8+ CTL 辨識靶細胞表面 pMHC-I 釋放穿孔素與顆粒酶殺傷靶細胞。
