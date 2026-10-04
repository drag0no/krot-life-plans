# AGENTS.md — AI AGENT GUIDELINES & REPOSITORY INVARIANTS

This file provides non-negotiable instructions, domain invariants, and formatting constraints for any AI agent interacting with the `krot-life-plans` repository.

## 1. REPOSITORY PURPOSE & ARCHITECTURE

This repository contains the living relocation, fiscal engineering, and wealth preservation dossier for Pavel Krot, Anna Fediunina, and their family.

### File Structure & Reading Order
```text
krot-life-plans/
├── AGENTS.md                          <── AI operating instructions & invariants
├── 00_MASTER_STRATEGY.md              <── [Start Here] Executive strategy, profile, portfolio engine
├── 00A_JURISDICTION_COMPARISON.md      <── [Master Matrix] 6-jurisdiction comparative deep-dive
├── 01_PHASE_SINGAPORE.md              <── [Phase 1 Core] Runway overview, EP renewal, timeline
├── 01A_DOCUMENT_PROCUREMENT.md        <── [Phase 1 Annex] Master document readiness, apostilles, validity tracker
├── 01B_FEDOT_CAPITAL.md               <── [Phase 1 Annex] Corporate governance, balance sheet repair, strike-off
├── 02_PHASE_BRAZIL.md                 <── [Phase 2 Core] Childbirth, 1-yr naturalization, Law 14.754 tax proof
├── 03B_DESTINATION_PORTUGAL.md        <── [Option B: 8.5/10] D7 passive visa, 7-Yr CPLP EU citizenship
├── 03C_DESTINATION_CYPRUS.md          <── [Option C: 8.4/10] Cat 6.2 Lifetime PR, 0% Non-Dom trading tax
└── 03E_DESTINATION_UK.md              <── [Option E: 7.4/10] Global Talent Tech Visa, 3-Yr ILR, 4-Yr FIG
```

### File Naming & Modularization Rules
* **Sequential Lifecycle:** Chronological phases use two-digit prefixes: `00_` (Master Strategy), `01_` (Singapore Runway), `02_` (Brazil Springboard).
* **Auxiliary & Deep-Dive Appendices (`<Phase><Letter>_`):** When a phase file accumulates deep operational lists or exceeds ~200 lines, extract the material into a lettered appendix under that phase (e.g. `00A_JURISDICTION_COMPARISON.md`, `01A_DOCUMENT_PROCUREMENT.md`, `01B_FEDOT_CAPITAL.md`).
* **Parallel Destination Variants (`03B_`, `03C_`, `03E_`):** Competing settlement destinations sit under prefix `03` with letter suffixes indicating their comparative ranking order.

## 2. HARD FAMILY & FINANCIAL INVARIANTS

Every proposal, calculation, or edit must adhere to these fixed boundaries:

* **Principals:** Pavel Krot (15+ yrs low-latency/eFX quant architect), Anna Fediunina, newborn child. Currently Russian citizens; acquiring dual Brazilian citizenship via Brazil springboard.
* **Household Net Worth:** **SGD 1,500,000 – 1,700,000 (~€1.05M – €1.18M / ~\$1.15M – \$1.3M USD)**.
* **Portfolio Allocation Engine:**
  * **Liquid Cash Anchor:** Exactly **SGD 200,000 (~€140,000)** in unencumbered risk-free cash.
  * **Crypto Sleeve:** Strictly **30% to 35%** (~SGD 450k–600k / ~€315k–420k).
  * **Active Strategy & Bonds (Remainder):** **~SGD 800,000 – 950,000** deployed in Pavel's 15% CAGR quarterly rebalancing strategy (100% turnover every 90 days) + US Treasury bond ladders.
* **The 50% Real Estate Hard Ceiling:** Property acquisition in any settlement jurisdiction must **NEVER exceed 50% of net worth** (max budget: **€520,000 – €590,000 / ~SGD 750k–850k**). Minimum requirement: **3 bedrooms, 2 bathrooms**.
* **Master Timeline:**
  * Departure from Singapore: **Q3 2027**.
  * Brazil stay (childbirth, 1-yr naturalization, DIRPF tax filing): **Q3 2027 – late 2028**.
  * European settlement: **Late 2028 / Early 2029**.

## 3. JURISDICTION SUMMARY & RECENT FINDINGS

