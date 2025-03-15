XNL Banking App

Overview

XNL Banking is a full-featured, cross-platform mobile banking application built with Flutter. It provides secure user authentication, real-time financial data display, secure payment integration, and robust state management. The app integrates with both RESTful APIs and GraphQL endpoints and supports push notifications via Firebase.

Features

Secure User Authentication (Login, Registration, OTP verification)

Real-Time Financial Data Display

Secure Payment Integration (Simulated payment processing)

State Management using Provider

RESTful API and GraphQL Integration

Push Notifications via Firebase

Intuitive UI/UX

Installation

Prerequisites

Install Flutter

Set up an Android/iOS emulator or connect a physical device

Ensure flutter doctor runs without issues

Steps

1.Clone the repository:
git clone https://github.com/yourusername/XNL-Banking.git
cd XNL-Banking

2.Install dependencies:
flutter pub get

3.Run the app:
flutter run

Folder Structure:

XNL-Banking/

│── lib/

│   ├── main.dart         # Entry point of the application

│   ├── screens/          # All UI screens

│   │   ├── login.dart    # Login screen

│   │   ├── register.dart # Registration screen

│   │   ├── home.dart     # Home screen with main functionalities

│   ├── widgets/          # Reusable UI components

│   ├── services/         # API and authentication services

│── assets/               # Images, icons, animations

│── pubspec.yaml          # Dependencies

Usage

Authentication Flow

1. Splash Screen: Displays XNL logo with a transition effect.

2. Registration: New users can register using phone number and email. OTP verification is required.

3. Login: Users enter their phone number and password.

4. Home Page: Displays quick access features:

- Send Money (To Mobile, To Bank & Self)

- Transaction History

- Check Balance

Security Measures

Password validation (5-digit numeric password)

Secure API communication (JWT/OAuth)

Firebase authentication and OTP verification

API Integration

The app interacts with both RESTful and GraphQL APIs:

RESTful API: Handles authentication, transaction history, and balance retrieval.

GraphQL API: Fetches live financial data.

Contribution

Fork the repository

Create a new branch: git checkout -b feature-name

Commit changes: git commit -m 'Added new feature'

Push to branch: git push origin feature-name

Open a Pull Request

License

This project is licensed under the MIT License.
