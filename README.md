# Living Squeek

A small companion app for Squeekchain holders. Your Squeek is a pixel creature that grows through five stages, and it only grows when the work behind it has settled on-chain. Live wheel readings are shown but never count.

Live site: https://dejagold123.github.io/Living-Squeek/

## What it does

- Look up any Squeek by token ID, or load every Squeek in a wallet (the "burrow").
- Shows whether a Squeek is asleep in a wallet or awake in staking.
- Prepares claim, merge and checkpoint calls as unsigned EIP-5792 bundles for your own wallet to sign.
- Makes a share card for any Squeek, all in the browser.

## Things worth knowing

- Sepolia testnet only. Test Squeeks and SQK have no monetary value.
- Independent project, not an official Squeekchain product. Built directly on the public API (Lane A, no IMD job).
- It never asks for a seed phrase or private key and never signs anything.
- Contract addresses come from the published `sepolia.json`, never from the API. If a deployment check fails, owner actions stop.
- If a live read fails, the page says "unknown" instead of showing zero.

## Run it

It's a single `index.html` with no build step. Open it in a browser, or serve the folder with any static host. On GitHub Pages: Settings, Pages, deploy from the `main` branch root.
