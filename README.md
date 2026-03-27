# 🐷 Floe — Personal Finance Tracker
### *Know where your money goes*

Floe is a free, privacy-first personal finance app that runs entirely in your browser. No account required. No bank login. No data ever leaves your device.

---

## ✨ Features

### 📥 Smart Import
- Import **PDF or CSV** bank statements from any bank
- Auto-detects Chime, Chase, Bank of America, Wells Fargo, Capital One, Ally, and more
- 800+ US merchants auto-categorized instantly
- Duplicate detection — reimport the same statement without double counting

### 💰 Dashboard
- **Safe to spend** — one number showing exactly what you can spend after bills, savings, and expenses
- Income, spending, and savings at a glance
- Month-over-month spending comparison
- Daily spending chart
- Spending forecast — projects your end-of-month total based on your current pace
- Recent transactions with inline category editing

### 📊 Budgets
- Set monthly limits per category
- Visual progress bars — turns red when you go over
- Edit or delete budgets inline with the ✏️ pencil icon
- Remaining budget summary at a glance

### 📅 Bills Tracker
- Add recurring bills with name, amount, due date, and category
- Color-coded status — normal, due soon (amber), overdue (red), paid (faded)
- Mark bills as paid — auto-resets at the start of each new month
- Subscription detector — automatically finds recurring charges in your transactions

### 🐷 Savings Goals
- Create goals with emoji, target amount, and target date
- Auto-detects savings deposits from imported statements using keywords
- Tracks net savings — deposits minus withdrawals
- Monthly contribution tracking and progress bars

### 📈 Investments
- Track 401k, Roth IRA, brokerage accounts, and crypto
- Contribution-only tracking — no fake growth numbers
- Portfolio allocation donut chart

### 🌙 Dark Mode
- Full dark mode with one click
- Remembers your preference

### 📱 Mobile Friendly
- Fully responsive — works on phones and tablets
- Bottom navigation bar on mobile

### 🔒 Privacy First
- **Everything stays on your device** — no servers, no accounts, no cloud
- Data stored in your browser's localStorage
- Export a JSON backup anytime
- Restore from backup anytime

---

## 🚀 Getting Started

1. **Download** `index.html`
2. **Open** it in any browser (Chrome, Firefox, Safari, Edge)
3. Go to **Import** and upload your bank statement (PDF or CSV)
4. That's it — your transactions are categorized instantly

No installation. No account. No internet connection required after the first load.

---

## 🏦 Supported Banks

Floe works with statements from any bank. It has enhanced detection for:

| Bank | PDF | CSV |
|------|-----|-----|
| Chime | ✓ | ✓ |
| Chase | ✓ | ✓ |
| Bank of America | ✓ | ✓ |
| Wells Fargo | ✓ | ✓ |
| Capital One | ✓ | ✓ |
| Ally Bank | ✓ | ✓ |
| Any other bank | ✓ | ✓ |

---

## 📂 How to Export Your Data

1. Click **Export / share data** in the sidebar
2. A JSON file downloads to your computer
3. Keep this as your backup

To restore: click **Restore from backup** and select your JSON file.

---

## 🛠️ Tech Stack

- Vanilla HTML, CSS, and JavaScript — zero frameworks
- [Chart.js](https://www.chartjs.org/) for charts
- [PDF.js](https://mozilla.github.io/pdf.js/) for PDF parsing
- localStorage for data persistence
- Single file — the entire app is one `.html` file

---

## 🗺️ Roadmap

- [ ] Cross-device sync
- [ ] Email bill reminders
- [ ] Monthly spending report (email)
- [ ] Net worth tracker
- [ ] Debt payoff planner
- [ ] iOS / Android app

---

## 📄 License

MIT License — free to use, modify, and distribute.

---

## 💬 Feedback

Found a bug or have a feature request? Open an issue on GitHub.

---

*Built with ❤️ — Floe is free forever for personal use.*
