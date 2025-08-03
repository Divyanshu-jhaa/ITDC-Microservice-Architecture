# ITDC Microservice Architecture

A scalable, modular system built using a microservice architecture with React frontend and multiple backend services using Spring Boot.

## 🔧 Repositories

- 🚪 **API Gateway** – [itdc-api-gateway](https://github.com/Divyanshu-jhaa/itdc-api-gateway)
- 🌐 **Service Discovery (Eureka)** – [itdc-discovery-server](https://github.com/Divyanshu-jhaa/itdc-service-discovery)
- 👤 **User Service** – [itdc-user-service](https://github.com/Divyanshu-jhaa/itdc-user-service)
- 🛠️ **Admin Service** – [itdc-admin-service](https://github.com/Divyanshu-jhaa/itdc-admin-service)
- 🖥️ **React Frontend** – [itdc-frontend](https://github.com/Divyanshu-jhaa/itdc-client)

## 🧰 Tech Stack

- React.js (Frontend)
- Spring Boot (Microservices)
- Spring Cloud Gateway (API Gateway)
- Eureka Server (Service Discovery)
- Render (Cloud Deployment)
- JWT (Authentication)
- REST APIs

## 🗂 Description

All client requests pass through the API Gateway, which connects to individual services registered via Eureka. Services wake up dynamically via Render's free tier logic. The frontend is fully reactive and communicates securely with backend services.

## 🚀 Live Demo (Optional)
https://itdc-client.onrender.com
