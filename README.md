# ⚡ Electricity Bill Generator Using Python

A professional Python console application that calculates an electricity bill based on the number of units consumed, applies a senior citizen discount, adds a fixed charge, calculates GST, and generates a detailed bill.

---

## 📌 Project Description

The **Electricity Bill Generator** is a beginner-friendly Python project that demonstrates the practical use of:

- User Input
- Variables
- Arithmetic Operators
- Conditional Statements (`if`, `elif`, `else`)
- Business Logic
- Billing System
- Formatted Output

This project simulates a real-world electricity billing system.

---

## 🚀 Features

- Accepts consumer details
- Calculates electricity charges based on units consumed
- Applies Senior Citizen Discount (10%)
- Adds Fixed Charge
- Calculates 18% GST
- Generates a complete electricity bill
- Simple and easy-to-understand code

---

## 🛠 Technologies Used

- Python 3

---

## 📋 Inputs

- Consumer Name
- Consumer ID
- Units Consumed
- Senior Citizen Status (Yes/No)

---

## ⚙ Billing Rules

### Electricity Charges

| Units Consumed | Rate |
|---------------:|------|
| 0 – 100 | ₹5 per unit |
| 101 – 300 | ₹7 per unit |
| Above 300 | ₹10 per unit |

### Senior Citizen Discount

- Yes → **10% Discount**
- No → **No Discount**

### Fixed Charge

- ₹200

### GST

- **18%**

---

## 🧮 Formula Used

```text
Electricity Charge = Units × Rate

Amount After Discount =
Electricity Charge − Discount

GST =
(Amount After Discount + Fixed Charge) × 18%

Final Bill =
Amount After Discount + Fixed Charge + GST
```

---

## 💻  Output

```text
Enter Consumer Name... Mohit
Enter Consumer ID... 425854894426
Enter Unit Consumed... 1200
Enter Senior Citizen (Yes/No) No

=========== Electricity Bill ===============

Consumer Name        : Mohit
Consumer ID          : 425854894426
Unit Consumed        : 1200
Electricity Charge   : 12000
Fixed Charge         : 200
Discount             : 0
GST                  : 2196.0
Total Bill           : 14396.0
```

---

## 📂 Project Structure

```
Electricity-Bill-Generator/
│
├── electricity_bill.ipynb
├── README.md
```

---

## 🎯 Learning Outcomes

By building this project, you will understand:

- Python Input & Output
- Conditional Statements
- Business Logic Implementation
- Billing System Development
- Mathematical Calculations
- Code Organization
- GitHub Project Documentation

---

## 👨‍💻 Author

**Mohit Batheja**

Python Developer | Learning Data Analytics & Machine Learning
