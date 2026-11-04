# Taiz Plant Physiology Cheatsheet — 高頻解題決策準則與量化速查手冊

專為生物奧林匹亞競賽（IBO）與高等植物生理學研究設計之快速判斷心法、量化公式與診斷對照表。

---

## 1. 生理分析與競賽解題必備決策準則（Decision Rules）

- **當診斷植物未知缺素症狀時（Mineral Deficiency Diagnostic Rule）**：
  - 若病徵（黃化、焦枯、紫紅）最先顯現於**下部老葉** $\to$ 必定為**移動性元素（Mobile elements: N, P, K, Mg）**，因植物啟動水解酵素將養分轉運至新芽。
  - 若病徵最先顯現於**頂端生長點或幼嫩新葉** $\to$ 必定為**非移動性元素（Immobile elements: Ca, Fe, B, Cu）**，因元素進入組織後固定無法再動員。
  - 幼葉脈間黃化但葉脈仍綠 $\to$ **缺鐵（Fe）**；老葉脈間黃化 $\to$ **缺鎂（Mg）**；老葉邊緣壞死捲縮 $\to$ **缺鉀（K）**。

- **當計算水分自發移動方向時（Water Potential Movement Rule）**：
  - 永遠比較兩系統之總水勢：$\Psi = \Psi_s + \Psi_p + \Psi_g$。
  - 水分**永遠且唯一**自總水勢較高（較少負值，如 $-0.2\text{ MPa}$）自發流向總水勢較低（較多負值，如 $-0.8\text{ MPa}$）之區域。
  - 開放式溶液中壓力勢 $\Psi_p = 0$；活植物細胞剛發生質壁分離時 $\Psi_p = 0$（臨界膨壓消失）；完全充水飽和細胞其 $\Psi_{\text{cell}} = 0$，此時 $\Psi_p = -\Psi_s$。

- **當推導光週期開花反應時（Photoperiodic Flowering Rules）**：
  - 遺忘日照長度，直接計算**連續黑暗時數（Dark period length）**。
  - **短日植物（SDP）**：暗期長度 $\ge$ 臨界夜長（Critical Night Length） $\to$ **開花**；若暗期被紅光閃光（Night break）打斷 $\to$ **不開花**。
  - **長日植物（LDP）**：暗期長度 $<$ 臨界夜長 $\to$ **開花**；若暗期被紅光閃光打斷（破壞長夜） $\to$ **促進開花**。
  - 光中斷照射序列中，**最後一次照射之光質決定一切**：若最後為紅光（R, 660 nm）則中斷成立；若最後為遠紅光（FR, 730 nm）則逆轉中斷。

- **當判斷生長素與細胞分裂素組織培養分化時（Organogenesis Ratio Rule）**：
  - $\frac{[\text{Auxin}]}{[\text{Cytokinin}]}$ **比值高** $\to$ 誘導分化形成**根（Roots）**。
  - $\frac{[\text{Auxin}]}{[\text{Cytokinin}]}$ **比值低** $\to$ 誘導分化形成**芽（Shoots）**。
  - $\frac{[\text{Auxin}]}{[\text{Cytokinin}]}$ **比值居中平衡** $\to$ 維持癒傷組織（Callus）不分化分裂生長。

- **當區別光合固碳途徑時（C3 vs C4 vs CAM Diagnostic Rule）**：
  - 具花環構造（Kranz anatomy）、低 $\text{CO}_2$ 補償點（$0\text{--}10\,\mu\text{L/L}$）、無明顯光呼吸 $\to$ **C4 植物**。
  - 白晝葉片組織酸度下降，夜間液胞累積大量蘋果酸使組織滴定酸度飆升、氣孔夜開晝閉 $\to$ **CAM 植物**。
  - 高光呼吸（高溫下可耗損 30% 以上同化碳）、高 $\text{CO}_2$ 補償點（$40\text{--}60\,\mu\text{L/L}$） $\to$ **C3 植物**。

---

## 2. 核心量化定律與計算方程式（Quantitative Equations）

