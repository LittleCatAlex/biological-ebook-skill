# Chapter 7: Lymphocyte Receptor Signaling (淋巴球受體訊息傳遞)

> **Part**: Part III — The Development of Mature Lymphocyte Receptor Repertoires (成熟淋巴球受體組庫的發育)

## Core Idea
抗原受體（TCR/BCR）自身無內在催化活性，透過非共價偶聯帶有 ITAM 基序的信號轉導模組（CD3 複合物或 Igα/Igβ）發起磷酸化級聯：Src 家族激酶（Lck/Blk）磷酸化 ITAM 招募串聯 SH2 結構域之 Syk 家族激酶（ZAP-70/Syk），進而磷酸化 LAT/SLP-76 支架裝配活化 PLC-γ，向核內同步分流釋放 NFAT（鈣離子）、NF-κB（PKC-θ/Carma1）與 AP-1（Ras-MAPK）三大命運決定轉錄因子，並由 CD28 與 CTLA-4/PD-1 檢查點精準微調活化閾值。

## Sections Outline
- **7.1 General principles of transmembrane signaling (跨膜受體信號轉導原則：蛋白質激酶、磷酸酶與接頭蛋白結構域)**
- **7.2 Antigen receptor signaling and lymphocyte activation (TCR 與 BCR 信號複合體：ITAM 磷酸化、ZAP-70/Syk 與四大下游分支)**
- **7.3 Co-stimulatory and inhibitory receptors (共刺激受體 (CD28) 與抑制性檢查點受體 (CTLA-4, PD-1) 之代謝微調)**

## Frameworks Introduced
### TCR Proximal Signalosome & Four Downstream Branches (TCR 近端信號體組裝與四大分流分支模型)
> **目的**：完整解析抗原辨識如何自質膜微小聚集放大為全域基因轉錄爆發

1. **受體聚集與初始 ITAM 磷酸化**：
   - TCR 結合 pMHC，共受體 (CD4/CD8) 將結合於胞質尾部的 Src 家族酪胺酸激酶 **Lck** 帶至 TCR-CD3 複合體旁。
   - Lck 磷酸化 CD3 (γε, δε) 與 ζ:ζ 同源二聚體胞質尾部之 **ITAM 基序**（每個 ITAM 含有兩個保守 Tyr，磷酸化形成雙磷酸 Tyr 標記）。
2. **ZAP-70 招募與核心支架成核**：
   - **ZAP-70** 激酶藉由其雙重串聯 **SH2 結構域**，高親和力鎖定結合於磷酸化之 ζ 鏈 ITAM。
   - Lck 磷酸化活化 ZAP-70；活化的 ZAP-70 迅速磷酸化質膜錨定支架蛋白 **LAT** 與胞質支架蛋白 **SLP-76**。
   - 轉接蛋白 Gads 橋接 LAT 與 SLP-76，組裝成巨大多蛋白「**LAT 信號小體 (LAT signalosome)**」，招募並活化 **PLC-γ1**（受 Itk 激酶磷酸化活化）。
