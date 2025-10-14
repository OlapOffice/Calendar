# 📅 Power BI Calendar – Multi-Calendar Time Intelligence Template
**Developer:** Howard Taylor (Semanticise Inc | OLAP Office Inc)
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

1. ## ⚙️ How to Use

   1. **Clone or download the repository:**

      ```
      git clone https://github.com/OlapOffice/Calendar.git
      ```

   2. **Open the project:**
       Launch `Calendar.pbip` in **Power BI Desktop** (or Fabric workspace) to explore the model and visuals.

   3. **Review the configuration:**
       In **Power Query**, open the `Date` query and adjust the configuration section to define:

      - Start and end dates
      - Fiscal year-end month
      - Optional retail or lunar calendars

   4. **Use the Calendar Template page:**

      - The included **“Page Calendar Template”** report page serves as a *starting point* for building new analytics views.
      - To create a new report page, **duplicate this template** and adapt it for your specific use case — for example, Sales, Financials, or Operations.
      - The **Calendar visuals, slicers, and measures** can be easily tailored to display the relevant **Calendar, Fiscal, or ISO** views based on the slicer selection.

   5. **Integrate into your solution:**

      - Copy the `.tmdl` files from

        ```
        ..\Semanticise-Calendar.SemanticModel\TMDLScripts
        ```

        into your Power BI Project or Fabric Semantic Model folder.

      - Open Power BI Desktop and enable the **TMDL View** to confirm the imported Date, SlicerDate, DateRolePlaying, and FiscalTimeIntelligence definitions.

      - Mark `Date` as the official Date Table, validate relationships, and refresh.

   6. **Customize further:**

      - Extend the model by adding your organization’s **custom fiscal logic**, **UDFs**, or **time-based KPIs**.
      - Optionally, integrate the Calendar framework into an existing semantic model to ensure alignment across datasets.

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

Please read the MIT License file included.

 **© 2025 Semanticise Inc / OLAP Office Inc.** All rights reserved. 
