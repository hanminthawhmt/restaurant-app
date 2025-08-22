# 🍽️ Restaurant App

This is a **mobile restaurant management application** developed as a **second-year Mobile Application Project**. The app is built using **Flutter** and **Firebase** and is designed to streamline restaurant operations across three key roles: **Waiter**, **Chef (Kitchen)**, and **Cashier**.  

---

## 🚀 Features  

### 👨‍🍳 Chef (Kitchen)  
- View incoming customer orders  
- Update order status (e.g., "In Progress", "Ready to Serve")  
- Send orders back to waiters once food is prepared  

### 👨‍💼 Waiter  
- Take customer orders and send them directly to the kitchen  
- View the status of placed orders  
- Get notified when food is ready to serve  

### 💰 Cashier  
- Take customer orders as well  
- Handle billing and checkout  
- Manage customer reservations  

---

## 🛠️ Technology Stack  
- **Flutter** → Cross-platform mobile application development  
- **Firebase** → Backend services (Authentication, Firestore Database, Notifications, etc.)  

---

## 📱 Installation & Setup  

1. Clone this repository:  
   ```bash
   git clone https://github.com/yourusername/restaurant-app.git
   cd restaurant-app
2. Install dependencies:
   flutter pub get
3. Configure Firebase
   - Create a Firebase project in the Firebase Console
   - Add Android and/or iOS apps and download the google-services.json (Android) or GoogleService-Info.plist (iOS)
   - Place them in the respective android/app and ios/Runner directories
4. run the app -> 
   flutter run

Objectives
    - Provide a smooth, digital solution for restaurants to manage orders, reservations, and billing
    - Improve coordination between waiters, chefs, and cashiers with real-time updates
    - Gain hands-on experience in Flutter mobile development and Firebase backend integration
