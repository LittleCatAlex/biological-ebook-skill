# Human Physiology High-Yield Formulae & Decision Rules
# 人體生理學高頻公式、常數標準與臨床競賽決策速查手冊

---

## Part 1: 核心生物物理與生理學計算公式

### 1. 膜生物物理與電生理學
- **斐克擴散定律（Fick's First Law of Diffusion）**：
  $$J = -P \cdot A \cdot (C_{out} - C_{in})$$
- **單一離子能斯特平衡電位（Nernst Equation, 37°C）**：
  $$E_{ion} = \frac{61}{z} \log_{10} \left( \frac{[ion]_{out}}{[ion]_{in}} \right) \quad \text{(mV)}$$
  - $E_{K^+} \approx -90\text{ mV}, \quad E_{Na^+} \approx +60\text{ mV}, \quad E_{Ca^{2+}} \approx +130\text{ mV}, \quad E_{Cl^-} \approx -70\text{ mV}$
- **高德曼-霍奇金-卡茲膜電位方程式（GHK Equation）**：
  $$V_m = 61 \log_{10} \left( \frac{P_K[K^+]_o + P_{Na}[Na^+]_o + P_{Cl}[Cl^-]_i}{P_K[K^+]_i + P_{Na}[Na^+]_i + P_{Cl}[Cl^-]_o} \right)$$

### 2. 心血管與血流動力學
- **循環歐姆定律（Ohm's Law for Circulation）**：
  $$\text{Flow } (Q) = \frac{\Delta P}{R}$$
- **泊肅葉阻力定律（Poiseuille's Equation）**：
  $$R = \frac{8\eta L}{\pi r^4} \implies R \propto \frac{1}{r^4}$$
- **心輸出量（Cardiac Output）與心搏量（Stroke Volume）**：
  $$CO = HR \times SV \approx 72 \times 70\text{ mL} \approx 5.0\text{ L/min}$$
  $$SV = EDV - ESV \approx 135 - 65 = 70\text{ mL}$$
- **射出分率（Ejection Fraction, EF）**：
  $$EF = \frac{SV}{EDV} \times 100\% \quad (\text{正常 } 55 - 70\%)$$
- **脈搏壓（Pulse Pressure）與平均動脈壓（MAP）**：
  $$PP = SP - DP \approx 120 - 80 = 40\text{ mmHg}$$
  $$MAP = DP + \frac{1}{3}PP = CO \times TPR \approx 80 + 13.3 \approx 93.3\text{ mmHg}$$
- **微血管跨壁史達林淨過濾壓（Net Filtration Pressure, NFP）**：
  $$NFP = (P_c + \pi_{if}) - (P_{if} + \pi_p)$$

### 3. 呼吸系統動力學與血氣
- **波義耳氣體定律（Boyle's Law）**：
  $$P_1V_1 = P_2V_2$$
- **肺泡氣體方程式（Alveolar Gas Equation, 乾空氣海平面）**：
  $$P_AO_2 = F_IO_2(P_{atm} - P_{H_2O}) - \frac{P_ACO_2}{RQ} = 0.21(760 - 47) - \frac{40}{0.8} \approx 150 - 50 = 100\text{ mmHg}$$
- **通氣量計算（Ventilation Dynamics）**：
  $$\text{分鐘肺通氣量 } V_E = TV \times RR \approx 500 \times 12 = 6000\text{ mL/min}$$
  $$\text{有效肺泡通氣量 } V_A = (TV - V_D) \times RR \approx (500 - 150) \times 12 = 4200\text{ mL/min}$$
- **動脈氧含量（Arterial Oxygen Content, $CaO_2$）**：
  $$CaO_2 = (1.34 \times [Hb] \times SaO_2) + (0.003 \times P_aO_2) \approx 20.1\text{ mL } O_2 / 100\text{ mL blood}$$

### 4. 腎臟與體液排泄動力學
- **淨過濾壓（Glomerular Net Filtration Pressure）**：
  $$NFP = P_{GC} - P_{BS} - \pi_{GC} \approx 55 - 15 - 30 = 10\text{ mmHg}$$
