# Metal Build Demo

This guide is for developers setting up a tokenized NextJS app using the [metal.build](https://metal.build) API. 

## Example

- Example site: [facecoin.world](https://facecoin.world)

## Prerequisites

- [pnpm](https://pnpm.io/installation) (`npm install -g pnpm@latest-10`)
- Vercel CLI (`pnpm i -g vercel`)

## Dependencies

- [Privy](https://www.privy.io/) - Wallet management
- [Replicate] - AI image generator
- [Prisma DB] - Storage (vercel hosted)
- [Neynar] - Farcaster auth support
- [Twitter] - Twitter auth support

## Initial Setup

1. Clone the repository:

   ```bash
   git clone git@github.com:0xmetropolis/metal-build-demo.git
   cd metal-build-demo
   ```

2. Install dependencies:

   ```bash
   pnpm i
   ```

3. Link to a Vercel project:

   ```bash
   vercel link
   ```

4. Pull environment variables:

   ```bash
   vercel env pull
   ```

## Development

Start the development server:

- Using VSCode: Press F5 to start with debugger
- Using CLI: `pnpm run dev`

The app will be available at `http://localhost:3000`
