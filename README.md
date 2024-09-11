# Health-care-diabetes-in-tableau-
Here’s a step-by-step guide on how to create the sheets and the dashboard  using Tableau:

1. Load the Data

Open Tableau.

Connect to your data source by clicking "Connect" (e.g., Excel, CSV, or database).

Once the data is loaded, Tableau will display the data preview.



---

2. Create Individual Sheets

Sheet 1: Donut Chart for Diabetes/Non-Diabetes

1. Create a new sheet by clicking the “New Worksheet” icon at the bottom.


2. Drag the categorical field (e.g., “Diabetes Status”) to the Columns shelf.

This field should contain values such as "Diabetic" and "Non-Diabetic."



3. Drag the measure field (e.g., "Number of Records") to the Rows shelf.


4. Click the drop-down menu on the Marks card and select Pie.


5. Add color: Drag the “Diabetes Status” field to the Color section under Marks.


6. Click on Size and increase the size to make the pie chart bigger.


7. To create the donut shape:

Drag the same measure (e.g., “Number of Records”) onto the Rows shelf again.

Click the drop-down arrow on the second chart’s axis and select Dual Axis.

Right-click one of the axes and uncheck Show Header.

For the second pie chart, click on Marks and remove all color and reduce the size of the center chart, creating the hole.



8. Add labels: Drag “Number of Records” to the Label section to display percentages on the pie chart.


9. Rename the sheet as Donut Chart.




---

Sheet 2: Bar Chart for BMI Related to Age

1. Create a new sheet.


2. Drag “Age” to the Columns shelf.


3. Drag “BMI” to the Rows shelf.


4. Change chart type: Click the drop-down menu on the Marks card and select Bar.


5. Add labels: Drag “BMI” to the Label section to show the values on top of the bars.


6. Adjust sorting: Sort the bars by ascending or descending order if needed.


7. Rename the sheet as BMI by Age.




---

Sheet 3: Bubble Chart for Blood Pressure by Age

1. Create a new sheet.


2. Drag “Age” to the Columns shelf.


3. Drag “Blood Pressure” to the Rows shelf.


4. Change the chart type to Bubble using the drop-down menu on the Marks card.


5. Drag “Blood Pressure” to the Size and Color sections in the Marks card.


6. Add labels: Drag the "Blood Pressure" field to the Label section.


7. Adjust the size of the bubbles as needed.


8. Rename the sheet as Blood Pressure Bubble.




---

Sheet 4: Heat Map for Health Indicators

1. Create a new sheet.


2. Drag “Age” to the Columns shelf.


3. Drag health metrics like BMI, Blood Pressure, Glucose, and Insulin to the Rows shelf.


4. Change the chart type to Heatmap using the Marks card.


5. Add color: Drag a measure (like BMI or Blood Pressure) to the Color section in the Marks card.


6. Adjust the color gradient to make differences more visible.


7. Rename the sheet as Health Indicators Heat Map.




---

3. Create the Dashboard

1. Click the "New Dashboard" icon at the bottom.


2. Drag and drop sheets: From the left panel, drag the sheets (Donut Chart, BMI by Age, Blood Pressure Bubble, and Health Indicators Heat Map) onto the dashboard.


3. Adjust layout: Resize and position each chart as per your needs. You can use tiled or floating layout options for flexibility.


4. Add filters:

If you want to make the dashboard interactive, drag a field (like “Age” or “Diabetes Status”) into the filter area.

You can make a filter global to apply to all the sheets by right-clicking on the filter and selecting "Apply to Worksheets".



5. Add titles and text: Add a title to the dashboard and provide any annotations using the Text object from the left-hand menu.





