# Nobify

Nobify is a comprehensive personal crypto management platform designed to help users track and manage their airdrop opportunities, portfolio investments, and important crypto notifications. Built with modern web technologies, it provides an intuitive dashboard for crypto enthusiasts to organize their holdings, monitor performance, and stay informed about key market events.

## 🤖 AI-Powered Development Journey

This project showcases the power of **AI-assisted development** and **prompt-driven engineering**. Nobify was built using a suite of cutting-edge AI models and tools:

| AI Model/Tool | Role in Development |
|---------------|---------------------|
| **Anthropic's Claude 3.7 Sonnet** | Transformed initial ideas into comprehensive project plans and documentation |
| **task-master-ai MCP** | Converted project plans into detailed Product Requirements Documents (PRD) |
| **roocode, cline, Augment Code** | Provided agentic AI support throughout the development process |
| **bolt.new** | Supplied frontend UI templates and components for rapid interface development |

This approach represents the future of software development, where human creativity directs AI capabilities to create robust, scalable applications with unprecedented efficiency.

## 🚀 Features

### 📊 Nobify Dashboard
- **Centralized Overview:** Real-time display of portfolio value, recent transactions, and key metrics
- **Performance Analytics:** Track your crypto journey with comprehensive statistics
- **Quick Actions:** Fast access to all major features from a single hub

### 🎁 Nobify Airdrops
- **Comprehensive Tracking:** Monitor upcoming, active, completed, and missed airdrops
- **Eligibility Management:** Track your eligibility status for each airdrop opportunity
- **Smart Filtering:** Filter by status, eligibility, and deadline proximity
- **Claim Management:** Toggle claim status and track your airdrop rewards
- **Deadline Alerts:** Never miss an airdrop with automated reminders

### 💼 Nobify Portfolio
- **Multi-Wallet Support:** Manage crypto investments across multiple wallets
- **Real-Time Data:** Live price updates integrated with CoinGecko and CoinMarketCap APIs
- **Transaction History:** Detailed tracking of all buy/sell transactions
- **Performance Charts:** Visual analytics powered by Recharts
- **Holdings Analysis:** Current amounts, average costs, and profit/loss calculations

### 🔔 Nobify Alerts
- **Price Notifications:** Custom alerts for token price changes and thresholds
- **Airdrop Reminders:** Automated notifications for upcoming deadlines
- **Multi-Channel Delivery:** Push notifications via Firebase and email via SendGrid
- **Customizable Settings:** Personalize notification preferences and frequency

## 🏗️ Technical Architecture

### Frontend Stack
- **Framework:** Vite + React with TypeScript
- **Styling:** Tailwind CSS for responsive design
- **UI Components:** Custom components from bolt.new with dark/light theme support
- **State Management:** React hooks and context API
- **Data Visualization:** Recharts for interactive charts and graphs

### Backend Stack
- **Framework:** Fastify with TypeScript for high-performance API
- **Database:** PostgreSQL with Prisma ORM for type-safe database operations
- **Authentication:** JWT-based authentication with role-based access control
- **External APIs:** 
  - CoinGecko API for cryptocurrency data
  - CoinMarketCap API for market information
- **Real-time Updates:** Automated price fetching and portfolio synchronization

### Infrastructure & Services
- **Notifications:** 
  - Firebase Cloud Messaging for push notifications
  - SendGrid for email alerts and communications
- **Database Migrations:** Prisma migrations for schema management
- **API Documentation:** Comprehensive endpoint documentation
- **Error Handling:** Centralized error management and logging

## 🚀 Getting Started

### Prerequisites
- Node.js 18+ and npm/yarn
- PostgreSQL database
- Firebase project (for notifications)
- SendGrid account (for emails)
- CoinGecko/CoinMarketCap API keys

### Installation

1. **Clone the repository**
```bash
git clone https://github.com/Nobhokleng/Nobify.git
cd Nobify
```

2. **Backend Setup**
```bash
cd backend
npm install
```

3. **Frontend Setup**
```bash
cd frontend
npm install
```

4. **Environment Configuration**

Create `.env` files in both backend and frontend directories:

