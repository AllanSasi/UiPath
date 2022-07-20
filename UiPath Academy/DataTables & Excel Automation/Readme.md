# UiPath Academy Practices

## DataTables
- DataTables1 - Build DataTable, Join DataTable, Remove DataColumn, Sort DataTable, Output DataTable.

## Excel Automation
- Excel1 - Workbook Read Range, Filter DataTable, Add DataRow, Excel Application Scope, Write Range.
- Excel2 - Excel Application Scope, Excel Read Range, Filter DataTable, Get RowItem, Add DataRow, Workbook Write Range.
- ExcelModern1 - Excel Process Scope, Use Excel File, Remove Duplicates, Copy/Paste Range, Insert Column, For Each Excel Row, VLookup, Write Cell.

## 
- Practice1-CalculatingSums
  - Calculating sum of values from two different columns of an Excel file
  - Keeps the Excel open and writes the results in real-time, row by row, changes can be seen.
    - Excel Application Scope, Excel Read Range, For Each Row in DataTable, Get RowItem, Excel Write Cell.
  - Keeps the Excel closed, set the column values in the memory Data Table and adds all the tables to a new Excel file at once, in the end.
    - Workbook Read Range, Add DataColumn, For Each Row in DataTable, Workbook Write Range.
  - Calculates the sum by using Excel formulas in the original file.
    - Excel Application Scope, Excel Read Range, Excel Write Range.
    
- Practice2-CalculatingLossInvoices
