# AgriBazar AI 🌾
Development of an Intelligent Agricultural Marketplace and Price Forecasting System  
Course: CSE 4104 (Software Development III)  
Department of Computer Science and Engineering | NUBTK  

---

## 👥 Project Contributors & Academic Information
* **Official Team Designation:** CSE4104-7D-T05  
* **Academic Section:** 7D  

### Roster:
1. **Niloy Kumar Saha** (ID: 11240121643)
2. **Papon Sen** (ID: 11230321364) 
3. **Samapti Dakua** (ID: 11230321350)
4. **Tithi Chowdhury** (ID: 11230321336) 

---

## 🎯 System Design Architecture & Blueprints
The production blueprint for AgriBazar AI translates enterprise agricultural business logic into a type-safe distributed infrastructure. The core synchronization engine enforces the following technical pipelines:
* **System Flow Execution:** `Client Presentation Layer (React.js)` ➔ `Application Service Layer (Spring Boot API Gateway)` ➔ `Persistent Data Store (MySQL via phpMyAdmin)`.
* **Asynchronous AI Hook:** The Java server intercepts analytical history queries and handles secure payloads with the `Google Gemini API Layer` to stream continuous time-series crop forecasting matrices directly to client dashboards.

---

## 🚀 Active Feature Modules (Week 04 Update)
* **Secure Auth Controller (`/api/auth`):** Enforces cryptographic hashing of credentials and state token validation over secure HTTPS.
* **Crop Inventory Manager (`/api/crops`):** Ingests harvest metadata alongside mandatory real-time smartphone photo attachments to ensure absolute product freshness.
* **Gemini Predictive Engine (`/api/ai`):** Parses localized historical commodity cost datasets to output predictive distrib-matrices for the upcoming 7-30 days.
* **Direct Settlement Network (`/api/orders`):** Orchestrates bulk cart management, automated status transition toggles (`SOLD_OUT`), and transactional messaging nodes.

---

## 📂 Production Repository Layout
```text
├── /frontend             # React.js client interface compilation files
│   ├── src/
│   └── package.json
├── /backend              # Java Spring Boot enterprise application code layers
│   ├── src/
│   └── pom.xml           # Dependencies build automation script
├── /database             # Contains structural MySQL relational schema dump files
├── /diagrams             # Individual system blueprints (.png)
└── /documentation        # Unified System Design official document PDF
```
