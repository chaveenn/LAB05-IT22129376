# 📦 IT22129376 – SE4010 Lab Sheet 05
## Microservices-Based E-Commerce Backend

This project implements a **Dockerized Microservices Architecture** using **Node.js and Express** with an **API Gateway pattern**.  
All client requests are routed through a single gateway which communicates with independent backend services.

---

## 🚀 Features

- API Gateway routing
- Independent microservices
- RESTful APIs
- Docker Compose setup
- Containerized deployment
- Easy scalability & service isolation

---

## 🏗️ System Architecture

Client  
↓  
API Gateway (Port 8080)  
↓  
- Item Service  
- Order Service  
- Payment Service  

---

## 📦 Services

| Service | Responsibility |
|---------|----------------|
| API Gateway | Routes all incoming requests |
| Item Service | Manage items/products |
| Order Service | Handle order creation |
| Payment Service | Process and track payments |

---

## ⚙️ Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/chaveenn/LAB-05-It22129376.git
