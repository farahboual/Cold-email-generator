## Smart Outreach Assistant
An intelligent AI-powered assistant created for service-based companies to streamline cold outreach. Built with Groq, LangChain, and Streamlit, this tool allows users to enter the URL of a company’s careers page, automatically extract job postings, and generate customized cold emails. These emails include curated portfolio links, matched intelligently from a vector database based on the job descriptions.

## Use Case: Real-World Scenario
Imagine Nike is looking to hire a Principal Software Engineer. Instead of going through the lengthy recruitment pipeline, AI_in_Need, a software service provider, wants to offer one of their expert engineers as an outsourced solution.

Farah, the business development executive at AI_in_Need, uses this app to automatically craft a tailored cold email for Nike—highlighting relevant projects and skills that align with the job posting. This not only saves Nike time and resources, but also creates a business opportunity for AI_in_Need.

## 📸 Demo Screenshot
![image](https://github.com/user-attachments/assets/df906e0b-4f9b-4d11-a690-62eebbcd30f1)




https://github.com/user-attachments/assets/a3006338-a67b-4a42-bf33-a9142bce6d75



## Architecture Overview
The diagram below outlines the system architecture and how different components interact to power the email generation process:


 Architecture Diagram


### ⚙️ Getting Started

#### Step 1: Configure Your API Key
Go to [Groq Console](https://console.groq.com/keys) and generate a new API key.  
Add it to the `.env` file located in the `app/` directory:



