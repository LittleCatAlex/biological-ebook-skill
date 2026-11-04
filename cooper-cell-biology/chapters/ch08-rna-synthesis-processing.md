# Chapter 8: RNA Synthesis and Processing (RNA合成與修飾加工)

> **Part**: Part II — The Flow of Genetic Information (遺傳訊息的流動)

## Core Idea
轉錄是以 DNA 為模板精準合成 RNA 的分子過程：原核生物依賴單一核心酶結合 σ 因子辨識啟動子；真核生物則演化出 Pol I、II、III 分工體系，Pol II 藉由 GTFs 組裝預起始複合體與 CTD 磷酸化密碼驅動轉錄，並協同偶聯 5' 加帽、剪接體兩步轉酯剪接與 3' 聚腺苷酸化成熟修飾。

## Sections Outline
- **8.1 Transcription in Bacteria (細菌的轉錄機制與終止方式)**
- **8.2 Eukaryotic RNA Polymerases and General Transcription Factors (真核 RNA 聚合酶與基礎轉錄因子複合體)**
- **8.3 RNA Processing and Turnover (真核 RNA 修飾加工、剪接體催化與 mRNA 代謝降解)**

## Frameworks Introduced
### Pol II Pre-Initiation Complex Assembly Sequence (Pol II 預起始複合體階層組裝工作流)
- **When to use**: 分析真核核心啟動子辨識、轉錄起始至延伸的分子拓撲順序
- **How to apply**:
1. TFIID 結合：TFIID 複合體中的 TBP (TATA-binding protein) 結合核心啟動子之 TATA box (約 -25 至 -30 bp)，使 DNA 局部彎曲約 80 度；TAFs 辨識 Inr (起始子) 與 DPE (下游啟動子元件)。
2. TFIIA 與 TFIIB 募集：TFIIA 穩定 TBP-DNA 結合；TFIIB 結合 TBP 並精準橋接測量轉錄起始點 (+1 位點)，同時招募 RNA Pol II。
3. Pol II-TFIIF 複合體進駐：TFIIF 引導 RNA Pol II 進入啟動子中心，防止非特異性 DNA 結合。
4. TFIIE 與 TFIIH 鎖定組裝：TFIIE 招募具多功能的十聚體 TFIIH。
5. 啟動子熔解與起始清除 (Promoter Clearance)：TFIIH 的 XPB/XPD 解旋酶亞基水解 ATP 解開 DNA 雙螺旋形成轉錄泡 (Transcription bubble)；TFIIH 的 CDK7 激酶亞基磷酸化 Pol II CTD 七肽重複序列之 **Serine 5 (Ser5)**，促使 Pol II 掙脫啟動子開跑轉錄延伸。

### CTD Phosphorylation Code & Cotranscriptional Coupling (CTD 磷酸化密碼與轉錄協同修飾偶聯架構)
- **When to use**: 追蹤 RNA Pol II 羧基末端結構域 (CTD, $Y_1S_2P_3T_4S_5P_6S_7$ 共有 52 次重複) 動態化學修飾與下游加工機器的時空偶聯
- **How to apply**:
1. 起始階段 (Ser5 磷酸化)：CDK7 磷酸化 Ser5，CTD 專一性結合 5' 端加帽酵素複合體 (Capping enzyme)，在新生轉錄本長度達 20-30 nt 時立即進行 5' 逆向 $m^7G$ 加帽。
2. 延伸階段 (Ser2 磷酸化)：P-TEFb (CDK9) 磷酸化 Ser2，形成 Ser2P/Ser5P 雙重標記，招募剪接體 snRNPs 複合體，對新合成出的外顯子/內含子邊界進行協同共轉錄剪接。
3. 終止階段 (Ser2 單一高磷酸化)：Ser5 磷酸基被去磷酸化移除，高密度 Ser2P 標記專一性招募聚腺苷酸化因子 CPSF 與 CstF，結合 AAUAAA 信號切割 RNA 並添加 Poly(A) 尾。

