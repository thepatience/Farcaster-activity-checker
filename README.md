# Farcaster Mini App - Cartoon Airdrop Checker

This project is a playful mini app (Next.js) that estimates Farcaster airdrop potential by combining mocked Farcaster profile data and mocked Base on-chain activity.
It's designed to be deployed to Vercel and published as a Farcaster Frame.

## How to use

1. Unzip and open the project.
2. Replace mocks in `app/api/check/route.js` with real API calls (Warpcast / Farcaster indexer / Base RPC).
3. Update `app/api/frame/route.js` `target` field with your deployed URL.
4. Deploy to Vercel (connect GitHub repo) or run locally with:
   ```bash
   npm install
   npm run dev
   ```

## Make it real
- To fetch real Farcaster data, use a Farcaster indexer (Warpcast API) or community-run Hub indexing endpoint.
- For Base on-chain data, query the Base RPC or use a block explorer API.

