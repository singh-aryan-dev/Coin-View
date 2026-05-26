# 🪙 CoinView

> A real-time cryptocurrency market data viewer — track live prices, market caps, and performance charts in a clean, focused React interface.

🔗 **Live Demo:** [coin-view-three.vercel.app](https://coin-view-three.vercel.app/)

---

## 📌 Overview

CoinView is a streamlined crypto market dashboard built for quick, essential analysis. It fetches live data from a cryptocurrency API and presents it through a clean, distraction-free interface — giving you the metrics that matter most without the noise. Whether you're monitoring your portfolio or researching market trends, CoinView puts real-time data at your fingertips.

---

## ✨ Features

- 💰 **Live Coin Prices** — Real-time price updates fetched directly from a live crypto API
- 📊 **Market Cap Tracking** — View and compare market capitalizations across coins
- 📈 **Performance Charts** — Visual price history and trend charts for quick analysis
- 🔍 **Coin Search & Filtering** — Quickly find and focus on specific cryptocurrencies
- 🌙 **Clean UI** — Minimal, distraction-free design focused purely on essential metrics
- 📱 **Responsive Design** — Fully optimized for desktop and mobile screens

---

## 🛠️ Tech Stack

| Technology | Purpose |
|------------|---------|
| **React** | Frontend UI framework |
| **JavaScript (ES6+)** | Core application logic |
| **CoinGecko API / CoinCap API** | Live cryptocurrency market data |
| **Chart.js / Recharts** | Data visualization and performance charts |
| **Axios / Fetch API** | HTTP requests and data fetching |
| **CSS3 / Material UI** | Styling and UI components |
| **Vercel** | Deployment and hosting |

---

## 🚀 Getting Started

### Prerequisites

- Node.js (v14 or higher)
- npm or yarn

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/singh-aryan-dev/coin-view.git
   cd coin-view
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Set up environment variables** *(if applicable)*

   Create a `.env` file in the root directory:
   ```env
   REACT_APP_CRYPTO_API_KEY=your_api_key_here
   ```

4. **Start the development server**
   ```bash
   npm start
   ```

   The app will run at `http://localhost:3000`

---

## 📁 Project Structure

```
coin-view/
├── public/
│   └── index.html
├── src/
│   ├── components/
│   │   ├── Banner/
│   │   ├── CoinTable/
│   │   ├── CoinChart/
│   │   └── Header/
│   ├── pages/
│   │   ├── HomePage.js
│   │   └── CoinPage.js
│   ├── api/
│   │   └── index.js        # API calls for live market data
│   ├── App.js
│   └── index.js
├── .env
├── package.json
└── README.md
```

---

## 📊 Key Metrics Displayed

- **Current Price** — Live USD (and multi-currency) pricing
- **Market Capitalization** — Total market value per coin
- **24h Price Change** — Percentage gain/loss over the last 24 hours
- **Price History Charts** — Configurable timeframe performance graphs
- **Volume** — 24-hour trading volume data

---

## 🌐 Deployment

This project is deployed on **Vercel**. To deploy your own instance:

```bash
npm run build
```

Connect your GitHub repository to [Vercel](https://vercel.com/) for automatic deployments on every push to `main`.

---

## 🔑 API Reference

- [CoinGecko API](https://www.coingecko.com/en/api) — Free, no auth required for public endpoints
- [CoinCap API](https://docs.coincap.io/) — Alternative real-time crypto data source

---

## 🤝 Contributing

Contributions, issues, and feature requests are welcome!

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

---

## 👨‍💻 Author

Developed by Aryan Singh

⭐ **If you found this project useful, please consider giving it a star!**
