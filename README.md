# 🚀 Microservices Spring Security with JWT

This repository contains a **Spring Boot microservices setup** with:

✨ **Key Features**  
- 🌐 **Centralized Configuration** using Spring Cloud Config Server  
- 🔍 **Service Discovery** using Eureka Server  
- 🛣️ **API Gateway** for routing requests between microservices  
- 📊 **Actuator Endpoints** exposed for monitoring (`/actuator`) - health, info, metrics, etc.  
- 🔒 **JWT Security** for authentication and authorization  
- 🗄️ **MySQL Database Integration** for persistent storage  

---

## 🏗️ Microservices Included

- **authserviceapp** – Authentication & User Management  
- **user-service** – User Related APIs  
- **api-gateway** – Routing and Centralized Entry Point  
- **service-registry** – Eureka Server for Service Discovery  

---

## ⚡ Getting Started

1. Start **Eureka Server** (`service-registry`)  
2. Start **Config Server**  
3. Start Microservices (`authserviceapp`, `user-service`, `api-gateway`)  
4. Access **Actuator Endpoints** at `/actuator` for monitoring  

---

