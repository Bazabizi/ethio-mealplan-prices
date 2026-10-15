# MealPlan ET price feed

Daily food prices for Addis Ababa, published as static JSON for the MealPlan ET app.
Built automatically every evening. Do not edit by hand.

| File | Who reads it |
|---|---|
| `test/prices.json` | Test builds of the app. May contain sample (placeholder) prices, marked `"_fixture": true`. |
| `prices.json` | Store builds. Real data only (not published yet). |

## Sources and attribution
- **Market prices: Addis Ababa City Administration Trade Bureau** (aaminfo.gov.et), daily retail prices.
- **Estimated prices: World Bank Real Time Food Prices**, CC BY 4.0.

See `ATTRIBUTION.txt` next to each feed.
