# RawEdge Deals

The simple affiliate links page for RawEdge: click a named casino, land on its current signup bonus, RawEdge earns its commission. No rankings, no reviews — those stay on rawedgecasinoreviews.com and are never for sale.

## Updating (monthly promos)
Edit `deals.json` only:
- Add a casino: add an entry to `casinos` (name, category, tags, affiliate `url`).
- Add a promo: add an entry to `promos` (casino, title, url, optional expires "YYYY-MM-DD").
- Listing order in the file is display order only — it is not a ranking.

## Rules
- Never print a bonus amount that has not been verified against the operator's current terms.
- Every outbound casino link keeps rel="sponsored noopener noreferrer".
- 18+ / responsible-gambling framing stays on the page.
