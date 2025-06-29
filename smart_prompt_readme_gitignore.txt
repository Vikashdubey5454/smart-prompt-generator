# .gitignore

# Java & Spring Boot
/target/
*.class
*.jar
*.war

# Node.js & React
/node_modules/
/build/
.env

# Logs
logs/
*.log

# IntelliJ IDEA
.idea/
*.iml

# System Files
.DS_Store
Thumbs.db


# README.md

# Smart Prompt Generator

Smart Prompt Generator is a full-stack AI web application that allows users to:

- 💬 **Generate Smart Chat Responses** using GPT-4o
- 🎨 **Generate AI Images** with DALL·E-2
- 🍲 **Create Custom Recipes** based on ingredients, cuisine, and diet

---

## 🚀 Technologies Used

### Frontend:
- React.js
- HTML, CSS, JavaScript

### Backend:
- Java
- Spring Boot
- REST API

### APIs:
- OpenAI GPT-4o for chat and recipe
- OpenAI DALL·E-2 for image generation

### Others:
- IntelliJ IDEA
- Git & GitHub
- Postman for testing

---

## ⚙️ Features

### 1. Chat Prompt Generator
- Users input any prompt and receive smart, human-like responses.

### 2. AI Image Generator
- Users provide a text prompt and get high-quality AI-generated images.
- Options include size, number of images, and quality.

### 3. Recipe Creator (Fun Use-Case)
- Users input ingredients, cuisine type, and dietary preferences.
- Output: AI-generated customized recipes.

---

## 🛠️ How to Run the Project

### 🔧 Backend (Spring Boot)
```bash
cd SpringAiDemo
./mvnw spring-boot:run
```

### 💻 Frontend (React)
```bash
cd spring-ai-demo-react
npm install
npm start
```

---

## 📂 Folder Structure
```
spring-ai-demo-main/
├── SpringAiDemo/        # Backend - Spring Boot
├── spring-ai-demo-react/ # Frontend - React
```

---

## 🧠 Author
- **Vikash Dubey**
