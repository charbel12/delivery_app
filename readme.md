# Flutter Eats

Flutter Eats is a multi-app platform similar to Uber Eats, developed using Flutter. The repository contains three separate applications:

- **User App**: For customers to browse restaurants, place orders, and track deliveries.
- **Store App**: For restaurant partners to manage menus, orders, and update availability.
- **Driver App**: For delivery partners to accept orders, navigate, and complete deliveries.

## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Apps Included](#apps-included)
- [Getting Started](#getting-started)
- [Repository Structure](#repository-structure)
- [Contributing](#contributing)
- [License](#license)

## Overview

Flutter Eats is designed to offer a seamless food delivery experience by uniting customers, restaurants, and delivery partners. Built with Flutter, the applications provide a consistent experience across multiple platforms.

## Features

- **User App**
    - Restaurant browsing
    - Order placement and tracking
    - Payment integration

- **Store App**
    - Menu management
    - Order notifications
    - Sales analytics

- **Driver App**
    - Order assignment and navigation assistance
    - Real-time tracking
    - Delivery status updates

## Apps Included

### User App
The User App allows customers to:
- View nearby restaurants and their menus.
- Place orders with ease.
- Monitor order status in real-time.

### Store App
The Store App helps restaurant partners to:
- Manage and update menus.
- Receive and manage orders.
- Monitor sales performance.

### Driver App
The Driver App equips delivery partners to:
- Receive and accept delivery orders.
- Navigate to pick up and drop off locations using in-app maps.
- Update delivery status in real-time.

## Getting Started

1. **Prerequisites**
     - Flutter SDK 2.x or higher.
     - Android Studio or Visual Studio Code.
     - A device/emulator to run Flutter applications.

2. **Installation**
     - Clone the repository:
         ```
         git clone https://github.com/charbel12/delivery_app.git
         ```
     - Navigate into the directory:
         ```
         cd delivery_app
         ```
     - Install dependencies for each app (located in separate directories):
         ```
         cd user_app && flutter pub get
         cd ../store_app && flutter pub get
         cd ../driver_app && flutter pub get
         ```

3. **Running the Apps**
     - To run an app, navigate to its directory and execute:
         ```
         flutter run
         ```

## Repository Structure

```
delivery_app/
├── user_app/      # Customer facing app
├── store_app/     # Restaurant management app
└── driver_app/    # Delivery partner app
```

## Contributing

Contributions are welcome! Please follow these steps:

1. Fork the repository.
2. Create a new branch: `git checkout -b feature/your-feature-name`
3. Commit your changes: `git commit -m "Add new feature"`
4. Push the branch: `git push origin feature/your-feature-name`
5. Open a Pull Request.

