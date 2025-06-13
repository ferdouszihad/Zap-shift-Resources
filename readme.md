# Zap Shift Resources

Welcome to **Zap Shift Resources**!  
A curated collection of tools, guides, and assets for developing robust parcel management systems.

---

## 📊 System Overview Table

| Role               | Key Responsibilities                                                                      | Earnings/Benefits                              |
| ------------------ | ----------------------------------------------------------------------------------------- | ---------------------------------------------- |
| **Merchant**       | - Book parcels<br>- Pay charges<br>- Track status<br>- Review service                     | - Real-time tracking<br>- Feedback opportunity |
| **Admin**          | - Assign agents<br>- Manage routing<br>- Oversee warehouses<br>- Monitor operations       | - System control<br>- Operational oversight    |
| **Delivery Agent** | - Collect/Deliver parcels<br>- Update status<br>- OTP confirmation<br>- Warehouse handoff | - ৳20 per delivery                             |

---

## 🛒 Pricing Structure

| Parcel Type      | Weight    | Within City | Outside City/District |
| ---------------- | --------- | ----------- | --------------------- |
| **Document**     | Any       | ৳60         | ৳80                   |
| **Non-Document** | Up to 3kg | ৳110        | ৳150                  |
| **Non-Document** | >3kg      | +৳40/kg     | +৳40/kg +৳40 extra    |

---

## 🚚 Delivery Workflow

```mermaid
flowchart TD
    A[Merchant Books Parcel] --> B[System Calculates Charge]
    B --> C[Payment & Tracking ID]
    C --> D[Admin Assigns Pickup Agent]
    D --> E{Within City?}
    E -- Yes --> F[Pickup Agent Collects Parcel]
    F --> G[Status: In Transit]
    G --> H[Ready for Delivery]
    H --> I[OTP Sent to Customer]
    I --> J[Delivery Confirmed]
    J --> K[Agent Earns ৳20]
    E -- No --> L[Submit to Origin Warehouse]
    L --> M[Inter-District Transit]
    M --> N[Arrive at Destination Warehouse]
    N --> O[Assign Local Delivery Agent]
    O --> P[OTP Delivery to Customer]
    P --> Q[Agent Earns ৳20]
```

---

## 🗂️ Key Features

- **Automated Pricing & Tracking**
- **Role-based Access & Workflow**
- **OTP-based Secure Delivery**
- **Nationwide Coverage (64 districts)**
- **Transparent Commission Structure**

---

---