### Spliceosome Two-Step Transesterification Mechanism (剪接體兩步轉酯生化催化模型)
- **When to use**: 精確解析 snRNPs 協同裝配與內含子套索切除的化學反應歷程
- **How to apply**:
1. 位點辨識：U1 snRNP 鹼基互補結合 5' 剪接位點 (共有序列 5'-AG|GURAGU-3')；剪接因子 U2AF 辨識 3' 剪接位點 AG 與富含嘧啶區段 (Polypyrimidine tract)，招募 U2 snRNP 互補結合分支點 (Branch point)，使分支位點之 **腺苷酸殘基 (Branch A)** 突起 (Bulging A)。
2. 三聯體進駐：U4/U6-U5 三核糖核蛋白複合體加入組裝，形成完整剪接體。
3. 構型重排與活化：ATP 水解驅動 U1 與 U4 解離，U6 釋放並與 U2 形成精確催化核心，催化中心本質為 U6/U2 snRNA 構成的核酶 (Ribozyme) 活性中心。
4. 第一步轉酯反應：分支位點 A 的 **2'-OH** 作為親核基團，攻擊 5' 剪接位點鳥嘌呤的 5' 磷酸二酯鍵，切斷 5' 外顯子並生成帶有套索形狀的內含子-3'外顯子中間體 (Lariat intermediate)。
5. 第二步轉酯反應：游離的 5' 外顯子露出之 **3'-OH** 作為親核基團，攻擊 3' 剪接位點的磷酸二酯鍵，將兩個外顯子以正常 $3'-5'$ 磷酸二酯鍵共價拼接，同時完整釋放套索狀內含子 (Lariat intron)，後續由去分支酶 (Debranching enzyme) 線性化降解。

## Key Concepts
- **Sigma Factor (σ 因子)**: 原核生物轉錄起始專一性因子，與 RNA 聚合酶核心酶結合形成全酶，特異辨識啟動子 -35 (TTGACA) 與 -10 (Pribnow box TATAAT) 共有序列。
- **RNA Polymerase I, II, III (真核三種 RNA 聚合酶)**: Pol I 轉錄 28S, 18S, 5.8S rRNA (核仁)；Pol II 轉錄 mRNA, snRNA, lncRNA, miRNA；Pol III 轉錄 tRNA, 5S rRNA, U6 snRNA。
- **TATA-Binding Protein (TBP, TATA 結合蛋白)**: 普遍存在於所有三種真核 RNA 聚合酶轉錄體系中的通用轉錄因子，特異插入 DNA 小溝使其劇烈彎曲以標記起始位點。
- **7-Methylguanosine Cap (m7G 帽子)**: 成熟真核 mRNA 5' 端特有結構，透過特殊的 $5'-5'$ 三磷酸鍵連接於第一個核苷酸，提供核酸外切酶防護並作為 eIF4E 轉譯起始辨識點。
- **Polyadenylation (聚腺苷酸化)**: CPSF 辨識 AAUAAA 保守信號切割 pre-mRNA 3' 端後，由聚腺苷酸聚合酶 (PAP) 以非模板依賴方式添加 200-250 個 A 鹼基形成 Poly(A) 尾。
- **snRNP (小核核糖核蛋白顆粒)**: 由 snRNA (U1, U2, U4, U5, U6) 與核心 Sm 蛋白質組裝而成的顆粒複合體，為真核剪接體的基本催化與辨識單位。
- **Exon Skipping ASO Therapy (外顯子跳躍反義寡核苷酸療法)**: 利用人工合成化學修飾反義寡核苷酸遮蔽 pre-mRNA 特殊剪接位點，引導剪接體跳過含突變的外顯子，恢復破壞的轉譯讀框（如治癒 DMD 之 Eteplirsen）。
- **Nonsense-Mediated Decay (NMD, 無義介導降解)**: mRNA 品質監控機制：當核醣體在前驅外顯子接合複合體 (EJC) 上游遇到提早終止密碼子 (PTC) 停滯時，招募 UPF 蛋白引發該缺陷 mRNA 快速去帽降解。
- **P-bodies (處理小體)**: 細胞質中富含 mRNA 去帽酶 (Dcp1/2)、5'$\to$3' 核酸外切酶 (Xrn1) 與 miRNA-RISC 的無膜液滴微結構域，為 mRNA 暫存或降解中心。
- **Intron Lariat (內含子套索)**: 剪接過程中分支位點腺苷酸 2'-OH 與 5' 剪接位點鳥苷酸形成特殊的 $2'-5'$ 磷酸二酯鍵所構成的環狀套索狀核酸結構。

