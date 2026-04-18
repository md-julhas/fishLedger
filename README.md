# Overview

**FishLedger** approximately saves 85% of time and significantly reduces manual errors by automating the entire local fish sales workflow—including the traditional local term “Mon” pricing system—replacing pen-and-paper recordkeeping and manual calculations.

In the **traditional method**, sellers spend significant time and effort:

- For every different size item of “Hilsa Fish”, they use a standard calculator and manually enter the full formula:`(mon price / 40) × (mon amount × 40 + kg + 0.gram)` They repeat the calculation 2–3 times to avoid mistakes.
- They write every item weight and price on paper.
- They manually calculate the total price of all Hilsa items.
- They separately calculate the total weight by summing mon + kg + gram across all Hilsa items, manually performing carry-over conversions (grams → kilograms → mon).
- They also calculate the total of other types of mixed fish container prices separately.

**With this app, the entire process is automated and simplified:**

1. Enter the values once per item: (For Mix Fish: price), (For Hilsa Fish: mon price, kg, and gram).
2. Tap **Save**.
3. Tap **Report**.

All calculations—including individual item pricing, weight conversions, total summations, and grand totals—are performed instantly and accurately.

## Features and Benefits

- **Zero calculation errors** — the app uses exact math (1 mon = 40 kg = 40,000 grams).
- **Completely paperless** — no pen, no notebook, no loose papers.
- **Works 100% offline** — perfect for wholesale markets or boats with no internet.
- **Runs like a native mobile app** — just open `index.html` on your phone or tablet.
- **Data saved automatically** — uses browser LocalStorage (nothing is lost until you delete it).
- **Professional PDF reports** — download structured tables of records, fully available offline after the first-time online run (no internet required afterward).
- **Easy to edit or delete** any item anytime.
- **Eye-catching modern UI** — designed specifically for boat owners and local sellers, making it simple and intuitive even for non-technical users.

### Report Screen (One-Tap Summary)

- **Every Hilsa size item record** — includes buyer name, mon price, detailed weight breakdown (mon–kg–gram), and automatically calculated item total price, along with consolidated totals of all item weights and prices for complete summary reporting.

- **All Mix Fish records** — includes buyer name, individual item prices, and automatically calculated item totals.

- **Edit / Delete buttons for each item** — allowing users to quickly modify or remove any individual record with ease and full control over data accuracy.

- **Grand Total** — automatically calculates the combined total of all Mix Fish and Hilsa items for a complete final summary.

- **Download PDF** — generate and export a complete structured report of all recordkeeping data for easy sharing, printing, and offline storage.

- **Clear All Data** — safely removes all stored records after a confirmation prompt, preventing accidental data loss.

## How to Use

2. Open `index.html` file in any web browser.
3. Start adding items.
4. Go to **Report** anytime to see live totals and download PDF.

## Tech Stack

- **HTML5**
- **CSS3**
- **Vanilla JavaScript (ES6)**
- **Local Storage API**
- **jsPDF**

No more calculator mistakes. No more paper. Just fast, accurate, professional fish sales.
