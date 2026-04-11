Set 5
✅ Q1. Build a Power BI Dashboard to Visualize Profit Insights
🔹 Step 1: Open Power BI
Launch Microsoft Power BI Desktop
🔹 Step 2: Load Dataset
Click Home → Get Data → Excel
Select DB2.xlsx (Profit Dataset)
Click Load
🔹 Step 3: Check Data
Go to Data View
Ensure fields like:
Profit
Sales
Category
Region
Date
Fix any missing or incorrect data if needed
🔹 Step 4: Create Basic Visuals

👉 1. Bar Chart (Profit by Category)

Select Clustered Bar Chart
Drag:
Category → Axis
Profit → Values

👉 2. Pie Chart (Profit by Region)

Select Pie Chart
Drag:
Region → Legend
Profit → Values

👉 3. Line Chart (Profit Over Time)

Select Line Chart
Drag:
Date → Axis
Profit → Values

👉 4. Card (Total Profit)

Select Card Visual
Drag Profit → Shows total profit

👉 5. Slicer (Filter Option)

Select Slicer
Drag:
Region or Category
Helps filter dashboard
🔹 Step 5: Arrange Dashboard
Place visuals neatly:
Top → Total Profit (Card)
Left → Bar Chart
Right → Pie Chart
Bottom → Line Chart
🔹 Step 6: Save File
Click File → Save As
Name: Profit Dashboard.pbix
✅ Q2. Apply Themes, Formatting, and Layout Improvements
🔹 Step 1: Apply Theme
Go to View → Themes
Choose a theme (e.g., Light, Dark, Corporate)
Or click Browse for Themes (custom theme)
🔹 Step 2: Format Visuals

Click each chart → go to Format (paint roller icon):

Change colors (use consistent color scheme)
Turn Data Labels ON
Add Titles (e.g., "Profit by Category")
Adjust font size and style
🔹 Step 3: Improve Layout
Align visuals properly (use gridlines)
Keep equal spacing between charts
Avoid clutter (don’t overcrowd)
🔹 Step 4: Add Background
Go to Format → Canvas Background
Add light color or image
Set transparency properly
🔹 Step 5: Add Borders & Effects
Enable:
Shadow
Border
Rounded corners
🔹 Step 6: Use Consistent Fonts
Same font style across dashboard
Highlight important values (like total profit)
🔹 Step 7: Add Titles & Headings
Insert Text Box
Add:
Dashboard Title → “Profit Analysis Dashboard”
🔹 Step 8: Final Check
Ensure:
Dashboard is clean
Easy to understand
Visually appealing
Set -6
✅ Q1. Create Bar, Pie, and Line Charts to Represent Sales Data
🔹 Step 1: Open Power BI
Launch Microsoft Power BI Desktop
🔹 Step 2: Load Dataset
Click Home → Get Data → Excel
Select DB1.xlsx (Sales Dataset)
Click Load
🔹 Step 3: Check Data
Go to Data View
Ensure columns like:
Sales
Category
Region
Date
🔹 Step 4: Create Bar Chart
Select Clustered Bar Chart
Drag:
Category → Axis
Sales → Values
👉 Shows sales by category
🔹 Step 5: Create Pie Chart
Select Pie Chart
Drag:
Region → Legend
Sales → Values
👉 Shows sales distribution by region
🔹 Step 6: Create Line Chart
Select Line Chart
Drag:
Date → Axis
Sales → Values
👉 Shows sales trend over time
🔹 Step 7: Arrange Visuals
Place charts neatly:
Left → Bar Chart
Right → Pie Chart
Bottom → Line Chart
🔹 Step 8: Save File
File → Save As → Sales Dashboard.pbix
✅ Q2. Apply Filters and Slicers to Improve Analysis
🔹 Step 1: Add Slicer
Click Slicer Visual
Drag field (e.g., Region or Category)
👉 Allows user to filter data
🔹 Step 2: Add Multiple Slicers
Add slicers for:
Category
Region
Date
🔹 Step 3: Apply Filters (Filter Pane)
Go to Filters Pane (right side)
Add filters:
Drag fields into:
Visual Level Filter
Page Level Filter
🔹 Step 4: Use Slicer Options
Change slicer type:
Dropdown
List
Enable Single Select or Multi Select
🔹 Step 5: Test Filtering
Click values in slicer
👉 All charts update automatically
🔹 Step 6: Format Slicers
Go to Format (paint icon):
Change color
Increase font size
Add title (e.g., “Select Region”)
🔹 Step 7: Arrange Layout
Place slicers at:
Top or left side for easy use
🔹 Step 8: Final Check
Ensure:
Filters work properly
Dashboard is clear and interactive
Set 7
✅ Healthcare Dashboard in Power BI (Step-by-Step)
🔹 Step 1: Open Power BI
Launch Microsoft Power BI Desktop
🔹 Step 2: Load Dataset
Click Home → Get Data → Excel
Select DB5.xlsx (Healthcare Dataset)
Click Load
🔹 Step 3: Check Data
Go to Data View
Verify important fields like:
Patient ID
Disease / Diagnosis
Age
Gender
Treatment Cost
Admission Date
🔹 Step 4: Create Key Visuals

