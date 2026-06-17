# EcoDrive - Vehicle Emission Testing & Certification System

EcoDrive is a Windows Forms desktop application developed in C# using .NET Framework and SQL Server. The system automates vehicle registration, dynamic time-slot booking for emission testing lanes, automated fee calculation, and real-time dashboard analytics for system administrators.

## Features

- **Dashboard:** Visualizes real-time metrics, lane usage statistics, and live capacity graphs using integrated Chart controls.
- **Vehicle Registration:** Registers customer details and vehicle specifications (engine capacity, fuel type) securely in a local database.
- **Dynamic Slot Booking:** Enforces lane blocking based on vehicle type (Light/Heavy) and runs live database checks to prevent overbooking for identical time-slots.
- **Payments & Receipts:** Auto-calculates testing fees dynamically and generates a downloadable text receipt post-payment.
- **Administrative Panel:** Decoupled secure admin interface featuring system metrics synchronization, safe database backups, and CSV data export capabilities.

## Tech Stack

- **Frontend:** Windows Forms (WinForms UI)
- **Backend:** C# (.NET Framework)
- **Database:** Microsoft SQL Server (LocalDB)

## Configuration

1. Open the solution file `EcoDrive.sln` inside Visual Studio.
2. Ensure the local database file `EcoDriveDB.mdf` is properly attached in the App_Data directory.
3. Build and run the application.