* **Hungary (Option A / 8.7 Rating — Top All-Rounder):** Analyzed in `00A_JURISDICTION_COMPARISON.md`. 10-Year Guest Investor permit via €500k property (tight at ~47% NW) or €250k fund. Flat 15% ETÜ trading tax (0% SZOCHO, loss netting). Full work & directorship access. BKK transit (10/10), Kifli.hu, sub-20 ms ping to Frankfurt. Lowest Russian banking friction in EU. Hungarian civics exam required for passport over 8-year runway (feasible as family is open to language study). Standalone destination file skipped for now.
* **Portugal (Option 03B / 8.5 Rating — EU Passport Pick):** D7 visa requires packaging trading profits into corporate dividends or bond coupons (consulates reject *mais-valias*). Flat 28% trading tax. Full local work rights permitted under D7. Preferred for full EU passport in 7 years under *Lei Orgânica n.º 1/2026* (Brazilian nationality waives CIPLE A2 language exam).
* **Cyprus (Option 03C / 8.4 Rating — Top Capital & Passive PR):** €300,000 (+VAT) new property gives immediate Lifetime PR in 2–3 months. 17-Year Non-Dom gives 0% tax on securities/derivatives trading. Requires 1-day visit every 2 years. Zero conscription if maintaining Category 6.2 PR with Brazilian passports. Note: Category 6.2 PR strictly prohibits domestic employment in Cyprus.
* **Belgium (Option D / 7.7 Rating — LNG & Corporate Peak):** Analyzed in `00A_JURISDICTION_COMPARISON.md`. S-Tier match for Anna (direct prior relationship with Fluxys at Zeebrugge LNG terminal, fluent French DELF B2). Larian Studios in Ghent and sub-10 ms Amsterdam ping for Pavel. Fast 5-year EU passport. Requires corporate Single Permit sponsorship (no passive visa); 33%–50% risk on active quant trading.
* **United Kingdom (Option 03E / 7.4 Rating — Tech Track):** Tech Nation Global Talent visa. Unrestricted open-market work rights. 3-Year fast-track ILR. 4-Year FIG regime (0% tax on foreign gains for 4 years). London 3-bed property (£650k–£900k) violates 50% NW cap, forcing family to rent (£2.8k–£3.5k/mo) or buy in commuter towns.
* **Poland (Option F / 7.8 Rating — GameDev & LNG Gateway):** Analyzed in `00A_JURISDICTION_COMPARISON.md`. Europe's #2 GameDev hub for Pavel (CD Projekt, Techland) + Świnoujście LNG terminal & Gdańsk FSRU for Anna. Flat 19% tax (*podatek Belki*). Full work access. Sub-25 ms ping. Requires Brazilian passports to buffer Polish consular scrutiny.
* **Discarded Nations:**
  * *Malta:* Discarded due to €70k non-refundable state fees.
  * *Uruguay:* Discarded per user direction.
  * *Montenegro:* Discarded (property yields 1-year temporary visa that legally never leads to PR under Art. 86; naturalization strictly forbids dual citizenship under Art. 8).

## 4. AGENT OPERATING RULES: DO'S AND DON'TS

### DO:
* **DO keep cross-file links strictly relative:** Use `[01_PHASE_SINGAPORE.md](01_PHASE_SINGAPORE.md)` or `[01A_DOCUMENT_PROCUREMENT.md](01A_DOCUMENT_PROCUREMENT.md)`. Never use `file:///` or absolute local drive paths.
* **DO format currency and math with LaTeX KaTeX:** Use `\$` for literal dollar signs to avoid KaTeX parsing errors (e.g. `\$1.5M SGD`). Use `$ ... $` for inline math equations.
* **DO preserve legal and tax specificity:** Always cite precise legislation (e.g., Lei 13.445/2017 Art. 65, Lei Orgânica 1/2026, UK Appendix Global Talent, Cyprus Category 6.2, Brazil Law 14.754, Hungary Act XC of 2023).
* **DO maintain the Singapore 8-year efficiency benchmark:** Evaluate lifestyle infrastructure against high-density transit (BKK/MRT), digital governance (Singpass/GOV.UK), and multi-day chilled macro meal prep (Nutrition Kitchen SG benchmark).
* **DO account for dual citizenship requirements:** Acknowledge that Pavel and Anna retain Russian citizenship alongside Brazilian passports; ensure police certificates from Russia, Singapore, and Brazil are factored into document roadmaps.

### DON'T:
* **DON'T run `git commit`:** The user has explicitly mandated **NO COMMITS**. Keep all file edits uncommitted in the working tree.
* **DON'T use `---` horizontal rule splitters:** The user explicitly instructed to remove all `---` dividers from markdown files. Use clean whitespace and headers (`##`, `###`) for sectioning.
* **DON'T run complex PowerShell scripts:** Avoid executing complex loops or regex multi-file replacement scripts via shell commands. Use direct tool inspection and file edits.
* **DON'T exceed the 50% net worth real estate cap:** Never recommend properties exceeding SGD 850k (~€520k / ~£490k).
* **DON'T confuse temporary residence with permanent residence (PR):** Distinguish sharply between renewable temporary visas (Greece, Montenegro, Hungary) and direct lifetime PR (Cyprus Category 6.2, Malta MPRP).
