
# Syncfusion Angular Pivot Table – Basic Usage Example

This sample demonstrates how to integrate and configure the **Syncfusion Pivot Table (PivotView)** component in an **Angular 13** application. The Pivot Table is a powerful UI component for organizing and analyzing large datasets in a tabular format.

## 📖 Overview

The Syncfusion Pivot Table (PivotView) component allows users to summarize and analyze data interactively. In this example, we showcase how to:

- Set up the Pivot Table in an Angular 13 application.
- Bind a static dataset to the component.
- Configure rows, columns, values, and formatting options.

The sample uses a dataset representing sales information for **Mountain Bikes** in **France** across different **quarters** and **fiscal years**.

## 🧩 Features Demonstrated

- **Data Binding:**  
  The Pivot Table is bound to a static array of sales data using the `dataSourceSettings` property.

- **Row and Column Configuration:**  
  - **Rows:** `Country`, `Products`  
  - **Columns:** `Year` (captioned as "Production Year"), `Quarter`  
  - **Values:** `Sold` (Units Sold), `Amount` (Sold Amount)

- **Custom Captions:**  
  Field captions are customized for better readability using the `caption` property.

- **Responsive Layout:**  
  The Pivot Table is rendered with a fixed height of `350px` for optimal display.

## 🛠 Prerequisites

To run this sample, ensure you have the following:

- **Node.js** and **npm** installed
- **Angular CLI** installed globally
- A modern browser (Chrome, Firefox, Edge)

## 🚀 Getting Started

1. **Clone the repository:**
   ```bash
   git clone https://github.com/SyncfusionExamples/ej2-angular-13-pivot-table
   ```

2. **Navigate to the project folder:**
   ```bash
   cd angular-pivot-table-sample
   ```

3. **Install dependencies:**
   ```bash
   npm install
   ```

4. **Run the application:**
   ```bash
   ng serve
   ```

5. **Open in browser:**
   Visit `http://localhost:4200` to view the Pivot Table in action.

## 📊 Sample Data

The sample uses a small dataset with the following fields:

```json
[
  { "Sold": 31, "Amount": 52824, "Country": "France", "Products": "Mountain Bikes", "Year": "FY 2015", "Quarter": "Q1" },
  { "Sold": 51, "Amount": 86904, "Country": "France", "Products": "Mountain Bikes", "Year": "FY 2015", "Quarter": "Q2" },
  { "Sold": 90, "Amount": 153360, "Country": "France", "Products": "Mountain Bikes", "Year": "FY 2015", "Quarter": "Q3" },
  { "Sold": 25, "Amount": 42600, "Country": "France", "Products": "Mountain Bikes", "Year": "FY 2015", "Quarter": "Q4" },
  { "Sold": 27, "Amount": 46008, "Country": "France", "Products": "Mountain Bikes", "Year": "FY 2016", "Quarter": "Q1" }
]
```

## 📚 Learn More

- [Syncfusion Angular Pivot Table Documentation](https://ej2.syncfusion.com/angular/documentation/pivotview/getting-started/)
- [Angular Pivot Table Demos](https://ej2.syncfusion.com/angular/demos/#/material3/pivot-table/overview)

## 💬 Support

For questions or feedback, visit:

- [Syncfusion Support Portal](https://support.syncfusion.com)
- [Syncfusion Community Forums](https://www.syncfusion.com/forums)

## 📜 License

This sample uses Syncfusion components which require a valid license for commercial use.  
[View Syncfusion License Terms](https://www.syncfusion.com/license/studio/22.2.5/syncfusion_essential_studio_eula.pdf)
