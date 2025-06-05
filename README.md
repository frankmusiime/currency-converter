#  Currency Converter Web App

A simple and lightweight currency converter built with **pure HTML, CSS, and JavaScript** — all in a single file. Users can convert between predefined currencies instantly in their browser without any setup or server.

---

## File Included

- `index.html` – A single standalone file containing:
  - HTML structure
  - Embedded CSS for styling
  - Embedded JavaScript for conversion logic

---

## How to Use

1. Download or clone this repository.
2. Open the `index.html` file in any modern web browser (Chrome, Firefox, Edge, etc.).
3. Select the currencies you want to convert **from** and **to**.
4. Enter an amount.
5. Click **Convert** to see the result.

---

## Features

- Predefined currency exchange rates
- Clear dropdowns with a default “Choose Currency” option
- Form validation to prevent errors
- Clean and responsive interface
- Works entirely offline — no external libraries or APIs

---

## Currency Rates Used

Rates are based on **USD as the reference (1.0)**.

| Currency | Code | Rate    |
|----------|------|---------|
| US Dollar | USD | 1.0     |
| Japanese Yen | JPY | 113.5  |
| Euro | EUR | 0.89    |
| Russian Ruble | RUB | 74.36   |
| British Pound | GBP | 0.74    |
| Rwandan Franc | RWF | 0.00086    |
| NRA (Custom) | NRA | 1200    |
| SHL (Custom) | SHL | 2900    |

---

## Conversion Formula

converted_amount = (amount × rate_from) ÷ rate_to

yaml
Copy
Edit

All calculations are done client-side using fixed values.

---

## Optional Improvements

You can improve or extend this app by:
- Connecting to a real-time exchange rate API (like ExchangeRate-API or OpenExchangeRates)
- Adding currency symbols and flags
- Supporting decimal precision selection
- Saving user preferences with localStorage

---
Made with using only HTML, CSS, and JavaScript.
