# 📅 Power BI Calendar – Multi-Calendar Time Intelligence Template
**Developer:** Howard Taylor (Semanticise Inc | OLAP Office)
 **License:** Free to use and adapt with attribution

------

## 🚀 Overview

The **Power BI Calendar** provides a flexible and extensible foundation for **Date, SlicerDate, and Fiscal Time Intelligence** modeling in **Power BI** and **Microsoft Fabric**.
 It’s designed to be an *example and reusable template* that you can easily tailor to your organization’s unique calendar, fiscal, or reporting requirements.

This project demonstrates how to build a configurable and future-proof time dimension framework entirely within Power BI Projects (`.pbip`), leveraging **Power Query (M)**, **DAX**, and **TMDL** definitions.

------

## 🧭 Key Features

✅ **Supports multiple calendar frameworks:**

- Gregorian / Standard Calendar
- Fiscal (custom year-ends)
- ISO 8601 Weeks
- Retail (4-4-5 structure)
- 13-Month Cycles
- Lunar Calendars
- JD Edwards integration (Julian dates)

✅ **Includes pre-built components:**

- Configurable **Date** table (Power Query M-script)
- Dynamic **SlicerDate** table for calendar switching
- **Fiscal Time Intelligence** calculation group
- Full **TMDL model definitions** for integration into `.pbip` projects
- Example of **Role-Playing Dimensions** (Order Date, Ship Date, etc.)

✅ **Ready for enterprise use:**

- Works seamlessly in Power BI Desktop and Microsoft Fabric
- Version-controlled semantic model definitions
- Extensible via **User Defined Functions (UDFs)** and custom measures

------

## 🧩 Files Provided

- `Date.tmdl`
- `SlicerDate.tmdl`
- `FiscalTimeIntelligence.tmdl`
- `Calendar.pbip` (example project)
- `/Config/` – Power Query scripts

TMDL files can be found in:

```
..\Semanticise-Calendar.SemanticModel\TMDLScripts
```

Or open directly in Power BI Desktop using the **TMDL View** (left margin).

------

## ⚙️ How to Use

1. Clone or download the repository:

   ```
   git clone https://github.com/OlapOffice/Calendar.git
   ```

2. Open `Calendar.pbip` in Power BI Desktop.

3. Review and modify the configuration section in the Power Query editor to set your fiscal year-end and date range.

4. Customize the model as needed for your own solution.

------

## 🧠 Training and Documentation

A **free detailed training course** is available covering:

- How to implement and extend the Date and SlicerDate tables
- Building Fiscal Time Intelligence using DAX and UDFs
- Integrating TMDL models into Power BI Projects
- Practical examples of Role-Playing Date tables

📖 Access the full course here: [🧭 Power BI Advanced Date and Slicer Date Modeling – Free Training Course | LinkedIn](https://www.linkedin.com/pulse/power-bi-advanced-date-slicer-modeling-free-training-howard-mnhxe/?trackingId=SPyXP4gHgsO2EaIS9ZxFbQ%3D%3D)


------

## 💬 Contributing & Feedback

This repository is intended as an **example and template**, and it can be customized to suit any solution’s needs.
 We welcome suggestions for improvements or additional features we may not have considered yet.

👉 Open an issue or submit a pull request to share your ideas!

------

## 🏷️ Credits

Developed by **Howard Taylor**
 **© 2025 Semanticise Inc / OLAP Office.** All rights reserved.
