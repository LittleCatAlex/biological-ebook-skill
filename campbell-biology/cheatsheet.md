# Campbell Biology Cheatsheet — High-Yield Decision Rules & Quick Reference

A rapid-lookup decision aid, diagnostic heuristic guide, and mathematical formula reference for biological analysis and Olympiad problem solving.

---

## 1. Decision Rules for Problem Solving

- **When analyzing an unknown pedigree pattern**:
  - If affected offspring are born to unaffected parents $    o$ rule is **Autosomal Recessive** ($Aa \times Aa \to aa$).
  - If affected fathers transmit the trait to **ALL daughters and NO sons** $    o$ rule is **X-Linked Dominant**.
  - If trait appears almost exclusively in males and skips generations through carrier females $    o$ rule is **X-Linked Recessive**.
  - If trait is transmitted exclusively from affected males to all male offspring $    o$ rule is **Y-Linked (Holandric)**.
  - If all offspring of an affected mother inherit the trait, but no offspring of an affected father do $    o$ rule is **Mitochondrial Maternal Inheritance**.

- **When calculating plant water movement direction**:
  - Always compute total water potential: $\Psi = \Psi_s + \Psi_p$.
  - Water **ALWAYS** moves spontaneously from higher (less negative) $\Psi$ toward lower (more negative) $\Psi$.
  - In an open beaker at atmospheric pressure, $\Psi_p = 0$, so $\Psi = \Psi_s$.
  - Calculate solute potential: $\Psi_s = -iCRT$ (where $i$ is ionization constant: sucrose = 1, $\text{NaCl} = 2$; $R = 0.0831\text{ L}\cdot\text{bar}/\text{mol}\cdot\text{K}$ or $0.00831\text{ L}\cdot\text{MPa}/\text{mol}\cdot\text{K}$).

- **When evaluating enzyme kinetic inhibition (Lineweaver-Burk Plot)**:
  - If curves intersect at the $y$-axis ($1/V_{max}$ unchanged) with altered $x$-intercept ($-1/K_m$ shifted) $    o$ **Competitive Inhibition** (can be overcome by excess substrate).
  - If curves intersect at the $x$-axis ($-1/K_m$ unchanged) with elevated $y$-intercept (reduced $V_{max}$) $    o$ **Non-competitive Inhibition** (allosteric site binding).
  - If lines are strictly parallel (both $V_{max}$ and $K_m$ decrease proportionally) $    o$ **Uncompetitive Inhibition** (binds only to enzyme-substrate complex).

- **When determining plant photosynthetic adaptation**:
  - High photorespiration risk in hot/arid conditions? $    o$ Check for **Kranz anatomy** (bundle-sheath chloroplasts) = **C4 Plant** (spatial separation via PEP carboxylase).
  - Stomata open only at night, malate stored in central vacuoles, daytime Calvin cycle with closed stomata? = **CAM Plant** (temporal separation).

---

## 2. Key Mathematical Formulas & Quantitative Laws

| Concept / Model | Mathematical Formula | Variables & Constants |
|---|---|---|
| Gibbs Free Energy | $\Delta G = \Delta H - T\Delta S$ | Spontaneous when $\Delta G < 0$; at equilibrium $\Delta G = 0$ |
| Equilibrium Free Energy | $\Delta G^\circ = -RT \ln K_{eq}$ | $R = 8.314\text{ J/mol}\cdot\text{K}$, $T$ in Kelvin |
| Hardy-Weinberg Law | $p + q = 1, \quad p^2 + 2pq + q^2 = 1$ | $p = f(A), q = f(a)$; $2pq$ = frequency of heterozygotes |
| Water Potential | $\Psi = \Psi_s + \Psi_p, \quad \Psi_s = -iCRT$ | $i$ = ionization constant, $C$ = molar concentration |
| Exponential Growth | $\frac{dN}{dt} = rN, \quad N(t) = N_0 e^{rt}$ | $r$ = per capita intrinsic rate of increase |
| Logistic Growth | $\frac{dN}{dt} = rN\left(\frac{K-N}{K}\right)$ | $K$ = carrying capacity; max growth rate occurs at $N = K/2$ |
| Lincoln-Petersen Index | $N = \frac{M \cdot n}{R}$ | $M$ = marked initially, $n$ = second capture total, $R$ = recaptured marked |
| Shannon Diversity Index | $H' = -\sum_{i=1}^S p_i \ln p_i$ | $p_i$ = relative abundance of $i$-th species |
| Nernst Equation (Membrane) | $E_{ion} = \frac{61.5}{z} \log_{10}\left(\frac{[ion]_{out}}{[ion]_{in}}\right)$ | At $37^\circ\text{C}$ in mV; $z$ = valence charge of ion |
| Trophic Ecological Efficiency | $\text{Efficiency} = \frac{\text{Production at Level } n}{\text{Production at Level } n-1} \approx 10\%$ | Limits food chains to 4–5 trophic levels |

---

## 3. High-Yield Physiological Constants & Thresholds

- **Neuron Action Potential**: Resting membrane potential $\approx -70\text{ mV}$; Threshold potential $\approx -55\text{ mV}$; Peak overshoot $\approx +35\text{ mV}$.
- **Human Blood Homeostasis**: Arterial pH $= 7.35\text{--}7.45$ (buffered by $\text{H}_2\text{CO}_3 / \text{HCO}_3^-$); fasting glucose $= 70\text{--}100\text{ mg/dL}$.
- **Aerobic Glucose ATP Stoichiometry**: Theoretical maximum $= 30\text{--}32\text{ ATP}$ per glucose molecule ($1\text{ NADH} \to 2.5\text{ ATP}$; $1\text{ FADH}_2 \to 1.5\text{ ATP}$).
- **Photosynthetic Energy Requirement**: Minimum 8–10 photons absorbed to evolve $1\text{ mole } \text{O}_2$ and reduce $2\text{ NADPH} + 3\text{ ATP}$.

---

## 4. Diagnostic Comparison Matrices

| Biological Feature | Bacteria | Archaea | Eukarya |
|---|---|---|---|
| Nuclear Envelope & Organelles | Absent | Absent | Present |
| Peptidoglycan in Cell Wall | Present | Absent | Absent (Cellulose or Chitin) |
| Membrane Lipid Linkage | Ester-linked, unbranched fatty acids | Ether-linked, branched isoprene hydrocarbons | Ester-linked, unbranched fatty acids |
| Initiator Amino Acid | Formyl-methionine (fMet) | Methionine | Methionine |
| RNA Polymerase Complexity | Single simple polymerase (4 subunits) | Several complex types (resemble eukaryotic) | Three distinct polymerases (Pol I, II, III) |
| Response to Streptomycin/Chloramphenicol | Growth inhibited | Growth not inhibited | Growth not inhibited |
| Introns in Protein-Coding Genes | Extremely rare | Present in some genes | Frequent in protein-coding genes |

| Embryological Feature | Protostome Development | Deuterostome Development |
|---|---|---|
| Cleavage Pattern | Spiral and Determinate | Radial and Indeterminate (twinning possible) |
| Coelom Formation | Schizocoelous: solid masses of mesoderm split | Enterocoelous: folds of archenteron form coelom |
| Blastopore Fate | Blastopore becomes the **Mouth** (anus forms second) | Blastopore becomes the **Anus** (mouth forms second) |
| Major Animal Phyla | Mollusca, Annelida, Arthropoda, Nematoda | Echinodermata, Chordata, Hemichordata |