3. **四大下游效應分支全面分流**：
   - **分支 1 (NFAT 轉錄因子活化 / 鈣信號軸)**：
     - PLC-γ1 水解 $PI(4,5)P_2$ 生成 **$IP_3$** $\to$ 開啟內質網 $IP_3R$ 鈣通道釋放 $Ca^{2+}$ $\to$ 內質網鈣耗竭促使 STIM1 聚集並開啟質膜 **CRAC 通道 (ORAI1)**，引發持續強烈胞外鈣內流 (SOCE)。
     - 高胞質 $Ca^{2+}$ 結合鈣調蛋白 (Calmodulin) $\to$ 活化絲/蘇胺酸磷酸酶 **鈣調磷酸酶 (Calcineurin)** $\to$ Calcineurin 脫去 **NFAT** 上的多重抑制性磷酸基，暴露出 NLS，NFAT 轉位入核驅動 **IL-2** 轉錄。
   - **分支 2 (NF-κB 轉錄因子活化 / PKC-θ 軸)**：
     - PLC-γ1 生成的另一產物 **DAG** 結合質膜 **PKC-θ** 並使其活化 $\to$ 活化 CARMA1-BCL10-MALT1 (CBM 複合體) $\to$ 招募並活化 **IKK 複合體** (IKKα/β/γ)。
     - IKK 磷酸化 **IκB**，誘導 IκB 發生 K48 泛素化被蛋白酶體降解 $\to$ 釋放 **NF-κB (p50/p65)** 二聚體迅速入核。
   - **分支 3 (AP-1 轉錄因子活化 / Ras-MAPK 軸)**：
     - DAG 與 LAT 招募 Ras-GEF (RasGRP) $\to$ 活化膜小 G 蛋白 **Ras** $\to$ 啟動 Raf-MEK-ERK 激酶級聯 $\to$ ERK 磷酸化 Elk-1 誘導 **c-Fos** 表現；同時 JNK 激酶磷酸化 **c-Jun** $\to$ c-Fos 與 c-Jun 組裝成異二聚體 **AP-1** 入核。
   - **分支 4 (細胞骨架重組與整合素黏附)**：
     - SLP-76 招募 Vav (Rho-GEF)，活化 Cdc42 與 Rac1，驅動肌動蛋白微絲重組，促使微絲向免疫突觸 (IS) 極化，並誘導整合素 LFA-1 構型展開提升黏附力。

### Co-stimulation vs Coinhibition Dialectic Balance (共刺激 CD28 與免疫檢查點 CTLA-4/PD-1 辯證對抗機制)
> **目的**：解析 T 細胞活化增殖油門與免疫耐受剎車的分子競合力學

1. **正向共刺激油門 (CD28)**：
   - CD28 組成型表現於 T 細胞表面，結合 APC 表面的 **B7.1 (CD80)** 或 **B7.2 (CD86)**。
   - CD28 胞質尾部被 Src 激酶磷酸化，招募並活化 **PI3K** $\to$ 生成 $PIP_3$ $\to$ 活化 **Akt** $\to$ 活化 mTORC1、促進有氧糖解代謝重編程、上調抗凋亡蛋白 **Bcl-xL** 並極大化 IL-2 轉錄。
2. **早期競爭性剎車 (CTLA-4 / CD152)**：
   - T 細胞活化後數小時內自胞內囊泡上調轉位至細胞表面；Treg 細胞則組成型高表現 CTLA-4。
   - CTLA-4 與 CD28 競爭結合相同的配體（B7-1/B7-2），但 CTLA-4 對 B7 分子的親和力高達 CD28 的 **20–100 倍**，能完全將 CD28 排擠開。
   - 物理阻斷 + 反向內吞：CTLA-4 二聚體能跨膜「抓取」APC 表面之 B7 配體並經反向胞吞 (Trans-endocytosis) 將 B7 分子直接拔除降解，徹底剝奪 APC 的共刺激能力。
3. **晚期周邊組織剎車 (PD-1 / CD279)**：
   - 主要表現於長期慢性活化之效應 T 細胞表面，結合發炎或腫瘤組織表面的 **PD-L1 (B7-H1)** 或 **PD-L2**。
   - 胞內抑制機制：PD-1 胞質尾部帶有 **ITIM** 與 **ITSM** 基序，被磷酸化後專一性招募酪胺酸磷酸酶 **SHP-2**。
   - SHP-2 直接去磷酸化 TCR 近端之 CD3ζ、ZAP-70 及 CD28 胞質微區，在源頭掐滅活化信號，誘導 T 細胞進入「功能耗竭態 (Exhaustion)」。

