This is NFT Marketplace built on Stacks using [Next.js](https://nextjs.org) project bootstrapped with [`create-next-app`](https://nextjs.org/docs/app/api-reference/cli/create-next-app).

## Getting Started

First, run the development server:

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
# or
bun dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

You can start editing the page by modifying `app/page.tsx`. The page auto-updates as you edit the file.

This project uses [`next/font`](https://nextjs.org/docs/app/building-your-application/optimizing/fonts) to automatically optimize and load [Geist](https://vercel.com/font), a new font family for Vercel.

## Setup Devnet
### Start Devnet in the Platform
1. Login to the Platform and start the devnet on the nft-marketplace project.
2. Use the contracts/nft-marketplace.clar file content and replace the existing content in the contracts/nft-marketplace.clar file in the nft-marketplace project.
3. Add also the contracts/funny-dog.clar file content to the contracts folder in the nft-marketplace project.
4. Deploy the contracts to the devnet by clicking on the Deploy Contracts button 


### Configure the Front-End
1. In the Platform web app, go to the API Keys page and get the API Key.
Add your Platform API Key to the .env file to the variable NEXT_PUBLIC_PLATFORM_HIRO_API_KEY
This will automatically configure the application to use the platform hosted devnet that is currently running.
The devnet wallet will be then used to execute the contract calls.
