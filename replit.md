# CoinHunters Explorer

CoinHunters Explorer is a blockchain explorer, wallet, and toolkit for the Cosmos ecosystem, branded for CoinHunters (coinhunterstr.com).

## Branding
- **Logo**: CoinHunters logo (coinhunters-logo.webp)
- **Colors**: Red (#ED1C24), Orange (#F06524), Blue (#007BFF), Black (#222222), Gray (#666666), Light (#F8F8F8)
- **Theme**: Single consistent light theme (no dark mode toggle)
- **Social Links**: Twitter (@AnadoluKripto), Telegram (AnadoluKripto), Website (coinhunterstr.com)

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
