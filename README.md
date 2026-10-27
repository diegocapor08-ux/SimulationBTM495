# ShopDesk – Small Business Manager (prototype)

Working prototype for the BTM 495 team project (Concordia University, JMSB, Fall 2026).

**Live preview:** enabled through GitHub Pages — see *Settings → Pages* for the link once it is turned on.

## What's in here

| File | Purpose |
|---|---|
| `index.html` | The whole prototype: HTML, CSS and JavaScript in one file. No build step. |
| `.nojekyll` | Tells GitHub Pages to serve the file as-is. |

## Running it locally

Open `index.html` in any browser. Data is stored in the browser's `localStorage`, so each person sees their own copy. Use **Reset sample data** (top right) to restore the demo data, or **Clear all data** to test empty screens.

## Sub-systems covered

Dashboard · Sales · Inventory (with restock alerts) · Reports · Suppliers and customers · Accounting · Scheduling · Customer support (complaints, requests, returns).

Class names in the code follow the team's class diagram (Store, StoreOwner, Employee, Product, InventoryRecord, RestockAlert, Sale, SaleItem, Customer, Supplier, PerformanceRecord, Ledger/Transaction, BudgetThreshold, Schedule, EmployeeShift, ComplaintCase, SupportRequest, ReturnRequest, ReportFilter, DashboardSummary).

## How the team works on it

1. Pull the latest version before editing.
2. Make one focused change per commit, with a clear message (e.g. `Inventory: add expiry filter`).
3. Push to `main`; the live preview updates within a minute or two.

Commit history doubles as evidence of each member's contribution for peer evaluation.
