# Universal Immunological Design Patterns (免疫系統八大通用架構模式)

本文件提煉自經典權威教科書《Janeway's Immunobiology》（第 9 版，Kenneth Murphy & Casey Weaver 著）。將貫穿全書 16 章與附錄的免疫學機制歸納為八大通用設計模式（Design Patterns），提供生物奧林匹亞競賽（IBO / 全國生奧選拔）、免疫學高階研究與臨床轉譯醫學的高階思維模型。

---

## Pattern 1: Multi-Tiered Clonal Selection & Tolerance (多級選殖選擇與自身耐受模式)
- **核心哲學**：在巨量隨機生成的抗原辨識庫中，透過嚴格的發育檢查點消除自體破壞者，並在周邊實施多層次動態抑制，兼顧防禦多樣性與組織安全性。
- **生化與細胞機制**：
  1. **中樞陰性選擇 (Central Negative Selection)**：
     - 胸腺皮質/髓質交界處，髓質上皮細胞(mTEC)依賴 AIRE 異位表現數千種周邊組織特異性抗原(TSA)。
     - 高親和力辨識自體胜肽-MHC的未成熟T細胞發生凋亡；骨髓中高親和力結合自體抗原的未成熟B細胞進行受體編輯(Receptor editing)或凋亡。
  2. **周邊主動耐受 (Peripheral Tolerance)**：
     - FoxP3+ CD25+ Treg 細胞利用高表現 CTLA-4 內吞並降解 APC 表面的 CD80/CD86 分子，切斷常規T細胞的共刺激信號。
     - 分泌免疫抑制性細胞因子 TGF-β、IL-10 與 IL-35，維持周邊組織長期的主動免疫靜默。
  3. **功能性失能與特權隔離 (Anergy & Privilege)**：
     - 缺乏信號二(共刺激)的T細胞進入生化惰性狀態(Anergy)；血-腦屏障、眼睛前房及睪丸透過高表現 FasL 與 TGF-β 建立免疫特權區。
- **競賽解題映射**：凡涉及自體免疫疾病機制(SLE、T1D、重症肌無力)或基因突變(AIRE突變致APECED、FoxP3突變致IPEX、Fas突變致ALPS)，必先調用本模式分析耐受漏洞。

---

## Pattern 2: Combinatorial & Somatic Hypermutation Diversification (組合式多樣性與體細胞突變引擎)
- **核心哲學**：利用有限的胚系基因組編碼無限的抗原辨識能力，並在免疫反應過程中利用定向隨機突變與自然選擇持續優化親和力。
- **生化與細胞機制**：
  1. **組合多樣性與接合多樣性 (V(D)J Recombination)**：
     - RAG1/RAG2 識別 12/23 RSS (重組信號序列) 並引入 DNA 雙股斷裂；Artemis 內切酶不對稱切割髮夾結構產生 P-核苷酸。
     - TdT (末端去氧核苷酸轉移酶) 隨機插入非模板編碼的 N-核苷酸，使 CDR3 區產生高達 $10^{11}$ 種以上的理論多樣性。
  2. **體細胞超突變與親和力成熟 (SHM & Affinity Maturation)**：
     - 活化誘導胞嘧啶去氨酶 (AID) 在胚生中心暗區將單股 DNA 的胞嘧啶去氨為尿嘧啶，觸發錯配修復(MMR)或鹼基切除修復(BER)。
     - 在 Ig 可變區引入高達 $10^{-3}$ 次/鹼基對/分裂世代的點突變；中心細胞在亮區經 FDC 展示之原生抗原與 Tfh 存活信號嚴格篩選，獲勝者親和力提升數百至數千倍。
- **競賽解題映射**：分析初次與二次抗體反應差異、共軛疫苗設計(聯動辨識)及 AID 基因缺陷導致高 IgM 症候群時必用。

---

## Pattern 3: Dual-Signal & Multi-Signal Activation Safeguard (雙信號與多信號活化保險機制)
- **核心哲學**：單一刺激不足以觸發不可逆的殺傷與發炎程序；唯有結合抗原特異性信號與危險評估信號，方能獲得免疫攻擊授權。
- **生化與細胞機制**：
  1. **T細胞啟動的三信號模型**：
     - **信號一 (抗原特異性)**：TCR 與 CD4/CD8 共同辨識 APC 表面的胜肽-MHC 複合物，激發 Lck 與 ZAP-70 磷酸化級聯。
     - **信號二 (共刺激安全性)**：APC 表面的 B7 (CD80/CD86) 結合 T 細胞表面的 CD28，提供 PI3K-Akt 與 Bcl-xL 存活信號，驅動 IL-2 與高親和力 IL-2R (CD25) 表現。
     - **信號三 (分化指導)**：微環境細胞因子(IL-12, IL-4, IL-6+TGF-β)誘導 T-bet, GATA3, RORγt 等主控轉錄因子表現，決定效應亞群定向。
  2. **B細胞雙重活化途徑**：
     - 胸腺相依(TD)抗原：BCR 結合抗原(信號一) + Tfh 表面 CD40L 結合 B 細胞 CD40 與分泌 IL-21 (信號二)。
     - 胸腺非相依(TI-1)抗原：BCR 結合抗原(信號一) + 高濃度病原 PAMP 活化 TLR (信號二)。
