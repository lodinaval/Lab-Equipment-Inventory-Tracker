# Lab Equipment Inventory Tracker

A Windows Forms (WinForms) application designed to streamline the management, borrowing, and returning of lab equipment in the Logic Circuits Laboratory at Mapúa University. 

This system replaces manual logging, allowing lab assistants and students to track equipment availability for specific experiments.

## 🚀 Features

* **Secure Authentication:** User login system with role-based access for students and laboratory assistants.
* **Inventory Management (CRUD):** Full Create, Read, Update, and Delete capabilities for tracking the laboratory's hardware inventory (e.g., ICs, microcontrollers, wires, breadboards).
* **Borrowing & Returning System:** Real-time tracking of who borrowed specific equipment, when it was issued, and when it is returned.
* **Experiment Templates:** Pre-configured equipment kits that automatically populate the required components for specific Mapúa Logic Circuits laboratory experiments, speeding up the checkout process.

## 🛠️ Tech Stack

* **Frontend:** Windows Forms (WinForms)
* **Database:** Microsoft SQL Server
* **Development Environment:** Visual Studio

## 📸 Screenshots
<img width="1265" height="710" alt="Lab System Dash" src="https://github.com/user-attachments/assets/517faec3-6cb5-4207-9dc9-dd4667be7cbf" />
<img width="1577" height="886" alt="Lab System All Equip" src="https://github.com/user-attachments/assets/8f9ef9ff-7d62-4199-beea-18acc6302586" />
<img width="1232" height="771" alt="Lab System Borrow" src="https://github.com/user-attachments/assets/e396c9a6-73e6-4f55-9a6e-4f4292b9bd57" />
<img width="1265" height="711" alt="Lab System Notif" src="https://github.com/user-attachments/assets/cc81bcf3-e956-4a15-b28b-3286cbc4cd02" />


## ⚙️ Setup and Installation

To run this project locally, you will need Visual Studio and Microsoft SQL Server installed on your machine.

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/lodinaval/Lab-Equipment-Inventory-Tracker.git](https://github.com/lodinaval/Lab-Equipment-Inventory-Tracker.git)
2. **Database Setup:**
   * Open Microsoft SQL Server Management Studio (SSMS).
   * Connect to your local SQL Server instance.
   * In the Object Explorer, right-click on the **Databases** folder and select **Import Data-tier Application...**
   * Click **Next**, choose **Import from local disk**, and browse to select the `InventorySystemDatabase.bacpac` file included in this repository.
   * Follow the wizard prompts to finish restoring the database structure and data.
