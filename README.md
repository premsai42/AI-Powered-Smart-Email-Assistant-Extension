# AI‑Powered Smart Email Assistant Extension

## 🎯 What this project is
A browser extension integrated with Gmail using AI-powered summarization and smart reply generation. Includes a React-based extension UI and a Spring Boot backend for high‑performance NLP and email automation.

## 🚀 Features
- AI‑powered email summarization
- Context‑aware reply suggestions
- Reply tone customization (Formal, Informal, Concise)
- <400 ms backend response time
- Seamless integration with Gmail UI
- Secure communication with OAuth2/Spring Security

## 📁 Repository Structure
```
/
├── email-writer-ext/        # Browser extension (React/TypeScript)
├── email-writer-react/      # Shared UI components
└── email-writer-sb/         # Spring Boot backend with AI integration
```

## 🛠 Getting Started
### 1. Clone the repository
```
git clone https://github.com/premsai42/AI-Powered-Smart-Email-Assistant-Extension.git
```

### 2. Backend Setup (`email-writer-sb`)
```
cd email-writer-sb
./mvnw spring-boot:run
```

### 3. Configure application credentials
- Gmail API OAuth credentials  
- Spring AI / Gemini Pro API key  
- Backend URL in `application.yml`

### 4. Frontend Extension Setup (`email-writer-ext`)
```
cd email-writer-ext
npm install
npm run build
```

### 5. Load Extension in Browser
- Open Chrome → Extensions  
- Enable *Developer Mode*  
- Click **Load Unpacked** and select the `build/` folder  
- Configure backend API URL inside extension settings

## 📌 Usage
1. Open Gmail  
2. Select an email thread  
3. Click the assistant panel  
4. Generate summary or AI replies instantly  
5. Edit, send, or copy the reply

## 🧩 Future Improvements
- Multi-language support  
- Outlook support  
- Voice-based email actions  
- Enhanced personalization using user profiles  

## 📜 License
MIT License

## 👤 Author
**Prem Sai Konatham**  
GitHub: [@premsai42](https://github.com/premsai42)
