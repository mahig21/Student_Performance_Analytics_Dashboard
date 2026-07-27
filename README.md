# Student Performance Analytics Dashboard 🎓📊

## Overview
Welcome to the **Student Performance Analytics Dashboard**! This is my first Power BI project, developed under the guidance of the **TNS India Foundation**. 

This interactive dashboard is designed to analyze student academic performance and attendance. By transforming raw educational data into visual insights, this project helps track success metrics and identify key trends. 

The project utilizes:
* **Power Query** for robust data cleaning and transformation.
* **DAX (Data Analysis Expressions)** for creating custom measures and advanced calculations.

The primary file in this repository is `Mahi_Student_Performace.pbit`, a Power BI Template. Unlike a standard `.pbix` file, this template retains the complete structural foundation of the project (data models, layouts, DAX measures, and themes) while remaining lightweight, as it does not store the underlying imported data.

## Repository Contents
The `Mahi_Student_Performace.pbit` file acts as a compressed package that includes all the necessary configurations to rebuild the dashboard. Its internal structure includes:
* **DataModelSchema:** The relational structure and logic mapping for the dashboard's data.
* **Report Layout & DiagramLayout:** The visual arrangement, pages, and interactive elements of the report.
* **Settings & Metadata:** The core configuration and project details.
* **Themes:** Pre-configured visual styling, including base themes (e.g., `CY26SU05.json`) and built-in UI themes (`CopilotDefault.json`).

## Prerequisites
To open and use this project, you will need:
* **Power BI Desktop:** Ensure you have the latest version installed. You can download it for free from the [Microsoft Store](https://aka.ms/pbidesktopstore) or the [official website](https://powerbi.microsoft.com/desktop/).

## How to Run the Project
1. **Clone or Download the Repository:**
   ```bash
   git clone https://github.com/mahig21/Student_Performance_Analytics_Dashboard.git
   ```
2. **Open the File:** Locate `Mahi_Student_Performace.pbit` in your local directory and double-click it to open it in Power BI Desktop.
3. **Connect Your Data:** Upon opening the template, Power BI will prompt you to provide the necessary credentials or parameters to connect to the raw data source.
4. **Refresh & View:** Once the data is successfully connected and loaded, the visuals will automatically populate.

## Tech Stack
* **Tool:** Microsoft Power BI
* **Data Transformation:** Power Query
* **Calculations:** DAX
* **File Format:** `.pbit` (Power BI Template)

## License
This project is open-source and available under the [MIT License](LICENSE).
