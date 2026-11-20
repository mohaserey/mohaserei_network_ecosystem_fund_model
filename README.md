# mohaserei_network_ecosystem_fund_model
Mohaserei System Network (MSN) — Ecosystem Fund Model (mohaserei_network_ecosystem_fund_model)

The Mohaserei Ecosystem Fund Model (mohaserei_network_ecosystem_fund_model/index.html) is a standalone, single-file interactive treasury simulator for the Mohaserei System Network (MSN). It models capital allocation across four core fund tranches, projects liquidity reserves and community UES/HCV yield, distributes allocations across Cambodia's 25 provinces and capital, and tracks tranche deployment milestones from 2026 to 2032.

Key Capabilities

Scenario Presets & Real-Time Allocation Controls:

Switch between Conservative ($60.00M pool, 45% release), Baseline ($120.00M pool, 65% release), and Expansion ($260.00M pool, 85% release) presets.

Tune total pool size ($10M–$500M), tranche weights (Growth & Infra, UES & Grants, MSN Liquidity, and Governance & Sec), target horizon (2026–2032), and tranche release rate (15%–100%), with a one-click Balance 100% action.

Live KPIs & Dual HTML5 Canvas Visualizers:

Displays live metrics for Total Fund Pool, Allocated Capital vs. unallocated buffer, Projected Liquidity Reserve, and annualized Community & UES Yield.

Renders a Capital Allocation & Tranche Distribution bar chart and a Multi-Year Fund Deployment & Reserve Trajectory (2026–2032) chart with hover and touch tooltips.

25-Region Cambodian Distribution Matrix:

Covers Phnom Penh and all 24 Cambodian provinces with Khmer (Kantumruy Pro) and English names, regional allocation weights, commune/sangkat counts, and UES/HCV grant shares.

Supports search filtering, dropdown selection, and interactive province focus cards.

Tranche & Deployment Schedule Ledger:

Filterable and searchable milestone ledger displaying each tranche's window, pool share, allocated USD, horizon-released amount, and status (ACTIVE, SCHEDULED, LOCKED).

Bilingual UI (ខ្មែរ / EN), Voice Briefs & JSON Export:

Switch between English (EN) and Khmer (ខ្មែរ), trigger a spoken summary via the Web Speech API (speechSynthesis) with toast fallbacks, persist state in localStorage under msn_fund_model_state_v1, and export timestamped JSON snapshots (Export JSON).

Running Locally

Open index.html directly in a modern browser or serve it over a local HTTP server:

python3 -m http.server 8080



Then open http://localhost:8080/mohaserei_network_ecosystem_fund_model/index.html.

Ecosystem Integration Notes

Keep the exact spelling Mohaserei across all documentation, datasets, and modules.

Connect loadState / saveState, tranche parameters, and regional weights to verified Mohaserei treasury and regional grant data sources when moving beyond local modeling.
