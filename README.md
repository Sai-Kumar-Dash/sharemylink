# SML — Send My Link

A lightweight full-stack web app to send and manage links across devices using a simple 6-digit code. No WhatsApp, no USB, no friction.

---

## 🔥 The Problem

You find a link on your phone. You need it on your laptop.  
WhatsApp Web isn't logged in. USB transfer doesn't work for links.  
So you either email it to yourself or just forget about it.

**SML solves this.**

---

## ✅ Features

- 📤 **Send** — Paste any link and get a 6-digit code instantly
- 📥 **Receive** — Enter the code on any device to get the link
- 🔗 **Dashboard** — Save and manage your personal link collection
- 👤 **Auth** — Sign up and log in to keep your links tied to your account
- 📱 **Responsive** — Works on mobile and desktop

---

## 🛠️ Tech Stack

| Layer | Technology |
|-------|-----------|
| Backend | Java, Spring Boot |
| Frontend | HTML, Tailwind CSS, Vanilla JavaScript |
| Database | JPA, Hibernate |
| Build Tool | Maven |

---

## 📁 Project Structure
sml-project/
├── src/main/java/com/sml/
│   ├── controller/
│   │   ├── AuthController.java
│   │   ├── LinkController.java
│   │   └── ShareController.java
│   ├── model/
│   │   ├── User.java
│   │   └── Link.java
│   ├── repository/
│   │   ├── UserRepository.java
│   │   └── LinkRepository.java
│   └── SmlApplication.java
└── src/main/resources/
└── static/
├── js/
│   ├── auth.js
│   └── share.js
├── dashboard.html
├── signin.html
├── signup.html
├── send.html
└── receive.html

---

## 🚀 Getting Started

### Prerequisites
- Java 17+
- Maven

### Run Locally

1. **Clone the repository**
```bash
git clone https://github.com/saikumardash/sml-project.git
cd sml-project
```

2. **Run the app**
```bash
./mvnw spring-boot:run
```

3. **Open in browser**
http://localhost:8080/signin.html

---

## 📌 How It Works

1. Sign up / Log in to your account
2. On the **Send** page — paste any link and click Generate Code
3. A **6-digit code** is generated
4. On any other device — go to the **Receive** page
5. Enter the code and get the link instantly

---

## 🔮 Future Plans

- [ ] Code expiry timer
- [ ] Copy to clipboard button
- [ ] Link categories and tags
- [ ] QR code instead of 6-digit code
- [ ] Mobile app version

---

## 👨‍💻 Author

**Sai Kumar Dash**  
[GitHub](https://github.com/Sai-Kumar-Dash)
[LinkedIn](https://linkedin.com/in/saikumardash)
