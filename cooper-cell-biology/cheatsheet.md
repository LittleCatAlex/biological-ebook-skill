# Cell & Molecular Biology Cheatsheet (細胞與分子生物學高頻速查手冊)

本手冊收錄《The Cell: A Molecular Approach》第 8 版所有核心物理化學公式、熱力學常數、典型細胞生理參數、抑制劑藥理對照表與經典生奧遺傳決策樹。

---

## 1. 核心物理化學公式與熱力學定律

### 光學顯微鏡阿貝繞射極限 (Abbe's Diffraction Limit)
$$d = \frac{0.61\lambda}{NA} = \frac{0.61\lambda}{n \sin \alpha}$$
- $d$：最小可分辨距離（解析度極限）；可見光下極限約為 **0.2 µm (200 nm)**。
- $\lambda$：照射光波長；$n$：介質折射率（空氣 $n=1.0$，油鏡 $n=1.51$）；$\alpha$：透鏡半孔徑角。

### 酵素米氏動力學 (Michaelis-Menten Kinetics)
$$v = \frac{V_{max}[S]}{K_m + [S]} \qquad \Longleftrightarrow \qquad \frac{1}{v} = \frac{K_m}{V_{max}}\left(\frac{1}{[S]}\right) + \frac{1}{V_{max}}$$
- $K_m$：達半飽和速率（$\frac{1}{2}V_{max}$）時所需的受質濃度，反映酵素對受質的表觀親和力。
- 雙倒數圖 (Lineweaver-Burk)：Y 軸截距為 $1/V_{max}$；X 軸截距為 $-1/K_m$；斜率為 $K_m/V_{max}$。