## Mental Models
- **Think of the CTD as a Conductor's Baton with Switched Flags (將 Pol II CTD 視為切換信號旗的指揮棒)**: Ser5 磷酸化如同升起綠旗（加帽工班進駐），Ser2 磷酸化如同升起藍旗（剪接工班與 Poly(A) 尾接力隊伍依序掛載）。
- **Think of the Spliceosome as an Origami Cut-and-Paste Artist (將剪接體視為摺紙剪貼大師)**: 利用 U2 與 U6 牽引將數千鹼基外的分支 A 精準拉至 5' 切口身邊，進行第一刀轉酯，再旋即將兩段外顯子平整對齊拼貼第二刀。
- **Think of NMD as Factory Quality Control Scrapping Defective Blueprints (將 NMD 視為品管銷毀殘缺藍圖)**: 如果在產品裝配中途（EJC 下游標記未清除前）就提前讀到停工紅燈（PTC），品管員 UPF 立即將整張藍圖投入碎紙機銷毀，避免生產致病毒性殘次截短蛋白。

## Anti-patterns
- **混淆真核三種 RNA 聚合酶對 α-鵝膏蕈鹼 (α-Amanitin) 的敏感性：Pol II 對極低濃度 α-鵝膏蕈鹼極度敏感（被完全抑制）；Pol III 僅對高濃度敏感；Pol I 則完全不敏感（抗性）。**: 在生奧毒理學與轉錄生化實驗題中混淆聚合酶身分。
- **誤以為真核 mRNA 5' 端的加帽反應是在轉錄完全終止後才發生：加帽反應是高度協同轉錄的事件 (Cotranscriptional)，早在新生 RNA 鏈僅伸長 20-30 個核苷酸時，5' 端一露頭就立即完成加帽。**: 在 RNA 成熟時間線問題中錯排反應順序。
- **忽視 5S rRNA 的轉錄來源：雖然 28S、18S、5.8S rRNA 均在核仁中由 Pol I 轉錄為 45S 單一前驅物後切割生成，但 **5S rRNA 係在核質中由 RNA Pol III 獨立轉錄**，再運入核仁組裝核醣體大單元。**: 在核醣體生物合成考題中誤將 5S rRNA 歸入 Pol I 產物。

## Reference Tables
| RNA 類型 | 負責轉錄之聚合酶 | 啟動子與轉錄因子特徵 | 關鍵後轉錄修飾加工 | 主要細胞定位與生理功能 |
| :--- | :--- | :--- | :--- | :--- |
| **mRNA** | **RNA Pol II** | TATA box, Inr, DPE; TFIID, TFIIB, TFIIH | 5' $m^7G$ 帽子, 選擇性剪接, 3' Poly(A) 尾 | 運出核孔至細胞質，作為蛋白質轉譯模板 |
| **pre-rRNA (45S)** | **RNA Pol I** | 核心啟動子 + 上游控制元件 UCE; SL1, UBF | 28S, 18S, 5.8S 切割裂解, snoRNA 引導 2'-O-甲基化 | 核仁 (Nucleolus)；組裝核醣體大小次單元核心催化骨架 |
| **tRNA** | **RNA Pol III** | 內部啟動子 (Box A, Box B); TFIIIB, TFIIIC | 5' 剪切 (RNase P), 3' CCA 裝載, 鹼基修飾 (I, $\Psi$, D) | 細胞質；轉運對應胺基酸至核醣體 A 位點 |
| **5S rRNA** | **RNA Pol III** | 內部啟動子 (Box A, Box C); TFIIIA, TFIIIB, TFIIIC | 無內含子剪接，末端微修飾加工 | 核仁與細胞質；組裝於核醣體 60S 大單元 |
| **snRNA (U1, U2, U4, U5)** | **RNA Pol II** | 類似 mRNA 啟動子；富含 PSE 元件 | 5' 三甲基鳥苷帽 ($m_3G$), 與 Sm 蛋白組裝 | 細胞核；剪接體核心催化構件 |
| **U6 snRNA** | **RNA Pol III** | 上游啟動子 (含 TATA-like 位點); TFIIIB | 3' 末端磷酸環化修飾，無 $m_3G$ 帽 | 細胞核；剪接體活性催化中心核酶 |

