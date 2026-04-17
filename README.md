# 🐟 FishLedger

A **Vanilla JavaScript Application** built to digitalize and simplify fish sales management for wholesalers and fishing boat owners. Traditionally, sellers rely on **pen and paper** to record fish container prices, calculate totals, and distribute profits. This app automates the entire process, saving valuable time and reducing manual errors.

---

## 🚀 Features

### 🔹 Sales Management

- Add, edit, delete, and view sales records.
- Record sales by **container price** or by **Hilsa** using the local measurement system:
  - **1 Mon = 40 Kg**
  - Hilsa sold by **Mon, Kg, and Gram** with a fixed per-Mon price.
- Multiple sizes/types of Hilsa fish supported with different rates.
- Automatically calculates total sales amount.

### 🔹 Profit Calculation

- Apply **commission (15%)** automatically to the gross total.
- Deduct additional **costs** to calculate net profit.
- Divide profit between:
  - **Boat Owner (8 portions)**
  - **Staff (7 portions)**

- Staff’s share is distributed based on roles:
  - **Captain:** 3x of a single staff’s portion
  - **Assistant Captain, Chef, Engine Driver:** 1.5x of a single staff’s portion
  - **Other Staff:** 1 portion each

### 🔹 Additional Features

- **Mobile-first design** for easy use in the marketplace.
- Uses **Local Storage** to store data for the current market period.
- Export sales and profit details in **PDF format**.

---

## 🛠️ Tech Stack

- **HTML5**
- **CSS3**
- **Vanilla JavaScript (ES6)**
- **Local Storage API**
- **PDF Export**

---

## 📱 Usage

1. Enter seller name, container price, or Hilsa Weight details (Mon, Kg, Gram).
2. Add multiple records as needed.
3. Enter costs after sales.
4. Get automatic calculation of:
   - Total Sales
   - Net Profit (after commission & costs)
   - Profit distribution (Owner & Staffs)
5. Download the report as **PDF**.