| 生理學定律／指標 | 數學方程式 | 參數意涵與單位說明 |
|---|---|---|
| 水勢總方程式 | $\Psi = \Psi_s + \Psi_p + \Psi_g$ | $\Psi$ 單位為 $\text{MPa}$（$1\text{ MPa} = 10\text{ bar} \approx 9.87\text{ atm}$） |
| 凡特荷夫溶質勢公式 | $\Psi_s = -iCRT$ | $i$ 解離係數（蔗糖=1, $\text{NaCl}$=2）；$R = 0.00831\text{ L}\cdot\text{MPa}/\text{mol}\cdot\text{K}$ |
| 能斯特平衡電位 | $\Delta E = \frac{2.303 RT}{zF} \log_{10}\left(\frac{[C]_o}{[C]_i}\right)$ | 判定離子主動吸入（$\Delta E_{\text{obs}} \neq \Delta E_{\text{Nernst}}$）之熱力學準則 |
| 費克第一擴散定律 | $J = -D \frac{\Delta C}{\Delta x}$ | 描述蒸散氣體及非帶電溶質短距離擴散通量（Flux） |
| 泊肅葉管流動定律 | $J_v = \frac{\pi r^4 \Delta P}{8 \eta L}$ | 導管半徑 $r$ 增加 2 倍，導水水力傳導度暴增 $2^4 = 16$ 倍 |
| 相對生長率（RGR） | $RGR = \frac{1}{W}\frac{dW}{dt} = NAR \times LAR$ | $W$ 乾重；$NAR$ 淨同化率（$g/m^2\cdot\text{day}$）；$LAR$ 葉面積比（$m^2/g$） |
| 葉面積比（LAR） | $LAR = SLA \times LWR$ | $SLA$ 比葉面積（$\text{葉面積}/\text{葉重}$）；$LWR$ 葉乾重佔全株比值 |

---

## 3. 重要生理閾值與物理常數（Physiological Constants）

- **純水水勢基準**：標準大氣壓、同溫下之純水 $\Psi = 0\text{ MPa}$。
- **植物質膜靜息電位**：$-120\text{ mV}$ 至 $-180\text{ mV}$（內負外正，由 P 型 $\text{H}^+$-ATPase 建立）。
- **木質部導管拉伸負壓**：正常蒸散木質部張力為 $-0.5$ 至 $-2.5\text{ MPa}$；孔蝕臨界張力約 $-3.0$ 至 $-4.5\text{ MPa}$。
- **光敏素光化學吸收光譜**：$P_r$ 吸收峰為 $660\text{ nm}$（紅光）；$P_{fr}$ 吸收峰為 $730\text{ nm}$（遠紅光）。
- **向光素與隱花色素激發光譜**：吸收峰為 $450\text{ nm}$（藍光/近紫外光 UV-A）。
- **土壤水分特性值**：田間容水量（Field Capacity）$\approx -0.03\text{ MPa}$；永久凋萎點（PWP）$\approx -1.5\text{ MPa}$。

---

## 4. 關鍵生理構造與途徑診斷矩陣（Diagnostic Matrices）

| 診斷指標 | C3 植物 | C4 植物 | CAM 植物 |
|---|---|---|---|
| 初步固碳酵素 | RuBisCO（葉肉） | PEP 羧化酶（葉肉） | PEP 羧化酶（夜間葉肉） |
| 維管束鞘解剖 | 無花環構造，葉綠體少 | 典型花環構造（Kranz），葉綠體大且多 | 無花環構造，具巨大儲水液胞 |
| 光呼吸速率 | 高（佔光合 25–40%） | 極低（幾乎檢測不到） | 極低（日間檢測不到） |
| $\text{CO}_2$ 補償點 | 高（$40\text{--}60\,\mu\text{L/L}$） | 極低（$0\text{--}10\,\mu\text{L/L}$） | 夜間接近 $0\,\mu\text{L/L}$ |
| 水分利用效率（WUE） | 低（$1\text{--}2\text{ g/kg } \text{H}_2\text{O}$） | 中（$2\text{--}4\text{ g/kg } \text{H}_2\text{O}$） | 極高（$4\text{--}10\text{ g/kg } \text{H}_2\text{O}$） |
| 最適光合溫度 | 較低（$15\text{--}25^\circ\text{C}$） | 高（$30\text{--}40^\circ\text{C}$） | 廣溫適應（夜涼晝熱） |
