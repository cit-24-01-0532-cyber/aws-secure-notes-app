# 🔐 Secure Cloud Notes App with AWS Cognito

A serverless web application that provides a secure platform for saving notes, featuring user authentication and authorization using **AWS Cognito**.

## 🚀 Key Features
- **User Authentication:** Secure Login, Sign-up, and Password recovery flows.
- **Token-Based Security:** Uses **JSON Web Tokens (JWT)** to authorize user requests and verify identity.
- **Serverless Integration:** Designed to work seamlessly with AWS S3 hosting and Cognito User Pools.
- **Modern UI:** Clean and responsive interface for safe note management.

## 🛠️ Architecture & Tools
- **Identity Management:** AWS Cognito (User Pools)
- **Security:** JWT (ID Tokens & Access Tokens)
- **Frontend:** HTML5, CSS3, JavaScript (ES6+)
- **Deployment:** AWS S3 Static Website Hosting

## 📸 Screenshots
### 1. Authentication Portal
*Secure login interface integrated with AWS Cognito.*
![Login Screen]()

### 2. Secure Dashboard
*Successfully authorized view showing the user's ID Token.*
![Dashboard]()

## 🏗️ How it Works
1. User enters credentials in the **Cognito-hosted UI**.
2. Upon successful login, AWS Cognito returns an **ID Token**.
3. The app verifies the token and grants access to the "Secure Notes" dashboard.
4. Users can then interact with the app securely, knowing their session is authorized.