- **競賽解題映射**：解釋免疫耐受失能、抗排斥藥物(Abatacept 阻斷 B7)與檢查點阻斷療法(抗 CTLA-4)的生化邏輯。

---

## Pattern 4: Compartmentalized Microenvironmental Homing & Chemotaxis (隔室化微環境定向歸巢與趨化網絡)
- **核心哲學**：不同發育階段與功能的免疫細胞被精準導航至專屬解剖微環境，確保反應效率並防止破壞性全身發炎。
- **生化與細胞機制**：
  1. **初生T細胞淋巴結歸巢**：
     - 初生T細胞表面 L-selectin (CD62L) 與 HEV 上的 PNAd (CD34, GlyCAM-1) 結合進行滾動。
     - CCL19/CCL21 結合 CCR7 活化整合素 LFA-1 變構為高親和力構形，結合 ICAM-1 牢固黏附並穿過血管外遊。
  2. **S1P-S1PR1 循環計時器**：
     - 淋巴結內 S1P 濃度極低，血液與淋巴管內 S1P 濃度高。未活化 T 細胞重新上調 S1PR1 沿梯度離開淋巴結；活化後 CD69 表現使 S1PR1 內吞降解，滯留組織增殖。
  3. **組織特異性歸巢印記**：
     - 腸道歸巢：MLN 樹突細胞代謝維生素 A 為維生素 A 酸(RA)，印記 T/B 細胞高表現 **α4β7 整合素** (結合黏膜內皮 **MAdCAM-1**) 與 **CCR9** (結合上皮分泌之 **CCL25**)。
     - 皮膚歸巢：皮膚樹突細胞代謝維生素 D，誘導淋巴球表現 CLA (皮膚淋巴球抗原) 與 CCR4/CCR10 (結合 CCL17/CCL27)。
- **競賽解題映射**：解答淋巴球再循環、發炎性腸道疾病(Vedolizumab 抗 α4β7 單抗治療)與組織常駐記憶細胞(Trm)特性。

---

## Pattern 5: Molecular Switches & Phosphorylation Cascades (ITAM/ITIM分子開關與激酶級聯)
- **核心哲學**：透過酪胺酸磷酸化與去磷酸化的動態平衡，實施毫秒級的信號放大與負回饋自我約束。
- **生化與細胞機制**：
  1. **活化型 ITAM 基序 (Immunoreceptor Tyrosine-based Activation Motif)**：
     - 序列特徵：$Yxx[L/I]x_{6-8}Yxx[L/I]$。存在於 CD3 γ/δ/ε/ζ 鏈、Igα/Igβ (CD79a/b) 及 FcR γ 鏈。
     - 活化級聯：受體交聯後 Src 家族激酶(Lck, Fyn, Lyn)磷酸化雙酪胺酸，招募雙 SH2 結構域激酶(ZAP-70, Syk)。
     - 支架組裝：磷酸化 LAT 與 SLP-76 招募 PLC-γ1，水解 PIP2 為 IP3 (釋放胞質 Ca2+ 活化 Calcineurin-NFAT) 與 DAG (活化 PKC-θ-NF-κB 及 Ras-MAPK-AP-1)。
  2. **抑制型 ITIM/ITSM 基序 (Inhibition / Switch Motifs)**：
     - 序列特徵：$[I/V/L/S]xYxx[L/V]$。存在於 FcγRIIB, PD-1, CTLA-4, BTLA 及 KIR。
     - 負調控機制：磷酸化酪胺酸招募含 SH2 結構域的磷酸酶(SHP-1, SHP-2 或 SHIP)。
     - 阻斷級聯：SHP-1/2 去磷酸化 ZAP-70/Syk 及 CD3ζ；SHIP 去磷酸化 PIP3 為 PI(3,4)P2，阻斷 Akt 與 Btk 膜移位。
- **競賽解題映射**：推導受體活化信號路徑突變、抗體回饋抑制(FcγRIIB交聯)及 PD-1 檢查點抑制劑之生化機轉。

---

