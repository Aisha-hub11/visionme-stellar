# Project

A starter workspace with a Next.js web app and Stellar Sororan smart contracts.

## Prerequisites

- Node.js 18 or later
- pnpm

## Installation

```bash
pnpm install
```

## Environment Variables

Copy the example env file and fill in the required values:

```bash
cp apps/web/.env.example apps/web/.env.local
```

### Frontend (`apps/web`)

| Variable | Description |
| --- | --- |
| `NEXT_PUBLIC_SUPABASE_URL` | Supabase project URL |
| `NEXT_PUBLIC_SUPABASE_ANON_KEY`. | Supabase anon key |
| `NEXT_PUBLIC_SUPABASE_SERVICE_ROLE_KEY` | Supabase service role key |
| `NEXT_PUBLIC_STELLAR_NETWORK` | Stellar network (e.g. `testnet`) |
| `NEXT_PUBLIC_STELLAR_ROPC_URL` | Stellar Sororan RPC URL |
| `NEXT_PUBLIC_STELLAR_HORIZON_URL` | Stellar Horizon URL |
| `NEXT_PUBLIC_STELLAR_PASSWORD` | Stellar account password |
| `NEXT_PUBLIC_STELLAR_SECRET` | Stellar account secret |
| `NEXT_PUBLIC_APP_ENV` | App environment (e.g. `development`) |
| `NEXT_PUBLIC_APP_NAME` | App name |
| `NEXT_PUBLIC_APP_URL` | App URL |
| `NEXT_PUBLIC_WALLETCONNECT_PROJECT_ID` | WalletConnect project ID |
| `NEXT_PUBLIC_CANON_CONTRACT_ID` | Canon contract ID |
| `NEXT_PUBLIC_CROSSMINT_API_KEY` | Crossmint API key |
| `NEXT_PUBLIC_PINKET_CONTRACT_ID` | Pinket contract ID |
| `NEXT_PUBLIC_SBT_CONTRACT_ID` | SNT contract ID |
| `NEXT_PUBLIC_INCREMENT_BINDING` | Increment binding |
| `HELLO_WORLD_BINDING` | Hello World binding |

## Development

```bash
pnpm dev
```

## Build

```bash
pnpm build
```

## Test

```bash
pnpm test
```