## Key Concepts & Vocabulary
- **ITAM (免疫受體酪胺酸活化基序)**：序列為 $Yxx[L/I]x_{6-8}Yxx[L/I]$ 的保守基序，存在於 CD3 鏈、Igα/Igβ 及 Fc 受體胞質尾部；兩顆 Tyr 被 Src 激酶磷酸化後專一招募具雙 SH2 結構域之 Syk 家族激酶。
- **ITIM (免疫受體酪胺酸抑制基序)**：序列為 $[I/V/L/S]xYxx[L/V]$ 的抑制基序，存在於 CTLA-4、PD-1、KIR 受體尾部；磷酸化後招募蛋白質酪胺酸磷酸酶 SHP-1/SHP-2 或脂質磷酸酶 SHIP，削弱活化信號。
- **Lck & Fyn**：T 淋巴球中核心 Src 家族非受體酪胺酸激酶，經 N 端豆蔻醯化錨定於質膜內小葉，受 CD4/CD8 募集並受 Csk 激酶（抑制性 Tyr505 磷酸化）與 CD45（活化性去磷酸化）嚴密調控。
- **ZAP-70 (70 kDa ζ-鏈關聯蛋白激酶)**：T 細胞特異之 Syk 家族激酶，具備兩個串聯 SH2 結構域，特異咬合雙磷酸化之 CD3ζ ITAM 並磷酸化下游 LAT 支架。
- **LAT (T 細胞活化連接子)**：膜整合性支架蛋白，被 ZAP-70 多位點磷酸化後招募 Grb2、Gads、PLC-γ1 與 SOS 組裝成巨分子信號小體，為 T 細胞活化的總路由器。
- **Calcineurin (鈣調磷酸酶)**：依賴鈣離子與鈣調蛋白的絲/蘇胺酸蛋白質磷酸酶，脫去 NFAT 抑制性磷酸基促使其入核；為免疫抑制劑環孢素 (Cyclosporine A) 與他克莫司 (FK506) 的直接分子標靶。
- **NFAT (活化 T 細胞核因子)**：高度磷酸化的胞質轉錄因子，經 Calcineurin 去磷酸化後暴露 NLS 迅速轉位入核，與 AP-1 協同活化 *IL-2* 基因轉錄。
- **Immunological Synapse (免疫突觸, IS / SMAC)**：T 細胞與 APC 緊密接觸形成的同心圓特化結構：中央 (c-SMAC) 富集 TCR-CD3 與 CD28；周圍 (p-SMAC) 富集 LFA-1 鎖定 ICAM-1 提供力學封閉；外圍 (d-SMAC) 富集巨大外被分子 CD45。
- **Cyclosporin A & Tacrolimus (環孢素 A 與他克莫司)**：臨床器官移植抗排斥一線免疫抑制劑；分別結合胞質親合素 (Cyclophilin / FKBP12) 形成藥物-伴侶複合體，強烈阻斷 Calcineurin 活性，阻斷 NFAT 活化與 IL-2 合成。
- **Checkpoint Inhibitors (免疫檢查點抑制劑)**：如抗 CTLA-4 抗體 (Ipilimumab) 與抗 PD-1 抗體 (Nivolumab, Pembrolizumab)，阻斷抑制性受體與配體結合，重新釋放耗竭 T 細胞殺傷腫瘤之免疫功能。

## Mental Models & Analogies
### Think of ITAMs as Dual-Pin Electrical Wall Sockets (將 ITAM 視為雙孔電源插座)
單插一孔（單磷酸化）不通電；Lck 同時給兩個孔插上高能磷酸插頭（雙磷酸化），ZAP-70 的雙 SH2 雙腳插頭才能嚴絲合縫插進去通電活化。

### Think of LAT as a Master Multi-Plug Power Strip (將 LAT 支架蛋白視為中央多孔延長線排插)
ZAP-70 點亮延長線總開關（多位點磷酸化），水泵線（PLC-γ1 鈣信號）、電風扇線（PKC-θ 促炎信號）與照明燈線（Ras-MAPK 增殖信號）全部同時插在 LAT 上高速運轉。

### Think of Calcineurin and NFAT as an Escort Removing a Straitjacket (將鈣調磷酸酶與 NFAT 視為解開束縛衣的特勤護送員)
NFAT 身上捆滿了磷酸基束縛衣，被死死困在細胞質牢房；高鈣離子喚醒解鎖專家（Calcineurin），一剪刀剪斷所有磷酸繩索，自由的 NFAT 拔腿衝入細胞核金庫簽署 IL-2 釋放令。

