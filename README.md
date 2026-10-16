<div align="center">
  <!-- Arrastra tu logo a GitHub y reemplaza este enlace -->
  <img src="/logo.png" alt="Quick Price Logo" width="120" />

  <h1>⚡ Quick Price</h1>
  <p><b>Agile & Collaborative Hybrid Inventory Management</b></p>

  <!-- Insignias del repositorio -->
  <p>
    <img src="https://img.shields.io/github/repo-size/Alitan999/QuickPrice?style=for-the-badge&color=blue" alt="Repo Size" />
    <img src="https://img.shields.io/github/license/Alitan999/QuickPrice?style=for-the-badge&color=green" alt="License" />
    <img src="https://img.shields.io/github/last-commit/Alitan999/QuickPrice?style=for-the-badge&color=orange" alt="Last Commit" />
  </p>

  <!-- Insignias de la tecnología -->
  <p>
    <img src="https://img.shields.io/badge/Kotlin-7F52FF?style=for-the-badge&logo=kotlin&logoColor=white" alt="Kotlin" />
    <img src="https://img.shields.io/badge/Android-3DDC84?style=for-the-badge&logo=android&logoColor=white" alt="Android" />
    <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript" />
    <img src="https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white" alt="Tailwind CSS" />
    <img src="https://img.shields.io/badge/Firebase-039BE5?style=for-the-badge&logo=firebase&logoColor=white" alt="Firebase" />
  </p>
</div>

---

## 📖 About the Project

**Quick Price** is an agile, collaborative price checker. Skip complex POS systems; just log the barcode, name, and price. Owners create a store, employees join via an access code, and data syncs in real-time. Search items by name or camera scan to get fast information instantly.

Designed as a **Hybrid Single Page Application (SPA)**, it runs a high-performance web interface inside a native Android Kotlin container, combining web development speed with native hardware access.

## ✨ Key Features

*   🔄 **Real-Time Sync:** Data updates instantly across all devices connected to the same store using Firebase Firestore onSnapshot listeners.
*   📷 **Smart Barcode Scanning:** Integrated `html5-qrcode` engine leveraging native Android camera permissions for rapid 1D and 2D code detection.
*   👥 **Team Synchronization:** Store catalogs are isolated and shared securely via unique access codes (`storeId`).
*   📦 **Full Inventory Control:** Simple CRUD interface to add, edit, or delete products and prices on the fly.
*   🎨 **Modern UI/UX:** Glassmorphism design system, animated aurora backgrounds, and staggered micro-animations built with Tailwind CSS.

---

## 🏗️ Technical Architecture

Quick Price follows a hybrid model:
1.  **Native Container (Kotlin):** Manages the application lifecycle, WebView initialization, and hardware permissions (Camera).
2.  **Frontend UI (HTML/JS/Tailwind):** Handles all business logic, UI rendering, and user interactions.
3.  **BaaS (Firebase):** Manages authentication and real-time NoSQL data storage.

### Data Model Overview
*   **User Profiles:** Manages user roles and links each user account to their respective store identifier.
*   **Store Inventory:** Real-time NoSQL documents storing product details including item codes, descriptions, pricing, metadata tracking on the last editor, and timestamps.

---

## 📱 Screenshots

> **Note:** Drag and drop screenshots of the app directly into the GitHub editor to replace these placeholders!

<div align="center">
  <img src="/QUICK PRICE SCREENSHOTS/Login.jpg" alt="Login Screen" width="220" />
  &nbsp;&nbsp;&nbsp;
  <img src="/QUICK PRICE SCREENSHOTS/Scanner.jpg" alt="Scanner Screen" width="220" />
  &nbsp;&nbsp;&nbsp;
  <img src="/QUICK PRICE SCREENSHOTS/Inventory.jpg" alt="Inventory Screen" width="220" />
</div>

---

## 🚀 How to Use (User Flow)

1. **Authentication:** Log in or register a new account.
2. **Store Setup:** 
   * *Owners:* Generate a new store code.
   * *Employees:* Enter the owner's code to join the store.
3. **Checking Prices:** Use the search bar to type a product name, or tap the barcode icon to scan an item using the device camera.
4. **Managing Inventory:** Navigate to the Inventory tab to add new items (manually or via scanner), edit existing prices, or delete outdated stock.

---

<div align="center">
  <b>Built by</b><br><br>
  <a href="https://github.com/Alitan999">
    <img src="https://img.shields.io/badge/Alitan999-121011?style=for-the-badge&logo=github&logoColor=white" alt="GitHub Profile" />
  </a>
  <br>
  <i>«I like turning ideas into things that actually work.»</i>
</div>
