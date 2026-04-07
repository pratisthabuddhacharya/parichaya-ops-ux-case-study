# Case Study: Parichaya Ops MVP
**Internal Operations App for Parichaya Advertising, Pokhara**

## 📌 Project Overview
Parichaya Advertising is a premier advertising firm in Pokhara, Nepal. As the company scaled, manual coordination became a bottleneck. This project is an MVP (Minimum Viable Product) designed to digitize the order lifecycle—from intake to installation—focusing on speed, trust, and operational clarity.

## ⚠️ The Problem
Before this solution, Parichaya faced several operational challenges:
* **Fragmented Data**: Design files and client requirements were scattered across WhatsApp chats.
* **Inventory Blindness**: No real-time tracking of flex rolls, vinyl, or LED frames.
* **Coordination Gaps**: Difficult to track which staff member was assigned to specific high-priority banners or billboards.

## 💡 The Solution
A "no-nonsense" internal mobile app that acts as a centralized "Source of Truth." [cite_start]It eliminates the need for constant administrative check-ins by empowering staff to manage their own workflows.

## 🔍 Phase 1: Research & Strategy
### User Needs (The Requirement Log)
* **Zero Bureaucracy**: Removed the admin bottleneck; staff claim work based on availability.
* **High-Trust Environment**: Designed for a small, expert team where micromanagement is unnecessary.
* **Asset Centrality**: Every order stores its own logos, links, and PDF attachments in one digital folder.
* **Traffic Light Status**: An instant visual priority system:
    * 🔴 **Red**: Not assigned / Not started.
    * 🟡 **Yellow**: Assigned / In progress.
    * 🟢 **Green**: Ready / Completed.

## 🛠️ Phase 2: UX Decision Log
### 1. Single-Screen Order Entry
* **Decision**: I rejected a standard 3-step wizard (Order → Customer → Payment).
* **Reason**: In a high-traffic shop, speed is everything. I combined item details and customer info into one scrolling screen to ensure sales staff can finish an entry while the customer is still at the counter.

### 2. "Deadline-First" Notifications
* **Decision**: Implemented a notification center sorted by due date.
* **Reason**: The team needs to know what is due *today* before they look at new orders. Overdue tasks are highlighted to trigger immediate action.

### 3. Self-Assignment Workflow
* **Decision**: Added an "Assign to Me" button on all order details.
* **Reason**: To reduce administrative overhead. If a printer or designer is free, they can claim an unassigned job instantly without waiting for a manager.

## 🎨 Phase 3: Visual Identity & Psychology
I strictly followed Parichaya's brand guidelines while applying functional UX psychology:

* **Strategic Use of Red**: While **Primary Red** is the brand color], I used it sparingly for branding and "Danger" actions (Delete/Cancel) to avoid user anxiety.
* **The Green CTA**: I chose **Secondary Green** (the complementary color of the brand red) for all primary Call-to-Action buttons.
    * **Logic**: Green signifies "Go" and "Success." In a fast-paced environment, using green for "Confirm Payment" or "Take Order" provides a positive mental model and reduces the stress associated with "Alert" colors.

## 🏗️ Phase 4: Product Architecture

| Component | MVP Function | Design Choice |
| :--- | :--- | :--- |
| **All Products** | Price lookup & Quick Order. | Table-based for quick scanning of sizes vs. rates. |
| **Order Summary** | Payment breakdown (Advance/Remaining). | Clear bold totals to avoid "hisab" errors. |
| **Staff Directory** | Manage roles and contact details. | Simple list with quick-edit capabilities. |
| **Customer Directory** | Contact history and location details. | Integrated "View All Orders" for loyalty tracking. |

## 📝 Reflections
This design isn't about fancy animations; it’s about making sure a billboard gets printed with the right logo and hung on time in New Road or Lakeside. By focusing on High Trust and Low Bureaucracy, the app becomes a partner to the staff, not a monitor.

## 💻 Screens
<img width="1736" height="1523" alt="login stuff" src="https://github.com/user-attachments/assets/e2e190a8-8311-4b3d-a01a-fbbcc001d663" />
<img width="2048" height="1810" alt="takeorder" src="https://github.com/user-attachments/assets/a72243df-1e3d-45a8-849e-7169b90b1519" />
<img width="1736" height="1063" alt="orderdetails" src="https://github.com/user-attachments/assets/a6ff4bb9-2c60-4329-a803-ee7cc56ecceb" />
<img width="1720" height="576" alt="itemdetails" src="https://github.com/user-attachments/assets/2973b930-7dc7-461f-bb85-d10a66b2025d" />
<img width="1891" height="1062" alt="customer and staff" src="https://github.com/user-attachments/assets/d2ea508e-f464-4cee-94d9-ccb945249f9f" />
<img width="1400" height="2048" alt="edit order and notificszation" src="https://github.com/user-attachments/assets/f0561f36-0de4-4f1d-ae02-c6e8069e50bb" />


