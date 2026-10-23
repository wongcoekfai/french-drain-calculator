# French Drain Calculator

Free french drain calculator: enter trench length, width and depth to get gravel
volume (cubic yards / tons / bags), perforated pipe length and filter fabric area.
Imperial and metric units. No sign-up, instant results.

Live: https://french-drain-calculator.app.workbuddy.host/?sharecode=XWTADL6CH4 (preview)
Production: https://draincalc.net (planned)

## Stack

- Pure static HTML + vanilla JS — zero build, zero dependencies
- Single page, ~8 KB, mobile-first
- SEO: WebApplication + FAQPage JSON-LD schema, canonical, meta description

## Deploy (Cloudflare Pages)

1. Push this repo to GitHub
2. Cloudflare Dashboard → Workers & Pages → Create → Pages → Connect to Git
3. Select this repo → Framework preset: **None** → Build command: *(empty)* →
   Build output directory: `/` → Deploy
4. Add custom domain in Pages project settings

## Related calculators (roadmap)

- Gravel Calculator for French Drain
- Pipe Slope Calculator
- Dry Well Sizing Calculator
- Catch Basin Calculator

## Disclaimer

Results are planning estimates only. Gravel density varies by quarry; always
verify quantities with your supplier and call 811 (US) before digging.
