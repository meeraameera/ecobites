# EcoBites

A **mobile application** designed to help households efficiently manage their food inventory, reduce wastage, and promote sustainable consumption.

---

## Problem Statement

Households, including those in Singapore, struggle with **food wastage** due to factors like forgetting grocery purchases and a lack of awareness of expiration dates. This results in items being overlooked, expiring, and ultimately discarded. Food wastage represents a loss of resources and contributes significantly to environmental issues and landfill accumulation.

---

## Project Goal

The primary goal of **EcoBites** is to develop a **mobile app** that helps families manage their food inventory efficiently, encouraging users to fully utilize ingredients before they expire.

---

## Technical Approach & Workflow

- **Scoping:**
  - Defined four core functions: Authentication, Groceries Quantity Tracker, Notification Reminder, and Analytic Tracker, detailing the necessary database operations (CRUD) for each.

- **Database Design:**  
  - Developed **ER Diagram** and **Data Dictionaries** for the `user`, `product`, `analytic_tracker`, and `reminder` tables.  
  - Tables store and link key information such as expiration dates, storage locations, and wastage data.

- **Interface Design:**  
  - Created **high-fidelity prototypes** for key screens: login, home page, filtered inventory views (Fridge, Freezer, Pantry), product adding (Manual/Image), reminders, history, and analytics.

- **Flutter Implementation:**  
  - Implemented the UI structure using a **Widget Tree** (e.g., Scaffold, Column, Row, Card, BottomNavigationBar) for the Home Page and other screens.

---

## Key Challenges Faced

- **Stability Issues:**  
  - Experienced performance problems where the web browser or Android device hung when attempting to implement additional features or enhancements.

---

## Installation & Execution

- Development requires a **mobile framework** (Flutter and Dart).
- Build the app following the designed UI and integrate it with the database structure to manage user data, product inventory, reminders, and analytics.
- Test the app on Android emulators or physical devices for performance and stability.  
  