## Common Pitfalls & Anti-Patterns
- ❌ **常見盲點**：混淆 ZAP-70 與 Syk 的細胞分佈特異性：**ZAP-70 專一性表現於 T 細胞與 NK 細胞**（受 CD3ζ 磷酸化招募）；而 **Syk 則主要表現於 B 細胞**（受 BCR 之 Igα/Igβ 磷酸化招募）與肥大細胞，兩者在不同細胞中擔任同等位置的催化接力角色。
  - ✅ **正確觀念**：在 B 與 T 細胞信號轉導路徑比較題中混淆激酶身分。
- ❌ **常見盲點**：誤以為環孢素 A (CsA) 與雷帕黴素 (Rapamycin) 的分子標靶相同：兩者均為強力免疫抑制劑且均結合細胞質親免素，但 **CsA 抑制的是 Calcineurin 磷酸酶**（阻斷 NFAT 入核與 IL-2 轉錄）；而 **Rapamycin (Sirolimus) 抑制的是 mTORC1 激酶**（阻斷下游 IL-2 受體驅動的細胞週期推進），兩者作用階段一早一晚截然不同。
  - ✅ **正確觀念**：在藥理學免疫抑制靶標對比中混淆 Calcineurin 與 mTOR。
- ❌ **常見盲點**：將 CTLA-4 與 PD-1 的作用位點與時間混為一談：**CTLA-4 主要在「免疫初次啟動階段」、於「次級淋巴器官 (淋巴結)」中抑制初始 T 細胞的過度活化**（主要拮抗 CD28 共刺激）；而 **PD-1 主要在「免疫效應晚期」、於「周邊外周發炎或腫瘤組織」中抑制效應 T 細胞**（直接去磷酸化 TCR 近端信號），兩者時空分工截然不同。
  - ✅ **正確觀念**：在腫瘤免疫檢查點抑制劑臨床應用機轉中混淆解剖與時相定位。

## Reference Tables
| 信號轉導成分 | T 淋巴球 (TCR 信號體系) | B 淋巴球 (BCR 信號體系) | 核心生化功能與對接結構域 |
| :--- | :--- | :--- | :--- |
| **抗原辨識複合體** | **TCR α:β 異二聚體** (單價) | **膜表面抗體 mIgM / mIgD** (雙價) | 特異性結合抗原決定基 (TCR 需 pMHC，BCR 辨識天然抗原) |
| **信號轉導模組 (帶 ITAM)** | **CD3 複合體 (γε, δε) 與 ζ:ζ** (共 10 個 ITAMs) | **Igα (CD79a) 與 Igβ (CD79b)** 異二聚體 (共 2 個 ITAMs) | 胞質尾部提供雙磷酸化 ITAM 錨定位點 |
| **起始 Src 家族激酶** | **Lck** (結合 CD4/CD8), Fyn | **Blk, Fyn, Lyn** | 磷酸化受體尾部 ITAM 基序與開關激活 |
| **近端 Syk 家族激酶** | **ZAP-70** (雙 SH2 結構域結合 ζ 鏈) | **Syk** (結合 Igα/Igβ 磷酸化 ITAM) | 磷酸化核心膜/胞質支架蛋白 |
| **核心轉接支架蛋白** | **LAT** (跨膜) + **SLP-76** (胞質) | **BLNK (SLP-65)** (胞質支架蛋白) | 招募 Gads/Grb2、Vav 與 PLC-γ 組裝多蛋白信號複合體 |
| **PLC 磷脂酶亞型** | **PLC-γ1** (受 Itk 激酶活化) | **PLC-γ2** (受 Btk 激酶活化) | 水解 $PI(4,5)P_2$ 生成第二信使 **$IP_3$** (鈣信號) 與 **DAG** (PKC) |
| **正向共刺激受體** | **CD28** (結合 APC 表面 CD80/CD86) | **CD19-CD21(CR2)-CD81 複合體** (結合 C3dg) | 活化 PI3K-Akt 存活途徑，將活化抗原閾值降低 100–1000 倍 |
| **負向抑制檢查點** | **CTLA-4** (高親和力奪取 B7), **PD-1** (招募 SHP-2) | **CD22** (招募 SHP-1), **FcγRIIB** (招募 SHIP 水解 $PIP_3$) | 阻止自體免疫過度活化，終止免疫反應 |

