# Spreadsheet Application

## Overview
This web application mimics the user interface and core functionalities of Google Sheets, focusing on mathematical and data quality functions, data entry, and key UI interactions.

## Features
1. **Spreadsheet Interface:**
   - Mimics Google Sheets UI with toolbar, formula bar, and cell structure.
   - Drag functionality for cell content, formulas, and selections.
   - Cell dependencies and updates.
   - Basic cell formatting (bold, italics, font size, color).
   - Add, delete, and resize rows and columns.

2. **Mathematical Functions:**
   - `SUM`: Calculates the sum of a range of cells.
   - `AVERAGE`: Calculates the average of a range of cells.
   - `MAX`: Returns the maximum value from a range of cells.
   - `MIN`: Returns the minimum value from a range of cells.
   - `COUNT`: Counts the number of cells containing numerical values in a range.

3. **Data Quality Functions:**
   - `TRIM`: Removes leading and trailing whitespace from a cell.
   - `UPPER`: Converts the text in a cell to uppercase.
   - `LOWER`: Converts the text in a cell to lowercase.
   - `REMOVE_DUPLICATES`: Removes duplicate rows from a selected range.
   - `FIND_AND_REPLACE`: Allows users to find and replace specific text within a range of cells.

4. **Data Entry and Validation:**
   - Input various data types (numbers, text, dates).
   - Basic data validation checks (e.g., ensuring numeric cells only contain numbers).

## Tech Stack
- **HTML:** Structure of the web application.
- **CSS:** Styling and layout.
- **JavaScript:** Functionality and interactivity.

## Data Structures
- **Grid Layout:** The spreadsheet is implemented using a grid layout with rows and columns.
- **Event Listeners:** Used for handling user interactions such as input, focus, and button clicks.

## Usage
1. Clone the repository.
2. Open `index.html` in a web browser.
3. Use the toolbar to format cells and add rows/columns.
4. Enter formulas in the formula bar or directly in cells.

## Bonus Features
- Additional mathematical and data quality functions.
- Support for complex formulas and cell referencing.
- Save and load spreadsheets.
- Data visualization capabilities (charts, graphs).

## Testing
- Users can test the implemented functions with their own data.
- Results of function execution are displayed clearly.
