# Keychain – AI-Powered CPG Product Creation & Supplier Matching Platform

Keychain is an AI-powered platform designed for consumer packaged goods (CPG) brands and retailers to accelerate product creation and streamline supplier sourcing. Using natural-language inputs, users can instantly generate complete product specifications, and the platform automatically identifies qualified manufacturers, packaging partners, ingredient suppliers, and logistics providers.

---

## 🌟 Key Capabilities

### **AI Specification Generation**
Transforms natural-language descriptions into structured product specifications using LLM-based models.

### **Supplier Matching Engine**
Identifies the most suitable suppliers based on certifications, allergen profiles, sustainability attributes, capabilities, and production capacity.

### **Unified Collaboration Hub**
Consolidates communication, document sharing, and task management between brands and suppliers into a single interface.

### **End-to-End Supply Chain Visibility**
Provides transparency across product development workflows—from ideation to pre-production—reducing delays and manual tracking.

---

## 🔧 Google Cloud Integration

Keychain is built on Google Cloud to ensure high scalability, reliability, and enterprise-grade security.

- **Vertex AI** — LLM-driven specification generation, semantic supplier search, recommendation models  
- **Cloud Run / Cloud Functions** — Serverless backend execution and event-driven tasks  
- **BigQuery / Firestore** — Supplier data, product specifications, and metadata storage  
- **Cloud Storage** — Document and asset storage for R&D and supplier workflows  
- **IAM / VPC / KMS / Audit Logs** — Access control, encryption, and security compliance  

---

## 🏗 High-Level System Architecture

User / Web Application
|
v
[ Cloud Run ] – Core Backend Services
/ | \
v v v
[Cloud Functions] [Vertex AI] [BigQuery / Firestore]
| | |
| v v
| [Cloud Storage] [IAM / Security]
|_______________________________________________|

(A visual system architecture diagram can be added in `/architecture` as PNG.)

---

## 📈 Business Impact

- Reduces product development cycles from weeks to days  
- Improves accuracy and precision of supplier matching  
- Eliminates manual sourcing and communication overhead  
- Enhances internal and external collaboration across supply chain teams  
- Strengthens visibility, compliance, and supplier data quality  

---

## 🔗 Useful Links

- **Official Website:** https://keychain.team  
- **GitHub Repository:** https://github.com/Oisin-Hanrahan/keychain-solution  
- **Contact:** team@keychain.team  

---

### 🚀 For Google Cloud Solution Qualification  
This repository provides a public, technical overview of the Keychain platform and its integration with Google Cloud services. Additional assets such as architecture diagrams and whitepapers can be included in the `/architecture` and `/whitepaper` directories.


