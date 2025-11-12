# 🍔 I Hungry Burger Shop - File Handling Edition

**Author:** Shameel Shajaad  
**Module:** Object-Oriented Programming & Data Structures and Algorithms (ICET Institute)  
**Language:** Java (NetBeans Project)

---

## 🧾 Description
**IHungryBurgerShop - File Handling Edition** is a **Java Swing-based burger shop ordering system** developed under the **Object-Oriented Programming & Data Structures and Algorithms** module at **ICET Institute**.  

This version introduces **file handling** to store and retrieve customer and order data persistently using text files (`Burger.txt`) through **FileWriter**, **BufferedWriter**, and **BufferedReader**.  
It builds upon earlier versions by maintaining a strong **OOP structure** and **Swing-based GUI**, now enhanced with **data persistence**.

> 💡 This version was developed using **NetBeans IDE** for better project management, GUI layout, and debugging support.

---

## 📌 Features

1. **File-Based Order Management**
   - Automatically creates and updates `Burger.txt` file
   - Saves all orders with customer details and order status
   - Loads and displays stored data on startup

2. **Customer Management**
   - Detects existing customers by phone number
   - Automatically adds new customers to the file
   - Displays full customer order history from stored records

3. **Order Handling**
   - Auto-generates unique order IDs (e.g., B0001, B0002, …)
   - Calculates order totals based on burger quantity
   - Updates and manages order statuses:
     - `0` → Preparing  
     - `1` → Delivered  
     - `2` → Canceled  

4. **Data Structures**
   - Uses arrays and lists to handle in-memory data
   - File storage simulates a mini database
   - Efficient searching and updating operations

6. **Graphical User Interface (GUI)**
   - Designed using **Java Swing (NetBeans GUI Designer)**
   - Includes menus, buttons, and tables for order display
   - Real-time input validation and error handling

---

## 📂 File Database Structure

All order details are stored in a plain text file named **`Burger.txt`**.  
Each line represents a single order record in the following format:

### **Format:**

OrderID,Phone,CustomerName,Quantity,Total,Status  

### **Example Data:**

B0001,0740698249,Shameel Shajaad,4,2000.0,0  
B0002,0740698249,Shameel Shajaad,9,4500.0,1  
B0003,0123456789,Nimal,6,3000.0,0  
B0004,0222222222,Steve Jobs,3,1500.0,2  
B0005,0444444444,Bill Gates,7,3500.0,0  


| Field | Description |
|--------|-------------|
| **OrderID** | Automatically generated ID (e.g., B0001, B0002, …) |
| **Phone** | Customer’s contact number |
| **CustomerName** | Customer’s full name |
| **Quantity** | Number of burgers ordered |
| **Total** | Price × Quantity |
| **Status** | 0 = Preparing, 1 = Delivered, 2 = Canceled |

---

## 📦 Setup & Run Instructions

1. **Clone the Repository**
   ```bash
   git clone https://github.com/ShameelShajaad/I-Hungry-Burger-Shop-File-Handling-Edition-.git

2. **Open in NetBeans**
   -Open NetBeans IDE
   -Go to File → Open Project
   -Select the cloned folder and open it

3. **Ensure Folder Structure**

IHungryBurgerShop-FileHandling-Edition/  
├── src/  
│   ├── iHungryBurgerShop/  
│   │   ├── HomePage.java  
│   │   ├── PlaceOrder.java  
│   │   ├── ViewOrders.java  
│   │   ├── UpdateOrder.java  
│   │   ├── Order.java  
│   │   └── Customer.java  
│   └── Images/  
│       ├── logo.png  
│       ├── burger.png  
│       └── background.jpg  
├── Burger.txt  
└── README.md  


4. **Run the Project**
   -Click the Run button in NetBeans
   -Or, open terminal inside project folder:
   ```bash
   javac src/iHungryBurgerShop *.java
   java src/iHungryBurgerShop/Main
   ```
5. **Important Notes**
   - `Burger.txt` must remain in the **project root directory**.  
   - Do **not rename** or move this file.  
   - Image paths are **relative**, so the `assets/images/` folder must remain unchanged.  

---

## 🧮 Concepts Demonstrated

| **Concept** | **Description** |
|--------------|-----------------|
| **OOP Principles** | Private attributes, getters/setters, and encapsulation |
| **File Handling** | Data stored persistently with FileWriter/BufferedReader |
| **Data Structures** | Uses arrays/lists for data management |
| **Swing GUI** | NetBeans-built user interface with event-driven design |
| **Search & Update** | Efficient record lookup and modification |

---

## ⚙️ Technologies Used

- **Java (JDK 17+)**  
- **NetBeans IDE**  
- **Java Swing**  
- **FileWriter / BufferedReader**  
- **Arrays / Lists for Data Storage**

---

## ⚡ Additional Notes

- Acts as a **mini file-based database system**  
- Built using **pure Java**, no external libraries or frameworks  
- Ideal for coursework demonstrations of **OOP + Data Structures + File Handling**  
- Simulates a **real-world data management system** with easy scalability  

---

## 🏁 Summary

The **IHungryBurgerShop - File Handling Edition** represents the **integration of file storage with OOP and GUI concepts**.  
It provides a realistic simulation of how a small-scale POS system stores and retrieves data without using SQL databases.  

---

### ✅ This project demonstrates proficiency in:
- Object-Oriented Programming (**Encapsulation & Reusability**)  
- Java Swing GUI Development (**NetBeans**)  
- File Handling with Persistent Storage  
- Data Structures and Array/List Management  
- Practical Software Design for Real-World Scenarios  