👉 1. Card (Total Patients)

Select Card Visual
Drag Patient ID (Count)
👉 Shows total number of patients

👉 2. Bar Chart (Patients by Disease)

Select Clustered Bar Chart
Drag:
Disease → Axis
Patient ID (Count) → Values
👉 Shows most common diseases

👉 3. Pie Chart (Patients by Gender)

Select Pie Chart
Drag:
Gender → Legend
Patient ID (Count) → Values

👉 4. Line Chart (Admissions Over Time)

Select Line Chart
Drag:
Admission Date → Axis
Patient ID (Count) → Values

👉 5. Column Chart (Treatment Cost by Category/Disease)

Drag:
Disease → Axis
Treatment Cost → Values
🔹 Step 5: Add Slicers (Filters)
Add Slicer Visuals for:
Gender
Disease
Date
👉 Makes dashboard interactive
🔹 Step 6: Arrange Dashboard Layout
Top → Title + Total Patients (Card)
Left → Bar Chart
Right → Pie Chart
Bottom → Line Chart + Cost Chart
Side → Slicers
🔹 Step 7: Apply Basic Formatting
Add titles (e.g., “Patients by Disease”)
Turn ON data labels
Use consistent colors
Adjust font size
🔹 Step 8: Add Dashboard Title
Insert Text Box
Title: “Healthcare Analysis Dashboard”
🔹 Step 9: Test Interactivity
Click slicers
👉 All charts should update automatically
🔹 Step 10: Save File
File → Save As → Healthcare Dashboard.pbix
Set 8
✅ Student Dashboard in Power BI (Step-by-Step)
🔷 Part 1: Create KPI Cards (Key Performance Indicators)
🔹 Step 1: Open Power BI
Launch Microsoft Power BI Desktop
🔹 Step 2: Load Dataset
Click Home → Get Data → Excel
Select DB6.xlsx (Student Dataset)
Click Load
🔹 Step 3: Check Data
Go to Data View
Verify fields like:
Student Name / ID
Marks
Subject
Class / Section
🔹 Step 4: Create KPI Cards

👉 1. Total Students

Select Card Visual
Drag Student ID → Count

👉 2. Total Marks

Select another Card
Drag Marks → Sum

👉 3. Average Marks

Select another Card
Drag Marks → Average

👉 4. Highest Marks (Optional)

Drag Marks → Max
🔹 Step 5: Arrange KPI Cards
Place all cards at the top of dashboard
Align them in a single row
🔹 Step 6: Format KPI Cards
Add titles:
“Total Students”
“Total Marks”
“Average Marks”
Increase font size
Apply consistent colors
🔷 Part 2: Use Drill-through and Tooltips
🔹 Step 7: Create Main Visual
Add a Bar Chart
Drag:
Student Name / Subject → Axis
Marks → Values
🔹 Step 8: Create Drill-through Page
Add a new page
Drag Student Name (or Subject) into Drill-through field
Add visuals like:
Marks details
Subject-wise performance

👉 Now right-click on any bar → Drill-through works

🔹 Step 9: Enable Drill-through Button (Optional)
Insert Button → Drill-through
Helps user navigate easily
🔹 Step 10: Create Tooltips Page
Add new page
Go to Page Information → Turn ON Tooltip
Set Page Size → Tooltip
🔹 Step 11: Design Tooltip
Add small visuals:
Marks
Subject
👉 Shows extra info on hover
🔹 Step 12: Assign Tooltip
Go back to main chart
In Format → Tooltip
Select your tooltip page
🔹 Step 13: Test Features
Hover → Tooltip appears
Right-click → Drill-through works
🔹 Step 14: Final Layout
Top → KPI Cards
Middle → Bar Chart
Keep layout clean
🔹 Step 15: Save File
File → Save As → Student Dashboard.pbix
