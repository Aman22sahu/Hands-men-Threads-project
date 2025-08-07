# HandsMen Threads: Elevating the Art of Sophistication in Men's Fashion

## 🧵 Project Overview

**HandsMen Threads** is a Salesforce-based premium tailoring management platform designed to transform the bespoke men’s fashion experience. The solution streamlines custom tailoring operations, automates client communications, and enhances order tracking with a focus on personalization and efficiency.

Built using Salesforce tools such as Custom Objects, Lightning Apps, Flows, Apex Triggers, Validation Rules, and Email Templates, this application is ideal for tailoring businesses seeking to embrace digital transformation.

---

## 🎯 Objectives

- Streamline men's bespoke tailoring operations.
- Improve customer experience with personalized workflows.
- Automate order confirmation, alerts, and feedback mechanisms.
- Ensure secure, role-based access using Salesforce Profiles and Roles.
- Enhance data accuracy through validation and automation.

---

## 🛠️ Features & Technologies Used

| Feature                     | Description                                                                 |
|----------------------------|-----------------------------------------------------------------------------|
| **Salesforce Lightning App**     | Custom app interface to manage all objects and modules.                    |
| **Custom Objects**         | Orders, Customers, Fabrics, Tailors, Loyalty Points                          |
| **Tabs**                   | Easy navigation for each object                                             |
| **Validation Rules**       | Ensure accurate order entries (e.g., delivery date > order date)            |
| **Profiles & Roles**       | Secure access for Admin, Tailor, and Support users                          |
| **Permission Sets**        | Extra permission granularity without changing profiles                      |
| **Email Templates & Alerts** | Auto-confirmations, stock alerts, loyalty rewards                           |
| **Flows**                  | Order submission, fabric stock monitoring, and loyalty automation           |
| **Apex Triggers**          | Loyalty point allocation and status updates                                 |

---

## 📌 Project Modules

### 1. **Developer Org Setup**
Created a dedicated Salesforce Developer Org for app development and testing.

### 2. **Custom Object Creation**
Created objects for Orders, Customers, Fabrics, and Loyalty Points with fields such as:
- Customer Name
- Measurement Details
- Fabric Code
- Order Status

### 3. **Lightning App Interface**
Built a custom Lightning App combining relevant tabs and tools for users.

### 4. **Validation Rules**
Examples:
- Order delivery date must be after the order date
- Mandatory fields cannot be left blank

### 5. **User Profiles and Roles**
- Admin: Full access
- Tailor: Assigned orders only
- Support: Read-only with permission set access

### 6. **User Creation**
Created multiple users to simulate real-time operations across roles.

### 7. **Email Templates & Alerts**
Branded HTML templates for:
- Order Confirmations
- Low Stock Alerts
- Loyalty Milestone Achievements

### 8. **Flow Implementation**
- Automated customer feedback email after order delivery
- Auto fabric reordering when stock drops below threshold

### 9. **Apex Triggers**
- Automatically assign loyalty points after every completed order
- Custom logic to notify tailors based on workload

---

## 💡 Real-World Use Case

> A customer places an order with "The Dapper Stitch" for a custom suit. The Salesforce app stores their details and preferences, sends a confirmation email, and assigns the order to a tailor. When fabrics run low, a flow triggers a restock alert. After five completed orders, the customer receives loyalty points via an Apex trigger and a personalized reward email.

---

## 📸 Screenshots

*(Add your screenshots here)*  
Example placeholders:
- [ ] Order Object View  
- [ ] Tailor Dashboard  
- [ ] Email Alert Template  

---

## 🚀 How to Run

> This project is built on Salesforce Developer Org. To try it yourself:
1. Sign up at: [https://developer.salesforce.com/signup](https://developer.salesforce.com/signup)
2. Clone this repository.
3. Use Salesforce Setup > Object Manager to recreate the custom objects.
4. Use Flow Builder and Apex Developer Console to implement business logic.

---

## 🙌 Author

**Aman Sahu**  
Salesforce Developer Trainee  
Project: SkillWallet | AgentBlazer Champion Program  
https://drive.google.com/file/d/19sHFGOtHX-yMktDmFa3T0FP-6VgdXz1B/view?usp=sharing