## Worked Example
**臨床免疫藥理案例推導：器官移植排斥中「鈣調磷酸酶抑制劑」與「mTOR 抑制劑」之雙重阻斷生化路徑**

考慮腎臟移植術後抗急性細胞性排斥 (ACR) 之免疫抑制藥物聯用方案：
1. **上游阻斷：環孢素 A (Cyclosporin A, CsA) 或他克莫司 (FK506 / Tacrolimus)**：
   - **生化靶標**：CsA 結合胞質親環素 (Cyclophilin)，FK506 結合 FKBP12。
   - 藥物-伴侶二元複合體專一性嵌入 **鈣調磷酸酶 (Calcineurin)** 的催化中心與調節結構域結合槽，完全阻斷其磷酸酶活性。
   - **效應**：即使供體移植物同種異體抗原刺激了受者 T 細胞受體，活化的 PLC-γ1 引發鈣內流，但由於 Calcineurin 被死鎖，**NFAT 無法被去磷酸化**。
   - NFAT 滯留胞質，無法入核活化 *IL-2* 基因啟動子，**T 細胞第一信號活化與細胞激素轉錄合成完全停擺 (Signal 1 Blockade)**。
2. **下游阻斷：雷帕黴素 (Rapamycin / Sirolimus)**：
   - **生化靶標**：Rapamycin 同樣結合胞質 **FKBP12**，但形成的 Rapamycin-FKBP12 複合體**完全不抑制 Calcineurin**，而是特異性結合併強烈抑制下游絲/蘇胺酸激酶 **mTORC1 (哺乳動物雷帕黴素靶蛋白複合體 1)**。
   - **效應**：即使有微量逃逸的 IL-2 結合了 T 細胞表面高親和力 IL-2 受體 (IL-2R, CD25)，原本應由 IL-2R 下游 PI3K-Akt 活化的 mTORC1 被雷帕黴素截斷。
   - S6K1 與 4E-BP1 磷酸化受阻，核醣體轉譯全面凍結，CDK2-Cyclin E 無法累積，T 細胞徹底阻滯於 **G1 期向 S 期轉換點**，無法進行克隆擴增 (Signal 3 Blockade)。
3. **結論與臨床協同優勢**：CsA 封殺了 IL-2 的「源頭生產（轉錄）」，Rapamycin 掐死了殘留 IL-2 的「下游響應（細胞週期擴增）」，兩者機制互補產生指數級協同抗排斥效能，開創了現代實體器官移植的生存奇蹟。

## Key Takeaways
1. TCR 與 BCR 自身無催化結構域，依賴非共價偶聯的 CD3 與 Igα/Igβ 胞質尾部 ITAM 基序啟動跨膜信號轉導。
2. Src 家族激酶（Lck/Lyn）磷酸化 ITAM 形成雙磷酸標籤，招募並激活串聯 SH2 激酶 ZAP-70/Syk。
3. ZAP-70 磷酸化 LAT/SLP-76 支架裝配 PLC-γ，下游分流為 NFAT（鈣信號）、NF-κB（PKC-θ 途徑）與 AP-1（Ras-MAPK 途徑）三大轉錄分支。
4. CD28 結合 B7 提供核心共刺激信號並啟動 PI3K-Akt 途徑，CTLA-4 以超高親和力爭奪 B7 踩下早期剎車，PD-1 藉由 SHP-2 磷酸酶終止周邊效應信號。
5. 免疫抑制劑環孢素與他克莫司專一抑制 Calcineurin 阻斷 NFAT 入核，雷帕黴素抑制 mTORC1 阻斷週期推進，兩者為器官移植抗排斥基石。

## Connects To
- **Ch 4 Antigen Recognition**: 銜接 TCR 與 BCR 抗原識別結構域與跨膜傳導組件的物理裝配。
- **Ch 8 Development of Lymphocytes**: 探討未成熟淋巴球 Pre-BCR 與 Pre-TCR 信號如何推動細胞存活並關閉重排。
- **Ch 16 Manipulation of Immune Response**: 深入免疫檢查點抗體（抗 CTLA-4 與抗 PD-1）在腫瘤免疫治療中的逆轉耗竭機制。