## Worked Example
**分子醫學與剪接病理題：杜興氏肌肉營養不良症 (DMD) 之反義寡核苷酸 (ASO) 外顯子跳躍治療推導**

1. **遺傳病理事實**：
   - 肌縮蛋白 (*DMD*) 基因位於 X 染色體，是人類最長基因（含 79 個外顯子）。
   - 某患童第 50 號外顯子發生單一缺失（$\Delta$Exon 50）。
   - 第 49 號外顯子結尾密碼子相位為讀框位點 1（餘 1 鹼基）；第 51 號外顯子開頭需 2 鹼基補全密碼子。
   - 缺失第 50 號外顯子後，第 49 號直接與第 51 號外顯子接合，導致**轉譯閱讀框移碼 (Frameshift)**，在下游第 52 號外顯子提早產生無義終止密碼子 (PTC)，觸發 NMD 或生成不穩定無功能截短蛋白，臨床表現為嚴重的杜興氏型。
2. **外顯子跳躍 (Exon Skipping) 設計思路**：
   - 若能人為促使剪接體將 **第 51 號外顯子連同跳過**（同時跳過 Exon 50 與 Exon 51）。
   - 檢驗閱讀框：計算 Exon 49 銜接 Exon 52 的鹼基相位。
   - 計算證實 Exon 49 尾端與 Exon 52 開端拼接時，鹼基總數恰為 3 的倍數，**完整恢復了蛋白質下游正常閱讀框 (In-frame)**！
3. **治療策略實現 (Eteplirsen)**：
   - 設計一條針對第 51 號外顯子內部剪接增強子序列 (ESE) 的化學修飾反義嗎啉基寡核苷酸 (PMO)。
   - ASO 與 pre-mRNA 互補結合阻斷 U2AF 與 snRNP 進駐，迫使剪接體將 Exon 49 直接拼接至 Exon 52。
   - 結果產出略微截短但保留關鍵肌纖維膜結合域之部分功能性肌縮蛋白，成功將重度致命的 DMD 降級為症狀輕微之貝克型肌肉營養不良症 (BMD)。

## Key Takeaways
1. 原核轉錄依賴核心酶結合 σ 因子辨識啟動子，而真核系統演化出 Pol I、II、III 分工負責不同 RNA 階層。
2. Pol II 轉錄依賴 TFIID、TFIIB 與 TFIIH 依序組裝預起始複合體，TFIIH 磷酸化 CTD Ser5 清除啟動子開跑轉錄。
3. CTD 磷酸化密碼在時間和空間上精準偶聯 5' 加帽（Ser5P）、共轉錄剪接（Ser2P/Ser5P）與 3' 聚腺苷酸化（Ser2P）。
4. 剪接體由五種 snRNPs 組裝成核酶活性中心，歷經分支 A 2'-OH 與 5' 切口的第一步轉酯，以及外顯子 3'-OH 攻擊的第二步轉酯，釋放內含子套索。
5. NMD 品質監控機制精準銷毀帶有提早終止密碼子 (PTC) 的缺陷 mRNA，而外顯子跳躍 ASO 技術已成為單基因遺傳病精準醫療典範。

## Connects To
- **Ch 7 Replication, Maintenance, and Rearrangements**: 比對 DNA 聚合酶校對能力與 RNA 聚合酶缺乏校對機制的保真度差異。
- **Ch 9 Transcriptional Regulation and Epigenetics**: 探討遠端增強子與 Mediator 複合體如何物理接觸 Pol II 基礎轉錄機器。
- **Ch 10 Protein Synthesis, Processing, and Regulation**: 銜接成熟 mRNA 5' 帽與 3' 尾在細胞質中被轉譯起始因子辨識與環狀化。