## Pattern 6: Functional Polarization & Mutual Antagonism (效應亞群極化與相互拮抗調控)
- **核心哲學**：面對多樣化病原體，免疫系統不實施折衷折中防禦，而是透過正向自我強化與相互抑制形成單向鎖定極化的免疫專科兵種。
- **生化與細胞機制**：
  1. **三大效應軸線之正回饋鎖定**：
     - **Type 1 (胞內病原/病毒)**：IL-12/IFN-γ $\implies$ STAT1/STAT4 $\implies$ **T-bet** 上調 $\implies$ 大量分泌 IFN-γ (進一步強化 T-bet 表現，正回饋鎖定)。
     - **Type 2 (蠕蟲/過敏原)**：IL-4 $\implies$ STAT6 $\implies$ **GATA3** 上調 $\implies$ 大量分泌 IL-4 (自體旁分泌強化 GATA3)。
     - **Type 3 (胞外菌/真菌)**：IL-6/TGF-β $\implies$ STAT3 $\implies$ **RORγt** 上調 $\implies$ 分泌 IL-17A/F 與 IL-22 (依賴 IL-23 維持存活)。
  2. **亞群間相互拮抗 (Cross-Inhibition)**：
     - Th1 分泌的 IFN-γ 強烈抑制 Th2 與 Th17 細胞的分化增殖。
     - Th2 分泌的 IL-4 與 IL-10 阻斷巨噬細胞分泌 IL-12 並抑制 Th1 極化。
     - 誘導型 Treg 分泌 TGF-β 與 IL-10，同時抑制 Th1、Th2 與 Th17 效應。
- **競賽解題映射**：分析麻風病雙極病理(結核樣型Th1 vs 瘤型Th2)、氣喘發作極化機制及自體免疫疾病轉換。

---

## Pattern 7: Multivalent Avidity & Complement Cascades (多價結合親合力與補體擴增級聯)
- **核心哲學**：單一分子親和力(Affinity)有限時，利用多價組裝產生幾何級數增強的總結合力(Avidity)，並觸發無催化劑流失的酶促連鎖放大。
- **生化與細胞機制**：
  1. **多聚體結構與親合力跳躍**：
     - 五聚體 IgM 具備 10 個抗原結合位點，儘管單個 Fab 親和力低，其多價結合總親合力(Avidity)提升高達 $10^3 \sim 10^5$ 倍。
     - 分子構形轉變：平面狀(Planar)游離 IgM 結合病原表面抗原後轉變為「訂書針狀」(Staple form)，暴露重鏈 Cμ3 結構域的 C1q 結合位點。
  2. **補體級聯之指數放大**：
     - 單個活化 C1s 可切割數百個 C4 與 C2，組裝成 C4b2a (C3轉化酶)。
     - 單個 C3 轉化酶每分鐘切割數千個 C3 為 C3b；替代途徑 C3bBb 形成強大的正回饋自催化擴增環(Amplification loop)。
     - C3b 密集共價沉積於病原表面形成調理吞噬(CR1)與引導 MAC (C5b-9) 膜打孔溶菌。
- **競賽解題映射**：解析 ABO 血型急性溶血反應、補體調節蛋白缺陷(PNH之CD59/CD55缺陷、血管神經性水腫之C1INH缺陷)及四聚體技術。

---

## Pattern 8: Evolutionary Arms Race & Antigenic Plasticity (宿主病原軍備競賽與抗原可塑性)
- **核心哲學**：病原體的突變速度遠快於宿主基因體進化；宿主以高度多態性的群體多樣性抵抗病原體的精準顛覆。
- **生化與細胞機制**：
  1. **宿主群體多態性作為物種防火牆**：
     - 人類 MHC (HLA) 具有極端的群體多型性(Polymorphism)與共顯性表現(Co-dominant expression)，沒有任何單一突變病原體能同時逃逸全人類族群的 MHC 呈遞。
  2. **病原體的對應破壞策略**：
     - **突變表位逃逸**：流感病毒 HA 表面點突變(抗原漂移)；HIV-1 逆轉錄酶高錯配率產生準種(Quasispecies)。
     - **表觀基因轉換**：錐蟲超過 1000 個 VSG 基因定期切換主導表現型，耗竭宿主抗體庫。
     - **直接癱瘓呈現網絡**：HSV ICP47 阻斷 TAP 轉運；CMV US11 將 MHC-I 逆向轉位送入蛋白酶體降解；EBV LMP-1 模擬 CD40 訊息引發淋巴瘤。
- **競賽解題映射**：解構新興傳染病大流行演化、疫苗脫靶抗藥性、柏林病患 CCR5-Δ32 骨髓移植治癒 HIV 之演化生態學本質。
