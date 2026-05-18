# 🚀 ByteExchange – Simulated Crypto Exchange

ByteExchange is a lightweight **simulated cryptocurrency exchange platform** that enables **BTC/USD trading** using **market and limit orders**, simulated wallets, a matching engine, real-time market updates, REST APIs, WebSocket streaming, and a modern React dashboard.

The platform is designed for learning and demonstrating **Java Spring Boot, WebSocket communication, distributed systems concepts, testing, observability, and containerized deployment**.

---

## 📌 Features

### 🔐 User Wallet System
- Simulated crypto and fiat balances
- User account management
- Wallet funding simulation
- Balance tracking

### 📈 Trading Engine
- BTC/USD trading pair
- **Market Orders**
- **Limit Orders**
- Order book management
- Trade matching engine
- Simulated trade execution

### 📡 Real-Time Market Data
- Live market updates using **WebSockets**
- Order book streaming
- Price updates
- Trade activity feed

### 🌐 REST API
- Wallet management endpoints
- Trading APIs
- Market data APIs
- Order placement and cancellation

### 📊 Dashboard & Visualization
- React-based trading dashboard
- Live charts using **Chart.js**
- Real-time order book display
- Market activity visualization

### ⚙️ Observability & Monitoring
- Logging with **SLF4J + Logback**
- Metrics using **Prometheus**
- Dashboards using **Grafana**
- Distributed tracing with **OpenTelemetry**

### 🧪 Testing
- Unit testing with **JUnit 5**
- Mock testing using **Mockito**
- Integration testing using **Testcontainers**
- API testing support

---

## 🏗️ Tech Stack

### Backend
- **Java 17+**
- **Spring Boot**
  - Spring Web
  - Spring Data JPA
  - Spring WebSocket
  - Spring Security *(optional)*

### Database & Caching
- **PostgreSQL**
- **Redis**
- **H2 Database** *(for testing)*

### Messaging *(Optional)*
- **Apache Kafka**
OR
- **RabbitMQ**

### Frontend
- **React (Vite / CRA)**
- **Chart.js**

### DevOps & Deployment
- **Docker**
- **Docker Compose**
- **GitHub Actions (CI/CD)**

### Observability
- **Prometheus**
- **Grafana**
- **OpenTelemetry**

---

## 📂 Project Structure
ByteExchange/
│── backend/
│ ├── src/
│ ├── controllers/
│ ├── services/
│ ├── repositories/
│ ├── models/
│ ├── websocket/
│ └── matching-engine/
│
│── frontend/
│ ├── src/
│ ├── components/
│ ├── pages/
│ ├── charts/
│ └── services/
│
│── docker/
│── docs/
│── tests/
│── docker-compose.yml
│── README.md


---

## 🔄 System Workflow

1. User logs in or creates a simulated wallet.
2. User deposits virtual USD/BTC funds.
3. User places **market** or **limit** orders.
4. Matching engine processes orders.
5. Trade executes if conditions match.
6. Wallet balances update.
7. Live updates stream through WebSocket.
8. Dashboard reflects trading activity in real time.

---

## 🔌 API Features

### Wallet APIs
- Create wallet
- Get balance
- Deposit simulated funds
- Withdraw simulated funds

### Trading APIs
- Place order
- Cancel order
- Get open orders
- View trade history

### Market APIs
- Order book data
- Price updates
- Market trades

---

## 🖥️ Running the Project

### 1️⃣ Clone Repository

```bash
git clone <repository-url>
cd ByteExchange
---
###2️⃣ Run with Docker
docker-compose up --build
---
###3️⃣ Run Backend
cd backend
./mvnw spring-boot:run
---
###4️⃣ Run Frontend
cd frontend
npm install
npm run dev
---
##🧪 Running Tests
./mvnw test
---
📊 Monitoring
| Tool       | URL                                            |
| ---------- | ---------------------------------------------- |
| Grafana    | [http://localhost:3000](http://localhost:3000) |
| Prometheus | [http://localhost:9090](http://localhost:9090) |

---
##🐳 Docker Support

ByteExchange supports containerized deployment using:

Docker
Docker Compose

This allows easy local development and CI/CD deployment.
Disclaimer: ByteExchange does not facilitate real cryptocurrency trading or financial transactions.


This version looks professional for GitHub and matches your project brief while using the name **ByteExchange** instead of OpenEx. I
---
##📅 Development Roadmap
Week 1 – Backend Foundations
REST API development
WebSocket setup
PostgreSQL & Redis integration
Wallet and trading services
Week 2 – Frontend Development
React dashboard
Chart.js integration
WebSocket connectivity
API integration
Week 3 – Testing & Monitoring
JUnit & Mockito
Testcontainers
Prometheus + Grafana
Load testing
Week 4 – Deployment
Docker containerization
GitHub Actions CI/CD
API documentation
Final project demo
---
##👥 Contributors

Team ByteExchange

---
##📄 License

This project is developed for educational purposes and simulation only.

Disclaimer: ByteExchange does not facilitate real cryptocurrency trading or financial transactions.

This version looks professional for GitHub and matches your project brief while using the name **ByteExchange** instead of OpenEx. It also sounds production-ready for submission.
