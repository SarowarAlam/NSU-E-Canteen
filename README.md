# NSU E Canteen - Project

## Project Overview
The **NSU E Canteen** is a web-based cafeteria management system for North South University (NSU) students. It streamlines food ordering from Kashundi, reducing wait times and ensuring a smooth ordering experience. The system features three panels for users, shop owners, and administrators, each tailored to their specific needs.

![image](https://github.com/user-attachments/assets/bf44af33-2d9b-47a8-bb66-522f303df412)

![image](https://github.com/user-attachments/assets/b7b04bbc-c7e2-4dab-b4f4-044dc1ae691f)

![image](https://github.com/user-attachments/assets/c83646c3-b5d7-438c-b25d-06a15635b26e)



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


![image](https://github.com/user-attachments/assets/d3578db6-bbba-4628-8523-5140d75b69f7)



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

## Optimization Metrics
The system was optimized for performance, with metrics showing:
- Admin Dashboard: 91% performance.

![image](https://github.com/user-attachments/assets/8299d53c-672e-49fe-839d-d84e997da7de)

  
- Admin Menu: 96% performance.

![image](https://github.com/user-attachments/assets/8507de82-4aab-45ff-b65e-be791f01d6d2)


- Admin Profile: 97% performance.

![image](https://github.com/user-attachments/assets/fd648fa9-6c55-471d-bf53-2a141e308321)


- Admin Userlist Optimization: 91% performance.

![image](https://github.com/user-attachments/assets/1945d232-7f45-4dce-b5b5-bbadf38b63fa)

- User Login: 82% performance.

![image](https://github.com/user-attachments/assets/8d6494c4-ad07-408f-8d00-1d5743126799)





## References
- [W3Schools](https://www.w3schools.com/whatis/)
- [Mozilla Developer Network](https://developer.mozilla.org/en-US/docs/Learn)
- [Geeks for Geeks](https://www.geeksforgeeks.org/web-development/)

---

