# Chapter 18: The Cell Cycle (細胞週期)

> **Part**: Part IV — Cell Regulation (細胞調控機制)

## Core Idea
細胞週期由 CDK-Cyclin 複合體引擎嚴格驅動單向不可逆推進：在 G1 期由生長因子引導 Rb-E2F 雙穩態開關跨越限制點；當 DNA 損傷時，ATM/ATR-p53-p21 防線阻滯週期進程；進入 M 期後，紡錘體組裝檢查點（SAC）監控染色體雙極張力，經 APC/C 泛素化降解 Securin 與 Cyclin B 引爆姊妹染色分體分離與胞質分裂。

## Sections Outline
- **18.1 The Eukaryotic Cell Cycle (真核細胞週期分期、G0 休眠與 G1 限制點)**
- **18.2 Regulators of Cell Cycle Progression (CDK、Cyclin、Wee1/Cdc25 開關、CKIs 與 DNA 損傷檢查點)**
- **18.3 The Events of M Phase (有絲分裂推進、SAC 紡錘體組裝檢查點、APC/C 蛋白酶體降解與胞質分裂)**

## Frameworks Introduced
### G1 Restriction Point & Rb-E2F Bistable Switch Model (G1 限制點與 Rb-E2F 雙穩態分子開關模型)
- **When to use**: 分析真核細胞如何脫離生長因子依賴性、自發承諾啟動 DNA 複製與細胞分裂
- **How to apply**:
1. 休眠期抑制態：在 G0 期與早期 G1 期，**低磷酸化 Rb (未磷酸化/低磷酸化視網膜母細胞瘤蛋白)** 緊緊結合 **E2F** 轉錄因子家族，並招募組蛋白去乙醯酶 (HDACs)，牢固壓制 S 期基因轉錄。
2. 生長因子啟動一階單磷酸化：
   - 胞外有絲分裂原 (Mitogens) 激活 Ras-MAPK 途徑，誘導 **Cyclin D** 轉錄與累積。
   - **CDK4/6-Cyclin D** 複合體組裝，對 Rb 進行一階「單磷酸化 (Hypo-phosphorylation)」。
   - 單磷酸化後的 Rb 鬆動但尚未完全解離 E2F，足以誘導低水平 **Cyclin E** 轉錄。
3. 限制點突破與全或無過度磷酸化：
   - **CDK2-Cyclin E** 活化後，對 Rb 進行全方位 **過度磷酸化 (Hyper-phosphorylation)**（在多達 14 個絲/蘇胺酸位點加上磷酸基）。
   - 劇烈的電荷排斥使 Rb 構型崩潰，**完全解離釋放 E2F**。
   - 游離 E2F 招募 HATs 強力活化自身 (*E2F*)、*Cyclin E*、*Cyclin A*、DNA 聚合酶與 MCM 解旋酶轉錄。
4. 正反饋鎖死不可逆性：Cyclin E 暴增進一步強化 CDK2 活性，反向維持 Rb 100% 過度磷酸化。此時即使完全撤除胞外生長因子，正反饋迴路已將開關永久鎖定在「開 (ON)」狀態，細胞**正式跨越限制點 (Restriction Point)**，不可逆邁向 S 期複製。

### DNA Damage Checkpoint Signaling Architecture (DNA 損傷檢查點信號傳導架構)
- **When to use**: 追蹤細胞感應雙股斷裂 (DSB) 或單股複製叉停滯後的阻滯修復與凋亡決策
- **How to apply**:
1. 雙股斷裂 (DSBs) 感應途徑 (ATM-Chk2 軸)：
   - MRN 複合體辨識斷端，招募並二聚化自活化 **ATM 激酶**。
   - ATM 磷酸化組蛋白變體 **H2AX (形成 $\gamma$-H2AX 焦點)**，標記損傷位點並招募 MDC1 與修復機器。
   - ATM 磷酸化活化下游 **Chk2 激酶**。
2. 複製叉停滯與單股 DNA 感應途徑 (ATR-Chk1 軸)：
   - 複製叉解旋與聚合酶解偶聯，暴露出長單股 DNA (ssDNA)，迅速被 **RPA** 蛋白包裹。
   - RPA 招募 ATRIP，激活 **ATR 激酶**；ATR 磷酸化活化下游 **Chk1 激酶**。
