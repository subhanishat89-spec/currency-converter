# 💱 Currency Converter

A lightweight, responsive, real-time currency converter built with vanilla HTML, CSS, and JavaScript. No frameworks, no build step, and no API key required.

🔗 **Live Demo:** [subhanishat89-spec.github.io/currency-converter](https://subhanishat89-spec.github.io/currency-converter/)

![Currency Converter Screenshot](screenshot.png)

## ✨ Features

- 💱 Live exchange rates for 14 popular currencies, including USD, EUR, GBP, CAD, AUD, JPY, INR, and BDT
- ⚡ Instant conversion as you type
- 🔄 One-click currency swap
- 🛟 Automatic fallback to a second API if the first one fails
- 🧠 Rate caching (10 minutes) to reduce unnecessary network requests
- ⏳ Loading skeleton and clear error messages with a Retry button
- 🕒 "Last updated" timestamp for transparency
- 🌙 Automatic dark mode based on system settings
- 📱 Fully responsive, mobile-first design
- ♿ Accessible: labeled inputs and live-region results

## 🛠️ Tech Stack

- **HTML5**: semantic structure
- **CSS3**: custom properties, flexbox, animations, dark mode
- **JavaScript (ES6+)**: async/await, Fetch API, `Intl.NumberFormat`

## 🌐 APIs Used

| Role | API |
|------|-----|
| Primary | [ExchangeRate-API (Open Access)](https://www.exchangerate-api.com/docs/free) |
| Fallback | [fawazahmed0/currency-api](https://github.com/fawazahmed0/exchange-api) via jsDelivr |

Both are free and need no API key.

## 🚀 Run Locally

```bash
git clone https://github.com/subhanishat89-spec/currency-converter.git
cd currency-converter
```

Then open `index.html` in your browser. No installation needed.

## 📂 Project Structure

```
currency-converter/
├── index.html    # HTML, CSS, and JavaScript in one file
└── README.md
```

## 🔮 Future Improvements

- 📈 7-day exchange rate trend chart
- ⭐ Favorite currency pairs saved in localStorage
- 🌍 Full list of world currencies with search

## 👤 Author

**Nishat Subha**
GitHub: [@subhanishat89-spec](https://github.com/subhanishat89-spec)

## 📄 License

This project is open source and available under the [MIT License](LICENSE).
