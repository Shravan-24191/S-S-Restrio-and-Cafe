# S-S-Restrio-and-Cafe
# S&S Restro & Cafe 🍽️

**S&S Restro & Cafe** is a Python-based restaurant billing and payment project designed to simulate a simple restaurant ordering system.

The project allows customers to select food items from a menu, enter quantities, generate a detailed bill, and choose a payment method. For UPI payments, the project generates a dynamic QR code containing the customer's total bill amount.

## 🚀 Features

* Customer name and mobile number input
* Digital restaurant menu
* Multiple item ordering
* Quantity-based billing
* Automatic item-wise price calculation
* Automatic grand total calculation
* Total quantity/item calculation
* Multiple payment options:

  * Cash
  * UPI & QR
  * Net Banking & Card
  * Coupon
* Dynamic UPI QR code generation
* Final bill display
* Simple and user-friendly console interface

## 🍕 Menu

| Item       |        Price |
| ---------- | -----------: |
| Pizza      |  ₹250 / Unit |
| Burger     |  ₹150 / Unit |
| Pasta      | ₹180 / Plate |
| Coffee     |    ₹50 / Cup |
| Cold Drink |  ₹50 / Litre |
| Thali      |  ₹80 / Plate |

## 🛠️ Technologies Used

* **Python**
* Dictionary
* Tuple
* List
* `while` loop
* `for` loop
* Conditional statements
* User input
* String formatting
* Basic billing calculations
* **qrcode** library
* **Pillow (PIL)**

## 📦 Python Libraries

Install the required libraries using:

```bash
pip install qrcode[pil]
```

The project uses:

```python
import qrcode
from PIL import Image
```

## 🔄 How the Project Works

### 1. Customer Details

The program first asks for:

* Customer name
* Mobile number

### 2. Menu Display

The restaurant menu is displayed with item numbers and prices.

### 3. Order Selection

The customer enters an item number and quantity.

The program continues accepting items until the customer enters:

```text
0
```

### 4. Bill Calculation

For every selected item:

```text
Total Price = Quantity × Price
```

The selected item is stored in the bill list.

### 5. Final Bill

The program displays:

* Customer name
* Contact number
* Ordered items
* Quantity
* Rate
* Item total
* Total items
* Grand total

### 6. Payment

The customer can select a payment method.

If **UPI** is selected, a UPI payment link is generated using the final bill amount and converted into a QR code.

Example:

```text
upi://pay?pa=UPI_ID&pn=Shravan%20Kumar&am=500&cu=INR
```

## 📊 Example

```text
Customer Name : Shravan
Contact No    : XXXXXXXXXX

Pizza   | Qty: 2 | Rate: 250 | Total: 500
Coffee  | Qty: 2 | Rate: 50  | Total: 100

Total Items : 4
Grand Total : 600

Payment Method : UPI
Please Scan QR Code
```

## 🎯 Project Objective

The main objective of this project is to create a simple restaurant billing application while practicing Python programming concepts such as:

* Variables
* Data types
* Dictionaries
* Lists
* Tuples
* Loops
* Conditional statements
* User input
* Calculations
* External Python libraries

## 🔮 Future Improvements

The project can be extended with:

* GST calculation
* Discount and coupon system
* Restaurant table number
* Order ID generation
* Date and time on the bill
* Database connectivity using MySQL
* GUI using Tkinter
* Customer order history
* Digital receipt generation
* PDF bill generation
* Sales and revenue reports
* Admin login
* Inventory management


**Shravan Kumar**

Python | SQL | Data Analytics | Data 
