<div align="center">
    <h1>GitCode-v2</h1>
    <strong>Tech stack: Next.js 13, React, Tailwind, ICP, Chainlink</strong>
</div>
<br>
<div align="center">
    <a href="">
        <img src="https://therealsujitk-vercel-badge.vercel.app/?app=gitcode-v2" alt="Vercel">
    </a>
     <a href="https://gitpod.io/#">
        <img src="https://img.shields.io/badge/setup-automated-blue?logo=gitpod" alt="Gitpod">
    </a>
     <a href="https://twitter.com/Aditya04183">
        <img src="https://img.shields.io/twitter/follow/Aditya04183?style=social" alt="Aditya Singh Twitter">
    </a>
</div>
<div align="center">
    <br>
    <a href="https://www.adityasingh.live/"><b>Visit »</b></a>
    <br>
</div>

## Overview

GitCode-v2 is a Next.js application for discovering sponsor projects and browsing on-chain bounties. The UI includes dedicated pages for featured projects, open bounties, and creating or claiming bounty submissions.

## Tech Stack

- Next.js 13
- React 18
- Tailwind CSS
- Ethers.js
- Hardhat
- Chainlink
- ICP

## Getting Started

### Prerequisites

- Node.js 18+
- npm, yarn, or pnpm

### Install dependencies

```bash
npm install
```

### Run the development server

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

## Available Scripts

- `npm run dev` — start the Next.js development server
- `npm run build` — create a production build
- `npm run start` — start the production server
- `npm run lint` — run contract linting, Prettier checks, and Next.js linting
- `npm run test` — run the unit test suite
- `npm run compile` — compile Hardhat contracts

## Project Structure

- `src/pages/` — Next.js routes for the landing page, bounties, projects, and flows such as create/apply/claim
- `components/` — reusable UI sections and page components
- `contracts/` — smart contract sources and generated artifacts used by the app
- `libs/` — task helpers, contract utilities, and supporting scripts
- `public/` — static assets and project images

## Notes

- The homepage currently announces GitCode-v3 as "Coming Soon..." while this repository contains the GitCode-v2 codebase.
- The bounties page reads blockchain data via `RPC_URL` and `PRIVATE_KEY` environment variables.

## Learn More

- [Next.js Documentation](https://nextjs.org/docs)
- [Hardhat Documentation](https://hardhat.org/docs)
- [Chainlink Documentation](https://docs.chain.link/)
