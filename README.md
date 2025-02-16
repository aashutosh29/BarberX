# **BarberX – Single Vendor Barber Booking App** 💈📲

**BarberX** is a simple and efficient **Android app** designed to help barbers and customers manage appointments. The app leverages modern Android development practices to deliver a seamless user experience with a focus on clean architecture, performance, and scalability. Built with **Kotlin** and following best practices, this project demonstrates my Android development skills and proficiency in building production-level applications.

---

## **Table of Contents**

1. [Features](#features)
2. [Technology Stack](#technology-stack)
3. [Code Structure](#code-structure)
4. [Installation](#installation)
5. [Setup](#setup)
6. [App Workflow](#app-workflow)
7. [Best Practices](#best-practices)
8. [Contributing](#contributing)
9. [License](#license)

---

## **Features**

### **Customer Features**
- **Browse Barber Profiles**: View barbers’ experience, specialization, and pricing.
- **Booking System**: Select a barber, pick a time slot, and book an appointment.
- **Payment Integration**: Secure payments via **Stripe/Razorpay** (cash, card, wallet).
- **Tip Option**: Add a tip during checkout based on service satisfaction.
- **Appointment History & Management**: View past and upcoming appointments.

### **Barber Features**
- **Profile Management**: Update personal details, working hours, services, and compensation model (Salary, Commission, or Chair Rental).
- **Earnings Tracking**: View real-time earnings categorized by **salary, commission percentage, and tips**.
- **Booking & Appointment Management**: Accept or reject bookings, manage availability, and view upcoming schedules.
- **Compensation Model Support**:
    - **Salary-based**: Fixed weekly/monthly payments.
    - **Commission-based**: Automatic earnings calculation based on service percentage (e.g., 40%-60%).
    - **Chair Rental**: Earnings tracking minus chair rental fees.
- **Payment History**: Track income breakdown from multiple sources (salary, commission, and tips).
- **Notifications & Alerts**: Get updates for new bookings, tips received, and earnings reports.

### **Admin Features**
- **Barber & Customer Management**: Add, edit, or remove barbers and customers.
- **Earnings Overview**: Admin can monitor barbers’ salary, commissions, and chair rental fees.
- **Payment Scheduling**: Manage and automate barber payouts based on their compensation model.
- **Reports & Analytics**: Generate reports on bookings, earnings, and platform performance.

---

## **Technology Stack**

This project showcases proficiency in the following technologies:

- **Kotlin**: Modern, expressive, and null-safe programming language for Android development.
- **Android SDK**: Native development using the latest Android APIs.
- **MVVM Architecture**: A clean architecture pattern used for better testability and maintainability.
- **Firebase**: Real-time database, authentication, and push notifications.
- **Stripe/Razorpay**: Payment gateway for secure transactions.
- **Room Database**: Local storage for offline functionality.
- **Retrofit**: For making API calls to the backend.
- **Hilt/Dagger**: Dependency injection frameworks used to manage app components and simplify testing.
- **Jetpack Compose**: A modern toolkit for building native UIs with less code and improved productivity.
- **JUnit**: For unit testing and ensuring robustness.
- **Espresso**: For UI testing to verify user interactions.
- **Mockito**: For mocking dependencies in unit tests to isolate components and test behavior.
- **Glide**: Efficient image loading and caching for barber profiles and services.
- **Firebase Analytics**: Tracks app usage and events to understand user behavior.
- **Stetho**: A debugging tool that allows you to inspect your app’s network requests, database, and shared preferences.
- **Firebase Authentication**: Handles user authentication, including Google and email/password logins.
- **OAuth 2.0**: For integrating third-party authentication (e.g., Facebook, Google).
- **WorkManager**: For handling background tasks, such as appointment reminders and data syncing.
- **GitHub Actions**: Automates continuous integration, testing, and deployment workflows.

---

## **Code Structure**

The app follows **MVVM (Model-View-ViewModel) Architecture** with a clean and modular approach:

- **Model**: Defines data entities and manages database interactions.
- **View**: Composed of Activities/Fragments (or Jetpack Compose components) to render UI.
- **ViewModel**: Handles UI-related logic and manages data using LiveData/Flow.
- **Repository**: Mediator between ViewModel and data sources (API, Firebase, Room).
- **Use Cases**: Encapsulates business logic for modularity.

This structure ensures scalability, testability, and ease of maintenance.

---

## **Installation**

### **Clone the Repository**
To get started with the project, clone this repository to your local machine using:

```bash
git clone https://github.com/aashutosh29/barberx.git