3. 阻滯效應器分支：
   - 快速暫態阻滯 (Cdc25 降解)：Chk1/Chk2 磷酸化 **Cdc25A/C 磷酸酶**，誘導其結合 14-3-3 蛋白並被泛素化降解。缺乏 Cdc25，CDK2/CDK1 上的 Wee1 抑制性磷酸基 (Thr14/Tyr15) 無法被移除，**週期立即剎車阻滯**。
   - 持續穩定阻滯 (p53-p21 軸)：ATM 與 Chk2 磷酸化 **p53** 的 N 端 Ser15 與 Ser20，破壞 E3 連接酶 Mdm2 與 p53 的結合，p53 擺脫降解迅速大量累積並形成同源四聚體。
   - 轉錄誘導 CKI：活化之 p53 強力活化 ***CDKN1A* (編碼 p21Cip1)** 轉錄；p21 結合併完全抑制 CDK2/CDK4 激酶，將細胞牢牢阻滯於 G1 期給予充分修復時間；若損傷過於災難無法修復，p53 誘導 *Puma* 與 *Bax* 轉錄啟動細胞凋亡。

### SAC & APC/C-Triggered Metaphase-to-Anaphase Switch (紡錘體檢查點與後期起始分子開關)
- **When to use**: 解析未正確附著動原體如何產生「等待信號」及張力平衡後姊妹染色分體瞬間彈開機制
- **How to apply**:
1. 中期「等待」信號 (SAC 活化)：
   - 只要有 **任何單一動原體未與紡錘絲微管結合**，或缺乏雙向對向張力，動原體上的 Aurora B 激酶即磷酸化外板結構，招募 **Mad1-Mad2** 複合體。
   - Mad2 構型由開放態 (O-Mad2) 轉變為閉合態 (C-Mad2)，與 **BubR1、Bub3** 組裝成 **有絲分裂檢查點複合體 (MCC)**。
   - MCC 如同手銬牢牢錮鎖 **Cdc20**，使後期促進複合體 (**APC/C**) 保持完全無催化活性。
2. 張力平衡與抑制解除：
   - 當所有染色體完成兩極雙向附著 (Amphitelic attachment)，微管向兩極拉扯產生巨大機械張力。
   - 張力將外板動原體底物拉出 Aurora B 的磷酸化觸及半徑，磷酸酶去磷酸化，MCC 解體，**釋放游離活性的 Cdc20**。
3. 姊妹分體分離與有絲分裂退出 (APC/C-Cdc20 激活)：
   - **APC/C-Cdc20** (巨大多亞基 E3 泛素連接酶) 活化，迅速多聚泛素化降解 **Securin (分離蛋白伴侶)**。
   - 伴侶降解釋放出游離活性的 **Separase (分離蛋白酶)**。
   - Separase 精準切割環繞姊妹染色分體之間的 **黏連蛋白 (Cohesin)** 核心亞基 **Scc1 (Rad21)**，套索解開，姊妹分體毫秒內同步被拉向兩極（後期 A 開始）。
   - 同步降解 Cyclin B：APC/C-Cdc20 同步泛素化降解 **Cyclin B**，CDK1 活性雪崩式下跌，細胞核膜得以在末期重新組裝，細胞退出有絲分裂。

## Key Concepts
- **Restriction Point (限制點 / START)**: G1 期晚期的不可逆分子關卡，受生長因子誘導之 Cyclin D-CDK4/6 與 Rb 磷酸化控制；一旦跨越，細胞將自主推進完成 S 期、G2 期與 M 期分裂。
- **Cyclin-Dependent Kinases (CDKs, 週期素依賴性激酶)**: 細胞週期引擎的核心催化絲/蘇胺酸激酶，催化活性絕對依賴特定週期素 (Cyclin) 結合並經 CAK 磷酸化 Thr 殘基。
- **Wee1 Kinase & Cdc25 Phosphatase (Wee1 激酶與 Cdc25 磷酸酶)**: 控制 M-CDK (CDK1) 活性的雙重開關：Wee1 磷酸化 Thr14/Tyr15 抑制活性；Cdc25 脫去該兩抑制性磷酸基，產生極速正反饋全或無暴發性活化。
- **CKIs (CDK 抑制蛋白)**: 兩大家族：INK4 家族 (p16INK4a, p15) 專一性結合 CDK4/6 阻止其與 Cyclin D 結合；Cip/Kip 家族 (p21Cip1, p27Kip1) 廣泛抑制 CDK2/1 複合體。
- **Retinoblastoma Protein (Rb, 視網膜母細胞瘤蛋白)**: 經典腫瘤抑制蛋白，去磷酸化狀態下結合 E2F 抑制轉錄，過度磷酸化解離 E2F 釋放細胞進入 S 期。
- **p53 & p21 (p53 轉錄因子與 p21 抑制劑)**: p53 感應 DNA 損傷累積，轉錄激活 p21Cip1；p21 抑制 CDK2/Cyclin E/A 激酶將細胞完全阻滯於 G1/S 期進行修復。
- **SAC (Spindle Assembly Checkpoint, 紡錘體組裝檢查點)**: 監控中期動原體微管雙向附著與拉伸張力的精密機制，未附著動原體生成 MCC 複合體阻斷 APC/C-Cdc20 活化。
- **Cohesin & Separase (黏連蛋白與分離酶)**: Cohesin 環狀四聚體複合體（Scc1, Scc3, Smc1, Smc3）套住姊妹染色分體；Separase 蛋白酶水解切斷 Scc1 觸發後期染色體分離。
- **Contractile Ring (胞質分裂收縮環)**: 由質膜下皮層肌動蛋白微絲 (Actin) 與非肌肌球蛋白 II (Myosin II) 雙向排列組裝成的短暫環狀結構，受 RhoA GTPase 調控向心收縮掐斷細胞。
- **Endoreplication (核內複製 / 多線化)**: 細胞歷經連續的 G1 與 S 期進行多次 DNA 複製，但完全跳過 M 期有絲分裂與胞質分裂，形成巨大多倍體細胞（如果蠅幼蟲唾腺多線染色體）。

