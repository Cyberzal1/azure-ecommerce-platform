# Strong Ape Apparel E-Commerce (Cloud Project)

## 🌐 Project Overview
Strong Ape Apparel is a Singapore-based retail brand expanding into e-commerce.  
This project was developed as part of our Cloud Computing module at Generations Singapore,  
with the goal of creating a **scalable, secure, and user-friendly online store**.

The e-commerce platform is built on **Microsoft Azure**, integrating cloud-native services for  
scalability, inventory management, and seamless payment processing.

🔗 **Demo Mockup Site:** [strongape.pythonanywhere.com](https://strongape.pythonanywhere.com/)  
🔗 **Presentation Slides:** [View Here](./docs/Strong_Apes_Distribution.pdf)  
🔗 **Proposal Report:** [View Here](./docs/Strong_Apes_Proposal.pdf)

---

## ✨ Features
- User registration & login (via Microsoft Entra ID)  
- Product browsing with categories & search  
- Shopping cart with Redis caching for performance  
- Secure checkout & payment integration  
- Inventory management linked to Azure SQL Database  
- Order confirmation and status tracking  
- Scalable cloud deployment with Azure DevOps CI/CD  

---

## 🏗️ System Architecture
The solution follows a **cloud-native architecture on Azure**:

1. Users access via browser or mobile app.  
2. Product catalog retrieved from Azure SQL & Blob Storage.  
3. Redis used for caching product queries.  
4. Shopping cart data queued in Azure Queue Storage.  
5. Azure Functions handle order processing & payments.  
6. Orders stored in Azure SQL Database.  
7. Confirmation displayed to the user after successful payment.  

📌 See full architecture diagram in `docs/architecture.png`.

---

## ⚙️ Tech Stack
- **Frontend:** HTML, CSS, Bootstrap/Tailwind  
- **Backend:** Flask (Python), SQLAlchemy ORM  
- **Database:** Azure SQL Database, Redis Cache  
- **Cloud Services:** Azure App Service, Blob Storage, Queue Storage, Azure Functions  
- **Security:** Microsoft Entra ID (Authentication), Azure Key Vault  
- **DevOps:** Azure DevOps (Pipelines, Artifacts), Application Insights, Azure Policy  

---

## 🚀 Deployment
- CI/CD via Azure DevOps pipelines  
- Hosted on Azure App Service with Blob Storage for static assets  
- Monitoring via Azure Application Insights  
- Secure credential management with Azure Key Vault  

---

## 📅 Project Timeline
- **Phase 1 (Weeks 1–3):** Scoping & Design  
- **Phase 2 (Weeks 4–10):** Frontend & Backend Development  
- **Phase 3 (Weeks 9–12):** Testing & Optimization  
- **Phase 4 (Weeks 11–13):** Deployment & Training  
- **Phase 5 (Weeks 13–14):** Post-deployment Support  

---

## 👥 Team Contributors
- Abel  
- Abedline  
- Sopfian (CyberZal)  
- Wee Chuan  

---

## 🔮 Future Improvements
- Mobile app integration  
- AI-driven product recommendations  
- Multi-language & multi-currency support  
- Enhanced analytics dashboard for sales insights  

---

## 🛠️ Run Locally
1. Clone the repository  
   ```bash
   git clone https://github.com/<your-repo>.git
   cd strong-ape-apparel
