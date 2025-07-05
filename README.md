# ZaynabQaz-HMS-SQL
This project is created in Visual Styudio (C#)  and SQL  Database.
# 🏨 Hotel Management System – C# with SQL Server

A fully functional **Hotel Management System** developed using **C# (.NET)** and connected to **SQL Server 2022**. This Windows Forms application enables hotel staff to manage rooms, bookings, guests, payments, and checkouts through a modern and user-friendly interface.

---

## 🚀 Key Features

- 🛏️ Room Management (Add, Edit, Delete, Search)
- 📆 Booking System with Stay Duration and Amount Calculation
- 👤 Guest Information Storage
- 💳 Payment Handling with Method and Transaction ID
- 🚪 Guest Checkout with Total Payment Calculation
- 🧾 Service Charges Management
- 📊 Dashboard with Summary Labels, Charts, and Tables
- 🔍 Search and Refresh functionality on every form

---

## 🛠️ Technologies Used

- **Language:** C#
- **Platform:** .NET Framework / WinForms
- **Database:** SQL Server 2022
- **IDE:** Visual Studio Code
- **UI Controls:** DataGridView, FlowLayoutPanel, Labels, Panels

## 📁 Project Structure
## 🔧 Database Configuration

1. Open **SQL Server 2022**.
2. Run the `HMS.sql` script to create required tables.
3. Update the connection string in `App.config`:
```xml
<connectionStrings>
  <add name="conn" connectionString="Data Source=YOUR_SERVER_NAME;Initial Catalog=HMS;Integrated Security=True" />
</connectionStrings>
