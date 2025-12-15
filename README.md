# 🍕 Zomato Clone Ecosystem

A complete, production-ready food delivery platform ecosystem consisting of a Customer App, Delivery Partner App, Restaurant Partner App, and a Super Admin Dashboard.

## 🌟 Ecosystem Overview

This monorepo contains the following applications:

| Application | GitHub Repository | Description | Tech Stack |
|-------------|-------------------|-------------|------------|
| **[Customer App](https://github.com/ArshVermaGit/zomato-customer-app) | For users to browse food, order, and track deliveries. | React Native (Expo) |
| **[Restaurant Partner App](https://github.com/ArshVermaGit/zomato-restaurant-partner) | For restaurants to manage menus, orders, and business. | React Native (Expo) |
| **[Delivery Partner App](https://github.com/ArshVermaGit/zomato-delivery-partner) | For drivers to accept orders and navigate to locations. | React Native (Expo) |
| **[Admin Dashboard](https://github.com/ArshVermaGit/zomato-admin-dashboard) | Super admin panel for managing the entire platform. | Next.js 16, Tailwind |
| [Backend API](https://github.com/ArshVermaGit/zomato-backend) | Centralized server handling all requests. | NestJS, PostgreSQL |

## ✨ Key Features across Ecosystem

- **Real-time Updates**: Socket.io integration for live order tracking and status updates.
- **Geospatial Features**: Live location tracking for drivers and users.
- **Seamless Payments**: Integrated payment gateways for secure transactions.
- **Cross-Platform**: Mobile apps work flawlessly on both iOS and Android.

## 🛠️ Tech Stack

- **Monorepo Tooling**: Lerna / Turbo
- **Backend**: Node.js, NestJS, Prisma ORM
- **Database**: PostgreSQL, Redis (Caching)
- **Frontend**: React Native, Next.js, TailwindCSS
- **Infrastructure**: Docker, Kubernetes (optional)

## 🚀 Getting Started

### Prerequisites

- Node.js 18+
- PostgreSQL
- Redis
- Expo CLI (`npm install -g expo-cli`)

### Installation

1.  **Clone the repository**
    ```bash
    git clone https://github.com/ArshVermaGit/zomato-ecosystem.git
    cd zomato-ecosystem
    ```

2.  **Install dependencies**
    ```bash
    npm install
    ```

3.  **Environment Setup**
    Copy `.env.example` to `.env` in the root and individual app directories and fill in the required credentials.

4.  **Run the Ecosystem**
    ```bash
    # Start Backend
    cd backend/zomato-api && npm run start:dev

    # Start Apps (in separate terminals)
    cd apps/zomato-customer-app && npx expo start
    ```

## 🤝 Contributing

Contributions are welcome! Please read the [contributing guidelines](CONTRIBUTING.md) first.

## 👨‍💻 Author

**Arsh Verma** - *Full Stack Developer*

Connect with me:

- 🐙 **GitHub**: [ArshVermaGit](https://github.com/ArshVermaGit)
- 💼 **LinkedIn**: [arshvermadev](https://www.linkedin.com/in/arshvermadev/)
- ✖️ **X (Twitter)**: [@TheArshVerma](https://x.com/TheArshVerma)
- 📧 **Email**: [Arshvermadev@gmail.com](mailto:Arshvermadev@gmail.com)

---

Made with ❤️ by ArshCreates
# zomato-ecosystem
