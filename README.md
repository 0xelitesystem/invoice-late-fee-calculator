# Invoice Late Fee Calculator

This tool calculates how many days an invoice is overdue, the interest accrued at an annual rate, any flat late fee, and the total now owed as of a chosen date. Interest is computed simply on the invoice amount, beyond an optional grace period.

**Live demo:** https://0xelitesystem.github.io/invoice-late-fee-calculator/

## What it does

Enter the invoice amount, the due date, and the date you are calculating for. Set a flat late fee, an annual interest rate, and a grace period if any. The tool returns days overdue, the interest accrued, the flat fee applied, and the total owed, stamped current or past due.

Interest here is simple: the annual rate reduced to a daily rate, multiplied by the days overdue past any grace period. Real agreements may compound or define terms differently, and late-fee and interest limits vary by place and contract.

## Aesthetic

A kraft-paper statement with a typewriter face and a rotated red double-ruled stamp that reads past due or current.

## Not financial advice

This tool performs arithmetic on the numbers you enter. It is not financial, tax, accounting, or legal advice, and it does not account for your specific circumstances. Verify any figure before acting on it.

## Privacy

Everything runs in your browser. Nothing you type is sent anywhere, stored, or saved. Closing the tab clears it.

## Use it

Open `index.html` in any modern browser, or host it as a static page. No build step, no dependencies, no network calls.

## License

MIT. Copyright (c) 2026 0xelitesystem.