## Mental Models
- **Think of the Restriction Point as a Slipper Clutched by Rb (將限制點視為被 Rb 夾住的灰姑娘玻璃鞋)**: E2F 是灰姑娘的腳，低磷酸化的 Rb 像一隻鋼夾死死咬住腳踝；CDK4/6 先敲裂第一道鎖，CDK2 火力全開炸碎鋼夾（過度磷酸化），E2F 自由奔向舞池（啟動 S 期）。
- **Think of Wee1 and Cdc25 as a Handbrake and Turbo Trigger (將 Wee1 與 Cdc25 視為手煞車與渦輪點火)**: Wee1 拉起手煞車（磷酸化 Thr14/Tyr15），讓 CDK1-Cyclin B 在 G2 期安靜累積彈藥；時間一到，Cdc25 一把放下手煞車並點燃渦輪，M-CDK 瞬間衝刺引爆有絲分裂。
- **Think of Separase as the Scissors Cutting the Ribbon for the Race (將分離酶視為剪綵起跑的剪刀)**: Securin 是套在剪刀刃上的保護套；APC/C 把保護套扯掉，Separase 剪刀喀嚓一聲剪斷 Cohesin 綵帶，兩側早已繃緊微管纜繩的姊妹染色單體瞬間朝兩極彈開。

## Anti-patterns
- **混淆 p53 在正常細胞與損傷細胞中的調控機制：正常細胞中 p53 並非不表現，而是表現後**迅速被 E3 連接酶 Mdm2 結合並多聚泛素化，被 26S 蛋白酶體極速降解（半衰期僅約 20 分鐘）**；DNA 損傷時 ATM/Chk2 磷酸化 p53 破壞了其與 Mdm2 的結合界面，使 p53 免於降解迅速累積。**: 在 p53 基因調控題中誤以為 DNA 損傷是促進 p53 的轉錄合成。
- **誤以為動原體只要附著微管就能通過 SAC 檢查點：SAC 不僅檢查「微管是否物理附著」，更關鍵的是檢測「**微管是否產生了對向拉扯機械張力 (Bipolar tension)**」；若兩極微管附著在同一個動原體上（同極附著 Syntelic attachment），由於缺乏反向拉力，SAC 依然處於報警阻滯狀態。**: 在染色體分離檢查點細節中遺漏雙向張力感應指標。
- **混淆 Wee1 與 CAK 的磷酸化效應：CAK 磷酸化 CDK1 的 Thr161 是「**活化性磷酸化**」；Wee1 磷酸化 CDK1 的 Thr14/Tyr15 是「**抑制性磷酸化**」，兩者磷酸化位點與生理功能完全相反。**: 在細胞週期激酶調控網絡中標錯磷酸化位點極性。

## Reference Tables
| 細胞週期時相 | 主導之 CDK-Cyclin 複合體 | 關鍵上游調節激酶 / 磷酸酶 | 主要細胞內磷酸化受質 | 核心驅動之細胞事件 |
| :--- | :--- | :--- | :--- | :--- |
| **G0 / 早期 G1 期** | 無活躍複合體 (受 CKI 壓制) | 生長因子誘導 ERK 活化 | 無 (Rb 處於低磷酸化抑制態) | 細胞維持休眠或感應生長信號，開始合成 Cyclin D |
| **中晚期 G1 期 (跨越限制點)** | **CDK4/6 - Cyclin D** | INK4 (p16) 抑制, CAK 活化 | **Rb 蛋白 (單磷酸化)** | 啟動初階 E2F 轉錄，誘導 Cyclin E 表現 |
| **G1/S 期轉換 (啟動複製)** | **CDK2 - Cyclin E** | Cip/Kip (p21/p27) 抑制 | **Rb 蛋白 (過度磷酸化)** | 徹底解離 E2F，爆發性轉錄 S 期基因，前複製複合體放電 |
| **S 期推進 (DNA 複製)** | **CDK2 - Cyclin A** | ATR-Chk1 監控複製叉 | 複製因子 (Cdc6, Cdt1, Pol α) | 驅動複製叉推進，磷酸化抑制 Cdt1 防止二次複製 (Licensing) |
| **G2/M 期轉換 (有絲分裂啟動)** | **CDK1 (Cdc2) - Cyclin B** | **Wee1 抑制, Cdc25 活化**, CAK | 核纖層蛋白 (Lamins), Condensin, MAPs | 染色質凝縮、核被膜瓦解、中心體分開、組裝紡錘體 |
| **中期向後期轉換 (染色體分離)** | **APC/C - Cdc20** (E3 連接酶) | SAC 檢查點 (Mad2/BubR1) 監控 | **Securin, Cyclin B (多聚泛素化)** | 活化 Separase 切斷 Cohesin，姊妹分體分離，退出 M 期 |

