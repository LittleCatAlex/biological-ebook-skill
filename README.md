# Biological Ebook Agent Skills (生物學經典教科書 Agent 技能庫)

本儲存庫收錄依據國際生物奧林匹亞（IBO）與高等生命科學學術標準構建之經典生物教科書 Agent 技能庫（Skills），嚴格遵循台灣教育部與大學生命科學審閱標準名詞（全繁體中文與專業英文雙語對照）。

---

## 📚 收錄技能列表 (Included Skills)

| 技能目錄 | 對應經典權威教科書 | 涵蓋範疇與章節規模 |
| :--- | :--- | :--- |
| **[`campbell-biology/`](campbell-biology/)** | *Campbell Biology* (12th Edition)<br>by Lisa A. Urry et al. | **全書 56 章**<br>涵蓋化學基礎、細胞、遺傳學、演化、生命多樣性、植物動植物形態與生理、生態學 |
| **[`taiz-plant-physiology/`](taiz-plant-physiology/)** | *Plant Physiology* (5th Edition)<br>by Lincoln Taiz & Eduardo Zeiger | **全書 26 章 + 3 大附錄**<br>水分子運動、溶質轉運、光合光/暗反應、韌皮部運輸、二次代謝、植物荷爾蒙、光形態發生、逆境生理學 |
| **[`sherwood-human-physiology/`](sherwood-human-physiology/)** | *Human Physiology: From Cells to Systems* (6th Edition)<br>by Lauralee Sherwood | **全書 20 章**<br>細胞膜電位、神經與自主神經系統、肌肉生理、心臟與循環、呼吸力學、腎臟水鹽平衡、消化吸收、內分泌與生殖系統 |
| **[`cooper-cell-biology/`](cooper-cell-biology/)** | *The Cell: A Molecular Approach* (8th Edition)<br>by Geoffrey M. Cooper | **全書 20 章**<br>細胞分子與化學滲透、遺傳訊息流動（轉錄/剪接/轉譯/表觀調控）、核質運輸與胞器轉位、細胞骨架與力學、細胞訊息傳遞、細胞週期、幹細胞凋亡與癌症分子生物學 |

---

## 🛠️ 技能架構規範 (Skill Architecture)

每個 Skill 均具備完整的自包含知識結構：
1. **`SKILL.md`**：核心能力宣告、路由分發、全書章節索引與問題解決啟發式決策樹（Token 數控制於 4,000 以內）。
2. **`chapters/`**：各章深度解構模組，統一採用 10 大標準區塊：
   - `Core Idea`（核心概念）
   - `Frameworks Introduced`（核心理論框架）
   - `Key Concepts`（關鍵名詞單句定義）
   - `Mental Models`（直觀思維模型）
   - `Anti-patterns`（高頻易混淆認知陷阱）
   - `Reference Tables`（生理參數矩陣、傳導路徑、比對表格）
   - `Worked Example`（生奧競賽級計算與生理病理推導）
   - `Key Takeaways`（必備結論要點）
   - `Connects To`（跨章節橫向概念網絡）
3. **`patterns.md`**：系統性分子調控與生理動態設計模式（Design Patterns）。
4. **`cheatsheet.md`**：高頻公式、常數、生理指標與抑制劑/藥理對照手冊。
5. **`glossary.md`**：A–Z 全書核心詞彙雙語對照解析。

---

## 🚀 安裝與配置 (Installation & Setup)

本儲存庫中的各技能遵循通用跨 Agent 標準規範（相容於 GitHub Copilot CLI、Claude Code、Hermes Agent、OpenCode、Google Antigravity 等）。

### 1. 安裝至跨 Agent 共享根目錄 (全系統推薦)
```bash
# 複製或建立符號連結至 ~/.agents/skills/
mkdir -p ~/.agents/skills
cp -r campbell-biology ~/.agents/skills/
cp -r taiz-plant-physiology ~/.agents/skills/
cp -r sherwood-human-physiology ~/.agents/skills/
cp -r cooper-cell-biology ~/.agents/skills/
```

### 2. 安裝至 Google Antigravity 配置目錄
```bash
# Windows PowerShell
Copy-Item -Recurse campbell-biology "$HOME\.gemini\config\skills\"
Copy-Item -Recurse taiz-plant-physiology "$HOME\.gemini\config\skills\"
Copy-Item -Recurse sherwood-human-physiology "$HOME\.gemini\config\skills\"
Copy-Item -Recurse cooper-cell-biology "$HOME\.gemini\config\skills\"
```

---

## 🔒 檢驗與品質保證 (Quality Assurance)
- **繁體中文審閱標準**：經自動化字元校驗，全庫包含 0 個簡體字符，符合台灣學術名詞規範。
- **安全掃描**：通過 `scan_generated_skill.py` 嚴格審計，無任何 Prompt Injection 或未授權指令風險。