### 吉布斯自由能與生物能量學 (Gibbs Free Energy)
$$\Delta G = \Delta H - T\Delta S = \Delta G^{\circ'} + RT \ln \left(\frac{[C]^c[D]^d}{[A]^a[B]^b}\right)$$
$$\Delta G^{\circ'} = -RT \ln K_{eq}' = -2.303 RT \log_{10} K_{eq}'$$
- 標準生理狀態下（$25^\circ\text{C}, \text{pH } 7.0$）：$RT \approx 0.59\text{ kcal/mol} \approx 2.48\text{ kJ/mol}$。
- ATP 水解：$\text{ATP} + H_2O \to \text{ADP} + P_i$，標準 $\Delta G^{\circ'} = -7.3\text{ kcal/mol} (-30.5\text{ kJ/mol})$；在活細胞生理條件下實際 $\Delta G \approx -12\text{ kcal/mol}$。

### 化學滲透質子動勢 (Proton-Motive Force, pmF)
$$\Delta p = \Delta \Psi - \frac{2.3 RT}{F}\Delta pH = \Delta \Psi - (60\text{ mV})\Delta pH \quad (\text{在 } 37^\circ\text{C})$$
- 典型粒線體內膜：$\Delta \Psi \approx 160-180\text{ mV}$（內負外正），$\Delta pH \approx 0.5-1.0\text{ 單位}$（外酸內鹼），總質子動勢 $\Delta p \approx 200-220\text{ mV}$。

### 能士特膜平衡電位 (Nernst Equation at 37°C)
$$E_{ion} = \frac{RT}{zF} \ln \left(\frac{[ion]_{out}}{[ion]_{in}}\right) = \frac{61.5\text{ mV}}{z} \log_{10} \left(\frac{[ion]_{out}}{[ion]_{in}}\right)$$
- 典型哺乳動物細胞平衡電位：$E_K \approx -90\text{ mV}$，$E_{Na} \approx +65\text{ mV}$，$E_{Ca} \approx +120\text{ mV}$，$E_{Cl} \approx -70\text{ mV}$。

---

## 2. 關鍵細胞常數與幾何尺度對照

| 生物結構 / 生化分子 | 物理尺度 / 分子量 | 特徵化學或生物學數值 |
| :--- | :--- | :--- |
| **典型動物體細胞直徑** | $10 - 30\ \mu\text{m}$ | 體積約 $1000 - 4000\ \mu\text{m}^3$ |
| **細胞核直徑** | $5 - 10\ \mu\text{m}$ | 佔細胞總體積約 10% |
| **粒線體尺寸** | 寬 $0.5 - 1.0\ \mu\text{m}$，長 $1 - 7\ \mu\text{m}$ | 類似好氧細菌尺寸 |
| **核孔複合體 (NPC)** | 直徑約 $120\text{ nm}$，孔徑約 $40\text{ nm}$ | 分子量約 $120\text{ MDa}$，由約 30 種 Nups 組成 |
| **核醣體尺寸** | 原核 70S ($20\text{ nm}$); 真核 80S ($25-30\text{ nm}$) | 真核由 60S 大單元與 40S 小單元組裝 |
| **微管 (Microtubule)** | 外徑 $25\text{ nm}$，內徑 $14\text{ nm}$ | 由 13 根原纖維圍成，Kinesin 步長 $8\text{ nm}$ |
| **中間絲 (Intermediate Filament)** | 直徑 $10 - 12\text{ nm}$ | 無極性，反平行四聚體組裝 |
| **微絲 (Actin Filament)** | 直徑約 $7\text{ nm}$ | 雙股螺旋，螺距 $36\text{ nm}$ |
| **質膜厚度** | 約 $7.5 - 10\text{ nm}$ (脂質雙層約 $4-5\text{ nm}$) | 疏水厚度約需 20–25 個胺基酸 α-螺旋跨越 |
| **B-DNA 雙螺旋幾何** | 直徑 $2.0\text{ nm}$，螺距 $3.4\text{ nm}$ | 每圈包含 $10.5\text{ bp}$，相鄰鹼基上升 $0.34\text{ nm}$ |
| **核小體核心結構** | 圓盤直徑 $11\text{ nm}$，高度 $5.7\text{ nm}$ | 纏繞 $147\text{ bp}$ DNA 1.65 圈，核心組蛋白八聚體 |
| **完全氧化 1 莫耳葡萄糖 ATP 產額** | **30 或 32 莫耳 ATP** | 依賴蘋果酸-天門冬胺酸穿梭 (32) 或磷酸甘油穿梭 (30) |
| **完全氧化 1 莫耳軟脂酸 (16:0) ATP 產額** | **106 莫耳 ATP** | 淨產額 (108 產出 - 2 活化消耗) |

---

## 3. 細胞生物學經典抑制劑、毒素與抗癌藥物速查表

| 化學藥物 / 毒素 | 作用分子標靶 (Target) | 直接生化與細胞生物學效應 | 經典臨床或科研應用 |
| :--- | :--- | :--- | :--- |
| **魚藤酮 (Rotenone)** | 呼吸鏈複合體 I (NADH 去氫酶) | 阻斷電子自 NADH 流向 CoQ，耗氧停止，$\Delta p$ 崩潰 | 殺蟲劑、粒線體呼吸功能研究 |
| **氰化物 ($CN^-$) / $CO$** | 呼吸鏈複合體 IV (細胞色素 c 氧化酶) | 結合血紅素鐵離子阻斷電子傳給 $O_2$，致命性細胞窒息 | 毒物學機制、急性中毒解毒研究 |
| **寡黴素 (Oligomycin)** | ATP 合成酶 $F_0$ 質子通道 | 堵塞質子回流孔道，完全停止 ATP 合成，繼發減緩耗氧 | 區分電子傳遞鏈偶聯與非偶聯呼吸 |
| **2,4-二硝基酚 (DNP) / FCCP** | 脂質雙層跨膜質子載體 | 消散跨膜質子動勢 ($\Delta p = 0$)，耗氧飆至極限，大量產熱 | 經典化學解偶聯劑 |
| **青黴素 (Penicillin)** | 細菌細胞壁轉肽酶 (Transpeptidase) | 競爭性共價抑制胜肽短鏈交聯，新形成細胞壁滲透破裂 | 抗生素抗菌治療 |
| **秋水仙素 (Colchicine)** | 微管蛋白異二聚體 (Tubulin) | 結合游離二聚體，抑制微管聚合，促使微管解聚 | 核型分析 (阻滯中期)、痛風治療 |
| **紫杉醇 (Paclitaxel / Taxol)** | 微管側壁原纖維 (Microtubule) | 特異穩定微管，強烈抑制微管解聚，凍結動態不穩定性 | 卵巢癌、乳癌一線化療藥物 |
| **胞謝鬆 (Cytochalasin B/D)** | 微絲刺狀端 ((+) Barbed end) | 結合微絲 (+) 端，阻斷肌動蛋白單體聚合 | 研究細胞爬行、胞質分裂收縮環 |
| **鬼筆環肽 (Phalloidin)** | 纖維狀肌動蛋白 (F-actin) 骨架 | 緊密鎖定 F-actin 抑制解聚，偶聯螢光染劑專一性染色 | 螢光顯微鏡微絲細胞骨架專一性染色 |
| **霍亂毒素 (Cholera Toxin)** | 異三聚體 G 蛋白之 $G\alpha_s$ 亞基 | ADP-核糖基化修飾鎖死於 GTP 活化態，cAMP 永久暴增 | 腸道上皮過度分泌氯離子引發水瀉 |
| **百日咳毒素 (Pertussis Toxin)** | 異三聚體 G 蛋白之 $G\alpha_i$ 亞基 | ADP-核糖基化修飾鎖死於 GDP 失活態，解除對 AC 抑制 | 呼吸道上皮發炎、百日咳病理 |
| **破傷風毒素 / 肉毒毒素** | 突觸小泡 SNARE 蛋白 (Synaptobrevin) | 鋅金屬內肽酶專一性水解切斷 SNARE，阻斷神經遞質胞吐 | 破傷風痙攣 / 肉毒中毒肌肉麻痺、除皺美容 |
| **伊馬替尼 (Imatinib / Gleevec)** | Bcr-Abl 嵌合酪胺酸激酶 ATP 口袋 | 競爭性抑制 Bcr-Abl、c-Kit 與 PDGFR 酪胺酸激酶活性 | 慢性骨髓性白血病 (CML)、胃腸道間質瘤 |
| **曲妥珠單抗 (Trastuzumab)** | HER2 / Neu (ERBB2) 受體胞外結構域 | 阻斷 HER2 自發二聚化並誘導內吞降解，招募 ADCC 殺傷 | HER2 過量表現型侵襲性乳癌 |
| **帕博利珠單抗 (Pembrolizumab)** | T 淋巴細胞表面 PD-1 免疫受體 | 阻斷 PD-1 與 PD-L1 抑制性結合，喚醒 CD8+ T 細胞抗癌殺傷 | 黑色素瘤、肺癌、MSI-H 實體腫瘤免疫治療 |
