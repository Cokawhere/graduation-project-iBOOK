iBook App
E-commerce for books with online payments,

<<<<<<< HEAD
iBook, is a multi-feature Flutter app with:

E-commerce for books (Cart → Shipping Info → Checkout → Paymob Integration).

Chat & Chatbot for user support.

User Profiles for personalization.

Blog Section to share articles and recommendations.


Tech stack:

Flutter + GetX for state management# 📚 Booksi

**Booksi** is a multi-feature Flutter app that brings together e-commerce, chat, and personalization in one elegant experience.

---

##  Features

- 🛒 **E-commerce for Books** — Browse, add to cart, enter shipping info, checkout, and pay via **Paymob Integration**.  
- 💬 **Chat & Chatbot** — Built-in support chat and AI-powered assistant for user help.  
-  **User Profiles** — Personalized dashboards and settings.  
-  **Blog Section** — Read and share articles & recommendations.

---

##  Tech Stack

| Category | Tools |
|-----------|--------|
| Framework | Flutter |
| State Management | GetX |
| Backend | Firebase (Auth + Firestore) |
| Payment Integration | Paymob |
| Architecture | Feature-Based + Modular (MVC, MVVM) |

---

##  Screenshots

| Home | Book Details | Cart | Checkout | Chat | Profile |Login|Blog|
|------|---------------|------|-----------|------|----------|------|-------|
| ![Home](assets/screenshots/home.jpg)<br>![filter](assets/screenshots/filter.jpg) | ![Book Details](assets/screenshots/bookdetails.jpg) | ![Cart](assets/screenshots/cart.jpg)<br>![Cart](assets/screenshots/cart2.jpg) | ![Checkout](assets/screenshots/payment.jpg)<br> ![Checkout](assets/screenshots/payment2.jpg)<br> ![Checkout](assets/screenshots/payment3.jpg) | ![Chat](assets/screenshots/masseges.jpg)<br>![Chat](assets/screenshots/messages2.jpg) | ![Profile](assets/screenshots/profile.jpg) |![login](assets/screenshots/login1.jpg)<br>![login](assets/screenshots/login2.jpg)<br>![login](assets/screenshots/sighup.jpg)|![blog](assets/screenshots/blog.jpg)<br>![blog](assets/screenshots/comment.jpg)|

---

##  About
Built by **Rana**  
Developed with **Flutter** and **GetX**, following clean and scalable architecture principles.


Firebase (Auth + Firestore) as backend

Paymob for secure online payments

Feature-Based Architecture, Modular Code Architecture (MVC, MVVM)
=======
Chat & Chatbot system for user support,

User Profiles for personalization,

Blog section to share articles and updates.


Features
-Chat System: Real-time messaging between users or support team.

-Chatbot: Automated responses to common questions.

-User Profile: Manage personal info and order history.

-Blog Section: Read articles, updates, and book recommendations.

-Browse books with detailed info (title, price, author, cover image).

-Add books to a shopping cart.

-Shipping Information Page to enter delivery details.

-Integrated Paymob payment gateway for card payments.

-Firestore order creation after successful payment.

-Order status lifecycle: pending → paid → shipped → delivered.

Tech Stack

-Frontend: Flutter + GetX

-Backend: Firebase Firestore

-Payments: Paymob Integration

-State Management: GetX Controllers


Order Flow

-User adds items to cart → items are stored inside the GetX state.

-User enters shipping information → stored in the shipping controller.

-User proceeds to checkout with Paymob → payment process starts.

-On payment success → collect:

-items from the cart

-buyerInfo from shipping page

-transactionId from Paymob

-totalPrice and status

-Create order in Firestore → orders collection

-Clear the cart after successful payment.
>>>>>>> d5a795f0a83ce38378b3fc3cbed537ca7176a4f3
