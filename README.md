# Nobify

Nobify is a personal crypto management tool designed to help users track and manage their airdrop results, portfolio investments, and important notifications. It provides a simple, intuitive web-based platform for crypto enthusiasts to organize their holdings, monitor performance, and stay informed about key crypto events.

## Features

- **Nobify Dashboard:** Central hub displaying key statistics and an overview of your crypto activities, including portfolio value, airdrop claims, and recent alerts.
- **Nobify Airdrops:** Track upcoming, ongoing, and completed airdrops with eligibility criteria, deadlines, and claim status.
- **Nobify Portfolio:** Manage and analyze your crypto investments across multiple wallets with real-time data and historical performance charts.
- **Nobify Alerts:** Set custom notifications for token price changes, airdrop deadlines, and other important events.

## Technical Architecture

- **Frontend:** Built with Next.js, using Tailwind CSS for styling and Recharts for data visualization.
- **Backend:** Fastify framework with integration to third-party APIs like CoinGecko and CoinMarketCap.
- **Database:** PostgreSQL for storing user data, airdrops, portfolio, and alerts.
- **Notifications:** Firebase Cloud Messaging for push notifications and SendGrid for email alerts.

## Getting Started

To get started with Nobify, clone the repository and follow the setup instructions in the respective frontend and backend directories.

## Assets

Below are some key visuals representing Nobify's features:

### Nobify Dashboard
![Nobify Dashboard](assets/nobify_dashbaord.png)

### Nobify Airdrops
![Nobify Airdrops](assets/nobify_airdrop.png)

### Nobify Portfolio
![Nobify Portfolio](assets/nobify_portfolio.png)

### Nobify Alerts
![Nobify Alerts and Notifications](assets/nobify_alerts.png)

## Roadmap

- Phase 1: Research & Branding
- Phase 2: Core Features Development
- Phase 3: Testing & Launch
- Phase 4: Iterate & Improve

## License

This project is licensed under the MIT License.

---

For detailed requirements and technical specifications, refer to the [Nobify Product Requirements Document](scripts/nobify_prd.txt).