- **腎清除率通用公式（Renal Clearance）**：
  $$C_x = \frac{U_x \times V}{P_x} \quad (\text{mL/min})$$
  - 菊糖清除率 $C_{inulin} = GFR \approx 125\text{ mL/min}$
  - PAH 清除率 $C_{PAH} = \text{有效腎血漿流量 } (RPF) \approx 625\text{ mL/min}$
- **腎血流量（Renal Blood Flow, RBF）**：
  $$RBF = \frac{RPF}{1 - Hct} \approx \frac{625}{1 - 0.45} \approx 1136\text{ mL/min} \quad (\approx 20-25\% CO)$$
- **過濾分率（Filtration Fraction, FF）**：
  $$FF = \frac{GFR}{RPF} = \frac{125}{625} = 0.20 = 20\%$$

### 5. 酸鹼平衡與陰離子間隙
- **韓德森-哈塞爾巴赫方程式（Henderson-Hasselbalch Equation）**：
  $$pH = 6.1 + \log_{10} \left( \frac{[HCO_3^-]}{0.03 \times PCO_2} \right)$$
- **血清陰離子間隙（Serum Anion Gap, AG）**：
  $$AG = [Na^+] - ([Cl^-] + [HCO_3^-]) \quad (\text{正常 } 8 - 12\text{ mEq/L})$$
- **代謝性酸中毒之呼吸代償預期公式（Winter's Formula）**：
  $$\text{Expected } PCO_2 = (1.5 \times [HCO_3^-]) + 8 \pm 2$$

---

## Part 2: 人體標準正常生理參數與常數速查表

| 生理參數名稱 | 標準正常值範圍 (SI / 常規單位) | 生理意義與極限臨界值 |
|---|---|---|
| **動脈血 pH** | $7.35 - 7.45$ (標準 7.40) | $< 6.8$ 或 $> 7.8$ 致死；$[H^+] \approx 40\text{ nmol/L}$ |
| **動脈二氧化碳分壓 ($P_aCO_2$)** | $35 - 45\text{ mmHg}$ (標準 40 mmHg) | 通氣金標準；$> 45$ 酸中毒；$< 35$ 鹼中毒 |
| **動脈氧分壓 ($P_aO_2$)** | $80 - 100\text{ mmHg}$ (海平面安靜) | $< 60\text{ mmHg}$ 啟動周邊化學感受器急救放電 |
| **動脈血碳酸氫根 ($[HCO_3^-]$)** | $22 - 26\text{ mEq/L}$ (標準 24 mEq/L) | 代謝性酸鹼指標；由腎臟主動合成回收 |
| **血清鈉離子 ($[Na^+]$)** | $135 - 145\text{ mEq/L}$ | ECF 滲透壓與 ECF 容積最主要決定者 |
| **血清鉀離子 ($[K^+]$)** | $3.5 - 5.0\text{ mEq/L}$ (狹窄窗口) | 靜止膜電位核心；$< 2.5$ 或 $> 6.5$ 致死心律不整 |
| **血清游離鈣離子 ($[Ca^{2+}]$)** | $1.1 - 1.3\text{ mM}$ (總鈣 2.2-2.6 mM) | 神經肌肉興奮與血液凝固關鍵；低鈣致抽搐 |
| **血漿滲透壓 (Plasma Osmolarity)**| $285 - 295\text{ mOsm/kg } H_2O$ | 嚴密維持；決定 ICF 與 ECF 水分轉移平衡 |
| **空腹血糖 (Fasting Glucose)** | $70 - 99\text{ mg/dL}$ (3.9 - 5.5 mM) | 胰島素與昇糖素拮抗調控；腎閾值 180 mg/dL |
| **血比容 (Hematocrit, Hct)** | 男性 42-52%；女性 37-47% | RBC 佔全血容積比例；決定全血黏滯度 $\eta$ |
| **腎絲球過濾率 (GFR)** | $120 - 125\text{ mL/min}$ ($180\text{ L/day}$) | 腎功能金標準；$< 15\text{ mL/min}$ 為終末期腎衰 |
| **血清肌酸酐 (Serum Creatinine)**| $0.6 - 1.2\text{ mg/dL}$ | 肌肉代謝產物；GFR 下降 50% 時始顯著升高 |

