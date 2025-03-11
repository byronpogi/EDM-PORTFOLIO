# Midterm Lab Task 1
- This is a project about data cleaning and preparation using Excel. It involves organizing and refining raw data by removing duplicates, correcting errors, filling in missing values, and standardizing formats. The project utilizes Excel tools like filters, formulas, and pivot tables to ensure the data is accurate, consistent, and ready for analysis or reporting.
  
## step by step process

### Step 1: Remove Duplicates
1. **Open your Excel file** containing the raw data.
2. Select the range of data or entire sheet you want to clean.
3. Go to the **Data** tab in the Excel ribbon.
4. Click on **Remove Duplicates** in the Data Tools group.
5. In the pop-up window, select the columns where you want to check for duplicates.
6. Click **OK** to remove duplicate entries. Excel will display how many duplicates were removed.

### Step 2: Handle Missing Data
1. **Identify missing data**: Look for blank cells in your dataset.
2. Decide how to handle missing values:
   - **Fill with a default value**: Use the **Find & Replace** (Ctrl + H) feature to replace blanks with a default value (e.g., "N/A").
   - **Fill with the average or median**: If the missing values are numeric, you can use Excel functions like `AVERAGE()` or `MEDIAN()` to replace the blanks.
   - **Remove rows with missing data**: If the missing data is significant, select the rows and delete them using **Right-click > Delete** or the **Delete** key.
3. **Use formulas**: You can use the `IFERROR()` or `IF()` functions to handle missing values conditionally, e.g., `=IF(ISBLANK(A2), "N/A", A2)`.

### Step 3: Standardize Data Formats
1. **Check for inconsistent formats**: Review your columns for different date formats, text case inconsistencies (upper/lower case), or number formats.
2. **Standardize dates**: 
   - Select the date column, then go to the **Home** tab.
   - In the **Number** group, choose **Short Date** or **Long Date** as required.
3. **Standardize text case**: Use the **UPPER()**, **LOWER()**, or **PROPER()** functions to ensure consistent text formatting.
   - Example: `=UPPER(A2)` converts all text in cell A2 to uppercase.
4. **Format numbers**: Ensure that numbers are in the correct format, such as currency, percentages, or general numbers. Select the range and use the **Number Format** dropdown in the **Home** tab.
5. **Fix column alignment**: Use Excel's "Text to Columns" feature to ensure that data is properly separated into different columns if necessary.

These steps help clean your data and prepare it for analysis by ensuring consistency and accuracy.

## Screenshots
![Image](https://github.com/user-attachments/assets/e8958e92-4858-4cd3-82fe-bac5e5f6a79f)

![Image](https://github.com/user-attachments/assets/d1c1002d-baf0-47c9-b5e6-fa5c57fe4112)

![Image](https://github.com/user-attachments/assets/bb6db05c-7487-4851-927f-ce681cbd07da)
