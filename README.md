# NOVA-EVENT-DRIVEN-AUTONOMOUS-TRADING-AGENT

> **"WHEN THE EVENT HITS, NOVA MOVES."**

NOVA is an event-driven AI trading agent designed as an institutional intelligence terminal combined with an autonomous decision engine. 

Presented through an austere, **Minimalist Monochrome** editorial interface, NOVA demonstrates that an LLM should not merely summarize financial headlines—it acts as the **reasoning layer within a disciplined quantitative transmission chain**.

---

## The Core Workflow

$$\mathbf{EVENT} \longrightarrow \mathbf{INTERPRET} \longrightarrow \mathbf{IMPACT} \longrightarrow \mathbf{DECIDE} \longrightarrow \mathbf{RISK} \longrightarrow \mathbf{EXECUTE} \longrightarrow \mathbf{LOG}$$

1. **EVENT**: Ingests macroeconomic telemetry (CPI, PPI, FOMC, NFP, GDP, Retail Sales, Geopolitical Shocks).
2. **INTERPRET**: Extracts metrics, compares actual vs expected consensus, and computes normalized statistical surprise.
3. **IMPACT**: Models macroeconomic transmission and cross-asset propagation across USD, Treasuries, Equities, and Digital Assets.
4. **DECIDE**: Generates **LONG**, **SHORT**, or **WAIT** directives alongside calibrated confidence scores.
5. **RISK**: Evaluates an independent **5-point risk gate** (Signal, Market, Liquidity, Risk Hurdle, Exposure).
6. **EXECUTE**: Routes orders to Simulation, Paper, or Live environments with deterministic stop-losses and profit targets.
7. **LOG**: Records an auditable forensic equation: $\text{Event} \times \text{Market} \times \text{Risk} = \text{Decision}$.

---

## Design System: Minimalist Monochrome

NOVA strictly implements an institutional, architectural aesthetic:

- **Absolute Monochrome Palette**:
  - `BLACK`: `#000000`
  - `WHITE`: `#FFFFFF`
  - `MUTED`: `#F5F5F5`
  - `MUTED TEXT`: `#525252`
  - `LIGHT BORDER`: `#E5E5E5`
  - *Strict Rule: Absolutely zero blue, green, red, purple, orange, or decorative color gradients. LONG, SHORT, and WAIT are communicated through typography, symbols (`↑`, `↓`, `—`), borders, spacing, and inversion.*
- **Zero Border Radius**: Pure geometric rectangles (`border-radius: 0px` on all buttons, badges, tables, modals, and inputs).
- **Zero Box Shadows**: Depth is created exclusively via line weights, black/white inversion, and negative space.
- **Typography Hierarchy**:
  - **Display**: *Playfair Display* (Editorial headlines & massive statements)
  - **Body**: *Source Serif 4* (Institutional reasoning & economic transmission)
  - **Technical**: *JetBrains Mono* (Quant metrics, tables, timestamps, logs, and live tape)
- **Signature Dividers**: 4px & 8px solid black structural rules punctuated with square punctuation boxes (`■`).
- **Tactile Texture**: Ultra-subtle hairline process grid overlay (2% ink density).

---

## Application Structure & Routes

```
/                   Editorial Landing Page & 7-Stage Workflow Manifesto
/terminal           Institutional Trading Terminal (Hero Event, Chain, Impact, Risk, Tape)
/events             Global Macro Release Directory & Filter
/events/[id]        Detailed Macro Event Intelligence & Transmission Matrix
/decisions          Auditable Decision Journal
/decisions/[id]     Forensic Decision Detail (Event * Market * Risk = Decision)
/portfolio          Capital Ledger & Monochrome Geometric Risk Allocation Bars
/replay             Historical Event Replay Engine (Multi-Speed Step Forensic Player)
/settings           System Risk Controls, Confidence Sliders, & Mode Toggles
```

---

## Key Features

### 1. Primary Terminal (`/terminal`)
- **Dominant Hero Event**: Highlighting release time, category, Actual, Expected, Previous, and Surprise metrics with bold editorial declarations (e.g., *"HIGHER THAN EXPECTED"*).
- **What Happened? & What Does It Mean?**: Authoritative breakdowns explaining structural inflation drivers and monetary policy reaction functions.
- **Macro Reasoning Chain**: Signature 6-step causal transmission diagram:
  $$\text{CPI +0.2\%} \to \text{INFLATION ABOVE EXP} \to \text{HIGHER FOR LONGER} \to \text{REAL YIELDS } \uparrow \to \text{RISK ASSETS } \downarrow \to \text{BTC SHORT}$$
- **Cross-Asset Impact Matrix**: Intermarket mapping across `BTC/USDT`, `ETH/USDT`, `NASDAQ 100`, `USD / DXY`, `US 10Y TREASURIES`, and `TOKENIZED EQUITIES`.
- **AI Decision Engine**: Autonomous recommendation (**LONG / SHORT / WAIT**). *WAIT is treated as a first-class decision* whenever edge or symmetry is absent.
- **Independent 5-Point Risk Gate**:
  - `SIGNAL VALIDATION` [✓]
  - `MARKET ALIGNMENT` [✓]
  - `LIQUIDITY DEPTH` [✓]
  - `PORTFOLIO RISK HURDLE` [✓]
  - `AGGREGATE EXPOSURE` [✓]
  - *Visually enforces that NOVA will not trade on AI conviction alone.*
