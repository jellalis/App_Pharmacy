# Pharmacy Shop Android App

An Android e-commerce application for a pharmacy, built with **Java** and **Android Studio**.  
Users can register, sign in, browse products, add items to a cart, and place basic orders.

---

## Tech Stack

- **Language:** Java  
- **Platform:** Android (minSdk / targetSdk as configured in `build.gradle`)  
- **IDE:** Android Studio  
- **Backend / BaaS:** Firebase Authentication, Cloud Firestore  
- **Architecture:** Activity/Fragment-based  
- **UI Components:** RecyclerView, Fragments, Material Design components  

---

## Features

- User registration and login using **Firebase Authentication**
- Browse a list of pharmacy products
- View detailed information for each product
- Add/remove products from a shopping cart
- Calculate total price for items in the cart
- Store orders in **Cloud Firestore**
- Basic error handling (invalid input, simple network issues)

---

## Getting Started

### Clone the repository

```bash
git clone https://github.com/jellalis/App_Pharmacy.git
cd App_Pharmacy 
```

### Prerequisites

- Android Studio (latest stable version)
- Java 8+ for Android development
- A Firebase account

## Firebase Setup

- This project uses Firebase for authentication and data storage.
- Go to the Firebase Console  and create a new project.
- Add a new Android app to the project:
- Use your app’s package name (as defined in AndroidManifest.xml).
- Download the generated google-services.json.
- Place google-services.json inside the app/ folder (this file is not committed to the repository).
- In Firebase, enable:
- Authentication (e.g. Email/Password sign-in)
- Cloud Firestore (in test or production mode, depending on your needs)
- Sync the project with Gradle files in Android Studio.

## Possible Improvements

- Improved UI/UX using Material Design 3 components
- Push notifications for order status updates
- Integration with a real payment provider (e.g. Stripe)
- Product search and filtering
- Role-based access (e.g. admin view for managing inventory)
