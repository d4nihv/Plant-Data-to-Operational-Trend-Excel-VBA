# Plant-Data-to-Operational-Trend-Excel-VBA
Converting data sets from a CSV (unlimited data sets) to graph trends. Time slider, and Overlay audits available
How to use the Excel dashboard

1. Open the PlantData Sheet. There should be 2 sheets. One has data, and the other displays a trend data. Create a separate sheet called Dashboard.

2. Ensure that the Developer ribbon is visible (top stuff like Home and Insert). If not, right-click that area, click Customise Ribbon, and tick the Developer box.

3. Open the Visual Basic Editor (VBE) in the sheet and open the code editor (double-click on the Excel workbook). Copy and input the newest version of the code. Ensure that your Excel file is saved as a macro-enabled file.

4. Create a shape in the dashboard sheet, named dashboard. Type in the shape "Run Dashboard"

5.  Then right-click on the shape that you made in the "Dashboard sheet". Click Assign Macro of the CarbonCaptureReport and press ok. It should run automatically; go to the VBE and click run on the coding editor

6. For time slider, create a new shape as well in dashboard sheet and assign macro of UpdateChartTimeFrame. Same process with audits. Change data to get other data
