# Ping Dashboard

Ping Dashboard is a blockchain explorer, wallet, and toolkit for the Cosmos ecosystem.

## Project Structure

- `explorer/` - Main Vue 3 + Vite application (submodule from ping-pub/explorer)
- `chains/` - Blockchain configuration files
  - `mainnet/` - Mainnet chain configurations (JSON files)
  - `testnet/` - Testnet chain configurations (JSON files)
- `logos/` - Chain logo assets
- `scripts/` - Utility scripts

## Technology Stack

- **Framework**: Vue 3 with Composition API
- **Build Tool**: Vite 4.x
- **Package Manager**: Yarn 1.x
- **Styling**: Tailwind CSS + DaisyUI
- **State Management**: Pinia
- **Language**: TypeScript

## Development

The development server runs on port 5000 with the workflow "Ping Dashboard":
```bash
cd explorer && yarn dev
```

## Build

```bash
cd explorer && yarn build
```

## Configuration

- Vite config: `explorer/vite.config.ts`
- Chain configs are copied from root `chains/` directory to `explorer/chains/`

## Deployment

Configured as a static site deployment with:
- Build command: `cd explorer && yarn build`
- Public directory: `explorer/dist`
