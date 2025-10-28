# 🛒 Cloud-Native E-commerce System

Cloud-Native Microservices Development with Docker and Web UI Integration  
Tech Stack: Docker · Flask · Node.js · MongoDB · PostgreSQL · REST · Docker Compose · Bootstrap · AWS
---

## 📘 Overview
- Designed and deployed containerized microservices for a full-stack e-commerce system.  
- Extended architecture with a Flask-Bootstrap web UI and structured the solution for cloud readiness on platforms like AWS ECS using Docker Compose and RESTful service orchestration.  
- Developed as an academic project for the **Cloud-Native Microservices Development** course, demonstrating full-stack cloud-based application design.
---

## ⚙️ Key Features
- Containerized microservices for user, product, order, and payment services using Docker.
- RESTful API endpoints for communication between services.  
- Flask-Bootstrap web UI for product browsing, cart management, and order checkout.  
- MongoDB for product catalog and user data, PostgreSQL for transactional order data.  
- Docker Compose setup for local orchestration of all services.  
- Structured for cloud deployment on AWS ECS or similar container platforms.

---

## 🗂️ Project Structure

cloud-native-ecommerce-system/

 ├── docker/ # Dockerfiles and Docker Compose configurations

 ├── services/
 
 │    ├── user/       # User service (Flask)
 │    ├── product/    # Product service (Node.js)
 │    ├── order/      # Order service (Node.js)
 │    └── payment/    # Payment service (Node.js)

 ├── web-ui/          # Flask-Bootstrap web interface

 ├── scripts/         # Utility and setup scripts

 ├── config/          # Environment and configuration files

 └── README.md

---

## 🚀 How to Run Locally
```bash
# Clone repository
git clone https://github.com/Kapil-Jobanputra/cloud-native-ecommerce-system.git

# Navigate into the project
cd cloud-native-ecommerce-system

# Build and start all services using Docker Compose
docker-compose up --build

```
Then open your browser and go to `http://127.0.0.1:5000`

---

## 🧾 Results & Insights
- Successfully deployed multiple containerized microservices communicating via REST APIs  
- Flask-Bootstrap web UI allows seamless product browsing, cart management, and order checkout  
- MongoDB and PostgreSQL integration ensured reliable data storage and transactional consistency  
- Docker Compose simplified local orchestration; architecture is ready for cloud deployment on AWS ECS  
- Demonstrated cloud-native microservices design, containerization, and full-stack development skills
---

## 👨‍💻 Role & Responsibilities
- Designed and developed the end-to-end microservices architecture using Docker, Flask, and Node.js  
- Built RESTful APIs and orchestrated service communication  
- Developed Flask-Bootstrap web UI for user interaction with products and orders  
- Integrated MongoDB and PostgreSQL for service-specific data management  
- Configured Docker Compose for local development and tested cloud-ready deployment setups
---

## 🧩 Future Enhancements
- Implement user authentication and role-based access control  
- Integrate payment gateway for real transactions  
- Add real-time notifications for order status updates  
- Deploy fully to AWS ECS with CI/CD pipelines for automatic updates  
- Include analytics dashboard for sales, user behavior, and inventory management
---

⭐ This project demonstrates full-stack cloud-native microservices development, containerization with Docker, RESTful service orchestration, and web UI integration for an academic e-commerce system.
