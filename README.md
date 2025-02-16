# BarberX – Single Vendor Barber Booking App

**BarberX** is an advanced **Android app** designed to streamline barber appointment bookings. This project showcases my **Android development skills** using **modern architectures** and best coding practices. Built with **Kotlin**, it follows industry standards to deliver a seamless and feature-rich experience for both customers and barbers.

---

## Table of Contents

- [Features](#features)
- [Technology Stack](#technology-stack)
- [Prerequisites](#prerequisites)
- [Setup](#setup)
- [App Workflow](#app-workflow)
- [Best Practices Followed](#best-practices-followed)
- [Contributing](#contributing)
- [License](#license)

---

## Features

### Customer Features

- **Browse Barber Profiles**: View barbers’ experience, services, and pricing.
- **Appointment Booking**: Select a barber, choose a slot, and confirm a booking.
- **Secure Payments**: Supports **Stripe/Razorpay** (cash, card, wallet payments).
- **Tip Option**: Add a tip during checkout based on satisfaction.
- **Appointment History**: View past and upcoming appointments.
- **Real-time Notifications**: Get reminders and updates on bookings.

### Barber Features

- **Profile Management**: Update details, working hours, services, and compensation model.
- **Earnings Tracking**: View income categorized by **salary, commission, and tips**.
- **Appointment Management**: Accept/reject bookings, manage availability.
- **Compensation Models**:
  - **Salary-based**: Fixed payments.
  - **Commission-based**: Percentage-based earnings (e.g., 40%-60%).
  - **Chair Rental**: Earnings minus rental fees.
- **Payment History**: Track salary, commission, and tips.
- **Notifications**: Alerts for new bookings and earnings updates.

### Admin Features

- **Manage Barbers & Customers**: Add, edit, and track users.
- **Earnings Overview**: Monitor barbers’ salary, commissions, and rental fees.
- **Automated Payments**: Handle barber payouts based on compensation models.
- **Reports & Analytics**: Generate insights on business performance.

---

## Technology Stack

This project demonstrates proficiency in:

- **Kotlin**
- **Android SDK**
- **MVVM Architecture**
- **Firebase (Authentication, Database, Push Notifications, Analytics)**
- **Stripe/Razorpay**
- **Room Database**
- **Retrofit**
- **Hilt/Dagger**
- **Jetpack Compose**
- **JUnit, Espresso, Mockito**
- **Glide**
- **Stetho**
- **OAuth 2.0**
- **WorkManager**
- **GitHub Actions**

---

## Prerequisites

Make sure you have the following installed:

- **Android Studio** (latest version)
- **Java JDK** (version 8 or higher)
- **Kotlin** (latest stable version)

---

## Setup

### Step 1: Open Project in Android Studio

- Open **Android Studio** and select **Open an Existing Project**.
- Navigate to the **BarberX** project folder and open it.

### Step 2: Set up Firebase

- Set up **Firebase** in the project to enable authentication, database, and push notifications.
- Download the **google-services.json** file and place it in the **app/** directory.

### Step 3: Run the App

- Click **Run** to launch the app on your emulator or physical device.

---

## App Workflow

### Customer Side:

- Browse barbers and services.
- Book appointments and make payments.
- Receive notifications for upcoming bookings.

### Barber Side:

- Manage profile, services, and schedule.
- Track earnings from salary, commission, and tips.
- Accept/reject bookings.

### Admin Side:

- Manage barbers, customers, and appointments.
- View financial reports and performance analytics.

---

## Best Practices Followed

- **Jetpack Compose**: Modern UI toolkit for building native UIs in a declarative manner.
- **Kotlin Coroutines**: Efficient background task handling.
- **LiveData/Flow**: Real-time UI updates.
- **Room Database**: Offline functionality for seamless experience.
- **Retrofit**: Optimized API calls.
- **Dependency Injection**: Hilt/Dagger for modular design.
- **MVVM Architecture**: Clean and scalable project structure.
- **Unit Testing**: JUnit, Mockito, and Espresso ensure robust testing.

---

## Contributing

Contributions are welcome! To contribute:

1. **Fork the repository** and create a new branch:
   ```bash
   git checkout -b feature/your-feature-name
   ```
2. **Make your changes** and write tests for new functionality.
3. **Submit a pull request** with a detailed description of your changes.

---

## License

This project is licensed under the **MIT License** - see the [LICENSE](LICENSE) file for details.

