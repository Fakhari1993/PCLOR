PCLOR – Textile Dyeing Management System

**PCLOR** is a desktop application developed in **C# (.NET Framework, WinForms)** designed to manage and optimize operations in a **textile dyeing factory**.  
It helps automate and monitor various production processes such as dyeing, sales, inventory, banking, and operational data management.

---

Features
**Production & Dyeing Management** – Track and manage dyeing operations and production batches.  
**Factory Process Control** – Handle fabric input, color recipes, and dye process details.  
**Sales & Finance Modules** – Includes banking, shop, and sale management forms.  
**Inventory Tracking** – Keep records of raw materials and finished goods.  
**User-Friendly Interface** – Built with WinForms for easy navigation and usability.  
**Reports & Analytics** – Generate detailed reports for production and business insights.  

---

Tech Stack

| Technology | Description |
| **Language** | C# |
| **Framework** | .NET Framework (WinForms) |
| **Database** | Likely Microsoft SQL Server (configurable via `app.config`) |
| **IDE** | Visual Studio |
| **UI** | Windows Forms Designer |

> **Note:**
> The codebase here is essentially a less complex version of the PCLOR system.
> Just the chosen forms and modules have been brought in here for the sake of examination and learning.
> The fully integrated ERP-based version carries on with more subsystems like payroll, advanced inventory, and production scheduling.


The​‍​‌‍​‍‌ fabric dyeing segment is a very traditional industry and most of the time it still uses manual record-keeping and has disconnected processes. 
This initiative is about digitalizing the operations of the factory in order to have the accuracy increased, the waste reduced, and the traceability heightened throughout the production ​‍​‌‍​‍‌lines.

Integration with ERP System:
PCLOR is developed as a modular subsystem within a larger ERP (Enterprise Resource Planning) environment tailored for textile manufacturing.

It interacts with other ERP modules such as:
Inventory Management – Synchronizes raw materials and finished goods.
Accounting Core – Shares financial data and journal entries.
Human Resources – Integrates employee cost and workload data.
Production Control – Links dyeing batches with upstream and downstream processes.
This modular architecture allows PCLOR to function both as an independent WinForms application and as an integrated ERP component, communicating through shared databases and configuration layers.

