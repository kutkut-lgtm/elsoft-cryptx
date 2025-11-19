CryptX Dashboard project

A modern, responsive cryptocurrency asset dashboard built with React 19 and Tailwind CSS. CryptX provides real-time market insights, transaction tracking, and performance analytics with a clean, pixel-perfect UI designed for optimal user experience.

Project Structure

```text
elsoft-cryptx/
├── public/
│   └── robots.txt              # SEO crawler instructions
├── src/
│   ├── assets/                 # Static assets (icons, images)
│   │   ├── btc.png
│   │   ├── cardano.png
│   │   ├── eth.png
│   │   └── lite.png
│   ├── components/
│   │   ├── layout/             # Layout components
│   │   │   ├── Header.jsx      # Top navigation and user controls
│   │   │   ├── MainContent.jsx # Main dashboard content area
│   │   │   └── Sidebar.jsx     # Navigation sidebar
│   │   └── ui/                 # Reusable UI components
│   │       ├── ChartVisual.jsx       # BTC price chart visualization
│   │       ├── LiveMarketCard.jsx    # Crypto market card with sparkline
│   │       ├── MetricCard.jsx        # Dashboard metric display
│   │       └── TransactionTable.jsx  # Transaction history table
│   ├── data/                   # Static data modules
│   │   ├── chartStaticData.js  # BTC chart timeline and labels
│   │   └── transactionData.js  # Market data and transactions
│   ├── App.jsx                 # Root application component
│   ├── main.jsx                # React DOM entry point
│   └── index.css               # Global styles and Tailwind imports
├── index.html                  # HTML entry point
├── package.json                # Project dependencies and scripts
├── postcss.config.js           # PostCSS configuration
├── tailwind.config.js          # Tailwind customization
├── vite.config.js              # Vite build configuration
└── README.md                   # This file
```