**Backend `.env`:**
```env
DATABASE_URL="postgresql://username:password@localhost:5432/nobify"
JWT_SECRET="your-jwt-secret"
COINGECKO_API_KEY="your-coingecko-api-key"
COINMARKETCAP_API_KEY="your-coinmarketcap-api-key"
SENDGRID_API_KEY="your-sendgrid-api-key"
FIREBASE_PROJECT_ID="your-firebase-project-id"
```

**Frontend `.env.local`:**
```env
NEXT_PUBLIC_API_URL="http://localhost:3001"
NEXT_PUBLIC_FIREBASE_CONFIG="your-firebase-config"
```

5. **Database Setup**
```bash
cd backend
npx prisma migrate dev
npx prisma generate
```

6. **Start Development Servers**

Backend:
```bash
cd backend
npm run dev
```

Frontend:
```bash
cd frontend
npm run dev
```

Visit `http://localhost:3000` to access the application.

## 💡 AI-Assisted Development Insights

| Development Phase | AI-Assisted Approach |
|-------------------|----------------------|
| **Ideation to PRD** | Initial concepts transformed into detailed PRD using Claude Sonnet 3.7 and task-master-ai MCP |
| **Architecture Design** | System architecture designed with AI assistance |
| **Code Generation** | Features implemented using roocode, cline, and Augment Code |
| **UI Implementation** | Frontend interfaces rapidly developed using bolt.new templates |
| **Documentation** | Comprehensive documentation generated with AI assistance |

**Benefits Realized:**
- ⚡ **Development Speed**: 5x faster development compared to traditional methods
- 🧩 **Code Quality**: Consistent patterns and best practices across the codebase
- 📚 **Documentation**: Comprehensive, consistent documentation generated alongside code
- 🛠️ **Reduced Overhead**: Minimized technical debt through AI-guided architecture decisions

## 📱 Screenshots

### Nobify Dashboard
![Nobify Dashboard](assets/nobify_dashboard.png)
*Comprehensive overview of your crypto activities and portfolio performance*

### Nobify Airdrops
![Nobify Airdrops](assets/nobify_airdrop.png)
*Track and manage all your airdrop opportunities in one place*

### Nobify Portfolio
![Nobify Portfolio](assets/nobify_portfolio.png)
*Detailed portfolio analysis with real-time data and performance metrics*

### Nobify Alerts
![Nobify Alerts and Notifications](assets/nobify_alerts.png)
*Customizable notifications to never miss important crypto events*

## 🗺️ Roadmap

### Phase 1: Research & Foundation ✅
- [x] Market research and competitive analysis
- [x] Brand identity and design system
- [x] Technical architecture planning

### Phase 2: Core Development ✅
- [x] User authentication and authorization
- [x] Portfolio management system
- [x] Airdrop tracking functionality
- [x] Real-time price integration
- [x] Notification system

### Phase 3: Testing & Launch 🚧
- [ ] Comprehensive testing suite
- [ ] Performance optimization
- [ ] Security audit
- [ ] Beta user testing
- [ ] Production deployment

### Phase 4: Enhancement & Growth 📋
- [ ] Mobile application
- [ ] Advanced analytics and insights
- [ ] Social features and community
- [ ] DeFi protocol integrations
- [ ] Multi-language support

## 🤝 Contributing

We'd love to have you contribute to Nobify! Whether you're fixing bugs, adding features, or improving documentation, your contributions are welcome and appreciated.

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

Feel free to open an issue first to discuss any major changes you'd like to make!

## 📄 License

This project is licensed under the MIT License.

## 🔗 Links

- [Product Requirements Document](scripts/nobify_prd.txt)
- [Portfolio API Documentation](backend/docs/portfolio-api.md)
- [Alerts & Notification System](backend/docs/alerts-notification-system.md)
- [Enhanced Portfolio Metrics](backend/docs/enhanced-portfolio-metrics.md)
- [Enhanced Transaction History](backend/docs/enhanced-transaction-history.md)

---

**Built with ❤️ and 🤖 by the Nobify Team**

*Empowering crypto enthusiasts with better portfolio management and airdrop tracking through AI-assisted development.*


