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
