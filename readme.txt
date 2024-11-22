# My Azure-Hosted Resume

Welcome to the GitHub repository for my **Azure-hosted Resume**! This project demonstrates my skills as an **Azure Cloud Solutions Architect** by using various Azure services to host my professional resume as a static website. You can view the live version of my resume at:
🌐 **[My Cool Resume Website](https://troddrige.com)**

## 🛠 Features of This Project

1. **HTML Resume**
   My resume is built entirely with HTML, showcasing my front-end development skills.

2. **CSS Styling**
   Styled with CSS to enhance readability and design.

3. **Azure Static Website Hosting**
   Hosted as a **static website** using Azure Storage, illustrating my ability to deploy scalable web applications.

4. **Secure HTTPS Connection**
   The site is secured with HTTPS, implemented using Azure CDN.

5. **Custom Domain**
   Access the site via a custom domain, configured with **Azure DNS** for professional branding.

6. **Visitor Counter**
   A **JavaScript-based visitor counter** dynamically displays the number of people visiting the site.

7. **CosmosDB Integration**
   The visitor counter is powered by **Azure CosmosDB**, leveraging the Table API to store and update visitor data.

8. **Serverless API with Azure Functions**
   A **Python-based API** (hosted using Azure Functions) securely communicates between the web app and CosmosDB.

9. **Infrastructure as Code (IaC)**
   All resources (Azure Functions, CosmosDB, etc.) are provisioned using **Azure Resource Manager (ARM) templates**.

10. **Continuous Integration and Deployment (CI/CD)**
    - **Back-end**: GitHub Actions automatically test and deploy Python code and ARM templates.
    - **Front-end**: GitHub Actions deploy updates to the static website in Azure Storage and purge the CDN cache.

11. **Python Testing**
    Robust Python tests ensure the quality and reliability of the back-end API.

## 📝 Blog Post: How I Hosted My Resume on Azure
For a detailed guide on how I built this project, including the challenges I faced and solutions I implemented, check out my blog post:
🔗 **[How I Hosted My Resume on Azure](https://trodrige.me)**

In the blog post, you'll learn:
- The step-by-step process of deploying a static website on Azure

Thank you for viewing my resume!!!
