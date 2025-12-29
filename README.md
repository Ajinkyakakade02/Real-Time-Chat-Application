# Real-Time Chat Application

A real-time chat application built using **Java and Spring Boot** that allows multiple users to communicate instantly. The application uses **WebSocket technology with STOMP over SockJS** to enable fast, bidirectional messaging through a simple and responsive web interface accessible on any device.

---

## Features
- Real-time messaging using WebSockets  
- Multi-user chat support  
- STOMP protocol for structured communication  
- SockJS fallback for browser compatibility  
- Responsive UI for desktop and mobile  
- Easy to deploy on cloud platforms  

---

## Tech Stack
**Backend**
- Java  
- Spring Boot  
- Spring WebSocket  
- STOMP Messaging  

**Frontend**
- HTML  
- CSS  
- JavaScript  
- Bootstrap  
- SockJS  
- STOMP.js  

---

## Project Structure

src
└── main
├── java
│ └── com.chat.app
│ ├── controller
│ ├── config
│ └── model
└── resources
├── static
│ ├── index.html
│ ├── app.js
│ └── style.css
└── application.properties


---

## How It Works
1. The client establishes a WebSocket connection with the server.
2. Messages are sent to the server using STOMP endpoints.
3. The Spring Boot server processes and broadcasts messages.
4. All connected users receive messages instantly without refreshing the page.

---

## How to Run Locally
1. Clone the repository

git clone https://github.com/Ajinkyakakade02/real-time-chat-app.git

2. Open the project in IntelliJ IDEA or VS Code  
3. Run the Spring Boot application  
4. Open your browser and visit:



---

## Deployment
This application can be deployed on cloud platforms such as **Railway**, **Render**, or **AWS**, making it accessible globally on any device.

---

## Future Enhancements
- User authentication
- Private chats
- Message persistence with database
- Online/offline status
- File sharing

---

## Author
**Ajinkya Kakade**

---

## License
This project is licensed under the MIT License.