---

## Part 3: 競賽與臨床高頻診斷決策流程樹

### 1. 動脈血氣分析（ABG）酸鹼四步診斷法
```
[步驟 1: 看 pH]
   ├─► pH < 7.35 ──► 酸血症 (Acidemia) ──┐
   └─► pH > 7.45 ──► 鹼血症 (Alkalemia) ─┼──► [步驟 2: 看原發方向]
                                         │      ├─► 若 PCO2 偏異方向與 pH 一致 ──► 呼吸性
                                         │      └─► 若 HCO3- 偏異方向與 pH 一致 ─► 代謝性
                                         ▼
[步驟 3: 若為代謝性酸中毒，必算 AG]
   AG = Na+ - (Cl- + HCO3-)
   ├─► AG > 12 ──► 高陰離子間隙代酸 (MUDPILES: 酮酸、乳酸、尿毒、中毒)
   └─► AG 8-12 ──► 正常陰離子間隙 / 高氯性代酸 (腹瀉失鹼、RTA)
                                         ▼
[步驟 4: 計算預期代償公式 (有無第二種合併失衡)]
   - 代酸預期 PCO2 = 1.5 * [HCO3-] + 8 ± 2 (Winter's formula)
     ├─ 實測 PCO2 恰在區間 ──► 單純性代謝性酸中毒 (完全代償)
     ├─ 實測 PCO2 > 預期上限 ──► 合併「呼吸性酸中毒」(通氣衰竭)
     └─ 實測 PCO2 < 預期下限 ──► 合併「呼吸性鹼中毒」(過度通氣)
```

### 2. 內分泌下視丘-垂體-周邊腺體原發性 vs 次發性病態定位矩陣
| 內分泌臨床狀態 | 周邊目標激素 (T3/T4, 皮質醇) | 垂體營養激素 (TSH, ACTH) | 病變解剖定位與診斷 |
|---|---|---|---|
| **原發性機能亢進** | $\Uparrow$ (異常暴升) | $\Downarrow$ (被負回饋完全壓制) | 周邊靶腺本身腺瘤或刺激性抗體 (如 Graves' 突眼) |
| **次發性機能亢進** | $\Uparrow$ (被動升高) | $\Uparrow$ (不受控過度分泌) | 腦下垂體前葉腺瘤 (如 Cushing 病, TSH 腺瘤) |
| **原發性機能低下** | $\Downarrow$ (靶腺衰竭分泌不足) | $\Uparrow$ (負回饋解除代償飆高) | 周邊靶腺實質破壞 (如 Hashimoto 甲狀腺炎, Addison 病) |
| **次發性機能低下** | $\Downarrow$ (缺乏刺激) | $\Downarrow$ (垂體或下視丘衰竭) | 腦下垂體壞死 (如席漢氏症 Sheehan's) 或垂體腫瘤壓迫 |

### 3. 阻塞型 vs 限制型肺功能測試（PFT）鑑別決策樹
```
[進行用力肺活量 Spirometry 測試]
               │
               ▼
      [評估 FEV1 / FVC 比值]
         ├─► FEV1 / FVC < 70% ──► **阻塞型肺疾 (Obstructive)**
         │                          ├─ 支氣管擴張劑可逆 (> 12% 且 > 200 mL) ──► **氣喘 (Asthma)**
         │                          └─ 不可逆，殘氣量 RV 與 TLC 升高 ────────► **COPD / 肺氣腫**
         │
         └─► FEV1 / FVC ≥ 70% ──► [檢查肺總量 TLC]
                                    ├─ TLC 正常 (80-120% 預測值) ──► **完全正常肺功能**
                                    └─ TLC < 80% 預測值 ──────────► **限制型肺疾 (Restrictive)**
                                                                       ├─ 肺實質纖維化 (DLCO 下降)
                                                                       └─ 胸壁/神經肌肉病變 (DLCO 正常)
```
