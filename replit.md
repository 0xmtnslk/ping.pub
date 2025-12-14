# CoinHunters Explorer

CoinHunters Explorer is a blockchain explorer, wallet, and toolkit for the Cosmos ecosystem, branded for CoinHunters (coinhunterstr.com).

## Branding
- **Logo**: CoinHunters logo (coinhunters-logo.webp)
- **Colors**: Red (#ED1C24), Orange (#F06524), Blue (#007BFF), Black (#222222), Gray (#666666), Light (#F8F8F8)
- **Theme**: Single consistent light theme (no dark mode toggle)
- **Social Links**: Twitter (@CoinHuntersTR), Telegram (CoinHuntersTR), Website (coinhunterstr.com)

## Project Structure
- `explorer/` - Main Vue 3 + Vite application
- `chains/` - Blockchain configuration files
  - `mainnet/` - Mainnet chain configurations (129 chains)
  - `testnet/` - Testnet chain configurations (78 chains)
- `logos/` - Chain logo assets

## Technology Stack
- **Framework**: Vue 3 with Composition API
- **Build Tool**: Vite 4.x
- **Package Manager**: Yarn 1.x
- **Styling**: Tailwind CSS + DaisyUI (custom coinhunters theme)
- **State Management**: Pinia
- **Language**: TypeScript

## Key Features
- Mainnet/Testnet network separation with tabs
- Modern card-based UI design
- Featured blockchains section
- Chain search functionality
- Multi-language support (i18n)

## Complete UI Redesign (December 2025)

### Navigation System
- **Top Navigation**: Horizontal navbar with logo, chain profile, social links, search, wallet
- **Chain Tabs**: Secondary tab bar appears only on chain pages (Dashboard, Governance, Staking, Blocks, Transactions, Uptime)
- **No Sidebar**: Clean full-width layout

### Design System
- **Primary Gradients**: Red (#ED1C24) to Orange (#F06524)
- **Dark Hero Sections**: slate-900 to slate-800 with glassmorphism effects
- **Card Styling**: rounded-3xl, shadow-sm, border-slate-100, hover effects
- **Stats Cards**: Colored gradients (emerald, blue, purple, amber)
- **Typography**: Bold headings, semibold labels, slate color palette

### Modernized Components
- **DefaultLayout**: Top horizontal navbar with chain-specific tabs
- **Homepage**: Centered hero with stats, Mainnet/Testnet tabs, no Featured Chains
- **Chain Dashboard**: Dark slate hero, price/market stats, modern wallet section, governance proposals
- **Staking Page**: Gradient header, featured validators cards, styled tables
- **Governance Page**: Gradient header, styled tabs with counts, modern proposal cards
- **Uptime Page**: Purple gradient header, uptime bars, validator cards
- **ProposalListItem**: Card-based design, status badges, voting buttons
- **ArrayObjectElement**: Modern table styling with hover states and scrollbar

## Development
```bash
cd explorer && yarn dev
```
Server runs on port 5000.

## Build
```bash
cd explorer && yarn build
```

## Deployment
Static site deployment:
- Build: `cd explorer && yarn build`
- Public directory: `explorer/dist`
