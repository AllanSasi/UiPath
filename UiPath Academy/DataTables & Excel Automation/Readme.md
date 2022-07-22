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
  - Need to check which of the invoices in an Excel file were issued to clients in bankruptcy and calculate the sum of the invoices to be recorded as loss.
  - Classic UI
    - Workbook Read Range, Read CSV, Join DataTables, Filter DataTable, For Each Row in DataTable, Workbook Write Range, Workbook Write Cell.
  - Modern UI
    - Excel Process Scope, Use Excel File, Read Range, Read CSV, Join DataTables, Write Range, Filter, For Each Excel Row, Write Cell.

- Practice3-CalculatingPercentagesOfExpenses
  - From a list of expenses (rent, food, utilities, leisure, savings) for some card payments were made. Some transactions were done in cash. Prepare a workflow to bring all the expenses in a single file and calculate the percentages for each expense made.
  - Excel Application Scope, Excel Read Range, Merge DataTable, For Each Row in DataTable, Get RowItem, Add to Collection, Build DataTable, Add DataRow, Workbook Write Range, Workbook Append Range.
