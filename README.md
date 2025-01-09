# NSU E Canteen - Project

## Project Overview
The **NSU E Canteen** is a web-based cafeteria management system for North South University (NSU) students. It streamlines food ordering from Kashundi, reducing wait times and ensuring a smooth ordering experience. The system features three panels for users, shop owners, and administrators, each tailored to their specific needs.

## Features
### User Features:
- View available food items, including descriptions and prices.
- Place orders online with a hassle-free payment system.
- View and manage orders via a user-friendly interface.

### Shop Owner Features:
- Update and manage the menu, including adding or removing items.
- View and prepare orders for delivery.

### Admin Features:
- Add, edit, or remove users.
- Manage the overall system and monitor performance metrics.

## Problem Statement
The traditional NSU canteen system often results in long queues, particularly during lunch hours. Students struggle to order and receive food within their short breaks. The NSU E Canteen addresses these challenges by allowing students to pre-order food online, make seamless payments, and collect food using a token system.

## Architecture
The system architecture is designed for efficiency and scalability, leveraging technologies such as PHP, JavaScript, MySQL, and AJAX. Key components include:
- **Frontend:** User interfaces for students, shop owners, and admins.
- **Backend:** Database management for users, orders, and menus.
- **Performance Optimization:** Techniques to ensure smooth operation across all modules.

![Architecture Diagram](Page-16.png)

## Use Cases
### 1. Create a New User Account
- **Actor:** User, Shop Owner
- **Description:** Register a new account using NSU ID, email, and password.
- **Outcome:** A user account is successfully created or an error is displayed if the process fails.

### 2. View Menu
- **Actor:** Registered User
- **Description:** Browse available food items, including details and prices.
- **Outcome:** Displays the menu or an error message if unavailable.

### 3. Add/Remove Items from Menu
- **Actor:** Shop Owner
- **Description:** Manage food items by adding, removing, or updating them.
- **Outcome:** Updates menu data in the database.

### 4. Place an Order
- **Actor:** User
- **Description:** Select items, confirm the order, and proceed to payment.
- **Outcome:** Order is placed, and the user is redirected to the payment page.

### 5. Payment and Token Generation
- **Actor:** User, Shop Owner
- **Description:** Make online payments via mobile apps, banking systems, or cards. Generate a token for order retrieval.
- **Outcome:** Payment confirmation and token display.

(For a complete list of use cases, refer to the full document.)

## Development Plan
A phased development approach was adopted:
- **June 15:** Project Proposal and Use Case Diagram.
- **June 29:** Interface design and HTML/CSS/JS development.
- **July 27:** Backend integration with PHP and MySQL.
- **August 3:** Hosting and API integration.
- **August 10:** Mock demo.
- **August 24:** Final project demo.

## Optimization Metrics
The system was optimized for performance, with metrics showing:
- Admin Dashboard: 91% performance.
- Admin Menu: 96% performance.
- Admin Profile: 97% performance.
- User Login: 82% performance.

(Refer to the Performance Optimization section for details.)

## References
- [W3Schools](https://www.w3schools.com/whatis/)
- [Mozilla Developer Network](https://developer.mozilla.org/en-US/docs/Learn)
- [Geeks for Geeks](https://www.geeksforgeeks.org/web-development/)

---

