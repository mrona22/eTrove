# 🎓 eTrove – Student Marketplace App

eTrove is a student-only marketplace application built in collaboration with a startup. It enables students to buy and sell items within their university community. The platform uses institutional `.edu` emails to restrict access to verified students, ensuring a private and relevant environment for each campus.

## 🚫 Not Open Source

This project is **not open source**. The repository exists for demonstration purposes only and does not contain the app’s full source code.

All intellectual property rights are retained by the startup behind the app. Please do not copy, distribute, or reuse any part of this codebase without permission.

## 🧪 Demo Login

You can try a demo version of the app using the following credentials:
(Keep in Mind currently only available on the Appstore US)

email: etrovedemo@gmail.com
password: 12345678


> 🔐 This demo login allows access to the main features of the app in a controlled environment. Please note that access is limited and subject to change.

## ⚙️ Tech Stack

- **SwiftUI** for frontend UI
- **Firebase** for:
  - Authentication with email verification
  - Firestore for real-time database and search
  - Cloud Functions for backend logic
  - Push notifications
- **Custom debounced search**, infinite scroll, and category filtering
- **Role-based access control** via `.edu` domain check and school-based content filtering

## ✍️ About This Project

I worked on this project while collaborating with a student-focused startup. My responsibilities included:

- Building the user registration flow, including verification and school extraction logic  
- Designing and implementing the Firestore-backed search experience  
- Handling asynchronous flows and loading states with Swift Concurrency  
- Supporting push notifications  
- Ensuring smooth UX with debounced search and category filters  

---

If you’d like to know more or are interested in collaborating, feel free to reach out!
