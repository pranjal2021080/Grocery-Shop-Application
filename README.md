
---

# 🛒 **Grocery Shop Android Application**

## 📌 **Project Overview**

This repository contains an **Android application for grocery shop owners and customers**.
The application simulates a **multi-shop grocery marketplace**, supporting **inventory management, customer shopping, cart handling, order placement, and delivery estimation**.

The project focuses on **real-world app design**, **role-based access**, and **end-to-end flow from item browsing to order completion**.

---

## 🎯 **Objective**

The goal of this project is to:

* Design a scalable grocery shopping application
* Support multiple shop owners with large inventories
* Allow customers to browse, shop, and place orders safely
* Demonstrate correct stock handling and delivery estimation
* Follow clean code organization and Android development practices

---

## 👥 **User Roles**

The application supports **two distinct user roles**:

### 🏪 **Shop Owner**

Each shop owner:

* Manages their own inventory
* Controls prices and stock quantities
* Views current items and orders
* Operates independently from other shops

### 🛍️ **Customer**

Each customer can:

* Browse items shop-wise or across shops
* Add items (with quantity) to a cart
* Place orders only when all items are in stock
* View estimated delivery time before checkout

---

## 📦 **Core Features**

### 🔹 Multi-Shop Support

* At least **5 shop owners**
* Each shop has **30+ items**
* Total items displayed during demo: **150+**

Each item includes:

* Unique Item ID
* Name
* Image
* Price
* Available stock quantity
* Optional description

---

### 🔹 Inventory Management (Shop Owner)

* Add new items
* Edit item details (price, stock)
* Remove items
* Maintain independent shop inventory
* Simple dashboard view of items and orders

---

### 🔹 Shopping & Orders (Customer)

* Browse items by shop or across all shops
* Add items with desired quantities to cart
* **Atomic order validation**:

  * Order succeeds **only if all items are in stock**
  * Partial orders are not allowed unless explicitly handled
* Stock quantities are updated immediately after successful order

---

### 🔹 Distance & Delivery Estimation

* Customer location obtained via:

  * Manual input or device GPS
* App calculates:

  * Distance between customer and selected shop
  * Estimated delivery time based on distance
* Delivery estimate is shown **before placing the order**

---

## 🧪 **Demo & Evaluation Requirements**

* Display **5 shops × 30 items each**
* Place at least one successful order
* Show:

  * Stock reduction after order
  * Correct delivery time estimation
* Demonstrate both **shop owner** and **customer** flows

---

## 🏗️ **Project Structure**

```
Grocery-Shop-App
├── Grocery-Shop-App.pdf     # Assignment / problem statement
└── Code
    ├── XML_Kotlin_Version   # XML + Kotlin implementation
    └── Compose_Version      # Jetpack Compose implementation
```

The repository is structured to ensure:

* Clear separation of documentation and code
* Easy build and demo
* Professional academic organization

---

## 🛠️ **Technologies Used**

* Android Studio
* Kotlin
* XML layouts
* Jetpack Compose
* Gradle build system

---

## 📚 **Learning Outcomes**

This project demonstrates:

* Android app architecture and UI design
* Role-based application logic
* Inventory and cart management
* Atomic transaction checks
* Distance-based computation
* Clean project structuring and documentation

---

## 📄 **Submission Note**

This repository includes:

* Complete source code
* Assignment PDF