- **Order Execution Panel**: Mode toggling (`SIMULATION`, `PAPER`, `LIVE`) with a strict pre-execution confirmation modal detailing exact Entry, Stop, Target, Position Size, and Max Loss.
- **Live Trade Tape & Agent Trace**: Real-time ticker and collapsible step-by-step forensic reasoning terminal.

### 2. Historical Event Replay (`/replay`)
- Re-run historical macro catalysts (CPI Inflation Shock, PPI Dovish Beat) as if they just occurred.
- Forensic playback engine with `PLAY`, `PAUSE`, `STEP`, `RESET`, and speed controls (`1x`, `2x`, `4x`).
- Demonstrates the sub-second progression:
  $$\text{Event Released} \to \text{Surprise Detected} \to \text{Macro Model Updated} \to \text{Impact Calculated} \to \text{Risk Gate Passed} \to \text{Signal Emitted} \to \text{Order Filled}$$

### 3. Auditable Decision Journal (`/decisions`)
- Permanent, searchable archive of every autonomous directive and execution.
- Detail page visualizes the institutional audit equation:
  $$\mathbf{EVENT} \times \mathbf{MARKET} \times \mathbf{RISK} = \mathbf{DECISION}$$

### 4. Geometric Risk Allocation (`/portfolio`)
- Account equity, cash buffer, open risk utilization, and daily P&L.
- Linear risk-density bars rendered using geometric unicode blocks (`██████████`) avoiding colorful donut charts.
- Active positions ledger with live unrealized P&L and single-click position closing.

### 5. Event Simulation Lab (`SIMULATE EVENT` Modal)
- Launchable from any screen via the navigation bar.
- Choose from standard presets (*CPI Spike, FOMC Shock Hike, PPI Cooling, NFP Beat, GDP Contraction*) or input a custom macro release to observe NOVA's real-time reasoning and execution gating.

---

## Tech Stack

- **Framework**: Next.js 15+ (App Router, Turbopack)
- **Language**: TypeScript (Strict Mode)
- **Styling**: Tailwind CSS with custom monochrome design tokens
- **Typography**: `next/font/google` (*Playfair Display*, *Source Serif 4*, *JetBrains Mono*)
- **Icons**: Lucide React (Strict monochrome, 1.5px stroke)
- **State Architecture**: Reactive React Context with live telemetry recalculation

---

## Getting Started

### Prerequisites
- Node.js 18.18+ or 20+ (Node 24+ supported)
- npm, pnpm, or yarn

### Installation

```bash
# 1. Clone the repository
git clone https://github.com/your-username/nova.git
cd nova

# 2. Install dependencies
npm install

# 3. Start development server
npm run dev
```

Open [http://localhost:3000](http://localhost:3000) in your browser.

### Production Build

```bash
# Build the optimized production bundle
npm run build

# Start the production server
npm run start
```

---

## Project Structure

```
nova/
├── public/
├── src/
│   ├── app/
│   │   ├── globals.css           # Monochrome tokens, 0px radius, texture, focus states
│   │   ├── layout.tsx            # Root layout with Google Fonts & TerminalProvider
│   │   ├── page.tsx              # Editorial Manifesto & Landing Page
│   │   ├── terminal/page.tsx     # Primary Trading Terminal
│   │   ├── events/               # Events directory & [id] detail pages
│   │   ├── decisions/            # Auditable Decision Journal & [id] detail pages
│   │   ├── portfolio/page.tsx    # Portfolio & Geometric Risk Allocation
│   │   ├── replay/page.tsx       # Historical Event Replay Suite
│   │   └── settings/page.tsx     # Risk Guardrails & Mode Governance
│   ├── components/
│   │   ├── common/SectionRule.tsx# 4px/8px rule with square punctuation box
│   │   ├── navigation/TopNav.tsx # Institutional top bar & mode toggles
│   │   └── terminal/             # HeroEvent, ReasoningChain, ImpactMap,
│   │                             # DecisionEngine, RiskEngine, ExecutionPanel,
│   │                             # LiveTradeTape, AgentTrace, SimulationModal
│   ├── context/
│   │   └── TerminalContext.tsx   # Reactive state management for events & portfolio
│   ├── lib/
│   │   ├── data.ts               # Macro dataset, historical decisions, replay steps
│   │   └── engine.ts             # Deterministic quantitative reasoning engine
│   └── types/
│       └── index.ts              # TypeScript interfaces
├── tailwind.config.ts            # Strict monochrome tokens and 0px radii
├── tsconfig.json
├── package.json
└── README.md
```

---

## License

MIT License. Designed for institutional intelligence research, algorithmic agent prototyping, and quantitative hackathon demonstrations.

