# SmartVal-AI Bahrain — Demo Starter

A polished, responsive Next.js dashboard for demonstrating real-estate investment analysis in Bahrain.

## Included
- Interactive Bahrain market dashboard
- Illustrative area comparison cards
- Editable investment assumptions
- Gross/net rental yield calculations
- Holding-period value projection
- Investor summary modal with Print / Save as PDF
- Responsive layout for mobile and desktop
- Clear disclosure that market data is illustrative, not verified live data

## Run locally
1. Install Node.js 20+.
2. Extract this folder.
3. Open a terminal in this folder and run:
   ```bash
   npm install
   npm run dev
   ```
4. Open http://localhost:3000

## Deploy on Vercel
1. Upload the project to a GitHub repository.
2. In Vercel, choose **Add New → Project** and import that repository.
3. Keep the framework preset as **Next.js**.
4. Click **Deploy**. No environment variables are needed for this demo.

## Important data note
The built-in figures are illustrative demo data. Do not present them as official Bahrain market prices or live transactions. Bahrain's Survey & Land Registration Bureau (SLRB) publishes open data, daily/live transaction statistics and reports:
- https://www.slrb.gov.bh/en/open-data
- https://www.slrb.gov.bh/en/live-statistics
- https://www.slrb.gov.bh/en/transaction-report

The Aqari real-estate databank may require account approval and subscription depending on access tier:
- https://aqari.rera.gov.bh/

Before production use, obtain data rights and confirm whether official data is downloadable or available through an approved API. Replace the illustrative arrays in `app/page.tsx` with a validated dataset, preserve source dates, and show a data freshness indicator. This starter does not claim to be a trained valuation model or live data integration.