## Worked Example
**經典發育與細胞生物學實驗推導：Masui & Markert 爪蟾卵母細胞 MPF 活性微注射鑑定**

1. **實驗背景與體系**：
   - 未受精的南非爪蟾 (Xenopus laevis) 卵母細胞天然停滯於減數分裂前期的 **G2 期**。
   - 在體內，孕酮 (Progesterone) 激素刺激引發卵母細胞恢復減數分裂，推進至中期 II (MII) 停滯（此狀態稱為成熟卵）。
2. **微注射實驗設計 (Masui & Markert 1971)**：
   - **實驗組 A**：用微吸管抽取處於 MII 期成熟卵的細胞質（僅約 50 nL），微量注射進入未經孕酮處理的停滯期 G2 卵母細胞中。
   - **實驗組 B (對照組)**：抽取普通 G2 期未成熟卵的細胞質，注射入同等 G2 卵母細胞中。
   - **蛋白質合成抑制測試**：在注射實驗組 A 細胞質前，預先加入環己醯亞胺 (Cycloheximide) 徹底阻斷宿主蛋白質的新生轉譯。
3. **實驗表型觀察**：
   - **實驗組 A 結果**：受注射的 G2 卵母細胞在完全無孕酮誘導下，**迅速自發發生核被膜瓦解 (GVBD) 並組裝減數分裂紡錘體**，直接躍進進入 M 期！
   - **對照組 B 結果**：細胞依然平靜停滯於 G2 期，無任何成熟跡象。
   - **環己醯亞胺測試結果**：即使細胞完全無法合成任何新蛋白質，注入 MII 胞質依然能**直接觸發核膜瓦解進入 M 期**！
4. **結論與科學里程碑**：
   - 證實 M 期細胞質中存在一種具備催化活性的全能驅動因子，命名為 **成熟促進因子 (Maturation Promoting Factor, MPF)**。
   - MPF 作用無需依賴新蛋白質合成，提示其為一種已預先存在並透過轉譯後化學修飾（去磷酸化）瞬間激活的酵素。
   - 後續純化與遺傳學證實，MPF 的生化本質即為萬能的 **CDK1-Cyclin B 異二聚體激酶複合體**，奠定了全真核生物細胞週期調控統一模型的歷史基石。

## Key Takeaways
1. 真核細胞週期受 CDK-Cyclin 複合體引擎單向推進，G1 限制點由 Cyclin D-CDK4/6 與 Rb 過度磷酸化解離 E2F 決定跨越。
2. Wee1 抑制性磷酸化與 Cdc25 活化性去磷酸化構成控制 CDK1-Cyclin B 活性的雙重開關，引爆有絲分裂前中期快速啟動。
3. DNA 損傷檢查點由 ATM/ATR 感應，透過 Chk1/Chk2 降解 Cdc25 實現即刻剎車，並磷酸化穩定 p53 誘導 p21 實現長期阻滯。
4. 紡錘體組裝檢查點 (SAC) 監控動原體微管雙向附著與拉力，未附著動原體組裝 MCC 複合體錮鎖 Cdc20 阻止後期啟動。
5. 當 SAC 警報解除，APC/C-Cdc20 泛素化降解 Securin 釋放 Separase 蛋白酶切斷 Cohesin 黏連蛋白，引爆姊妹染色分體瞬間彈開分離。

## Connects To
- **Ch 11 The Nucleus**: 深入核纖層蛋白 (Lamins) 在前中期被 CDK1 磷酸化引發核被膜解體。
- **Ch 14 The Cytoskeleton and Cell Movement**: 對接動原體微管牽拉力學、肌動蛋白-Myosin II 胞質分裂收縮環。
- **Ch 20 Cancer**: 連結腫瘤中 Rb 突變、p53 突變及 p16INK4a 缺失導致的細胞週期失控性無限增殖。
