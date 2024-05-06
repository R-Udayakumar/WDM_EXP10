### EX10 Sentimental Analysis on Any Dataset Using Rapidminer
### DATE: 25.04.2024
### AIM: To create a project for Sentimental Analysis on Any Dataset a Using Rapidminer
### Description: 
<div align = "justify">

### Procedure:
1) ***Import CSV data***
    <p>a. Drag the "Read CSV" operator from the IO folder onto the process canvas.
    <p>b. Double-click on the operator to open its configuration panel.
    <p>c. Specify the path to the Excel file you want to analyze.
    <p>d. Configure options such as sheet selection, header inclusion, etc.
    <p>e. Click on the "Run" button to execute the operator and import the Excel data.
2) ***Perform sentiment analysis with Generate Attributes operator***
    <p>a. Drag the "Generate Attributes" operator from the Operators panel onto the canvas.
    <p>b. Connect the output of the "Extract Sentiment" operator to the input of the "Generate Attributes" operator.
    <p>c. Double-click on the "Generate Attributes" operator to configure it.
    <p>d. Specify a name for the new sentiment attribute you want to generate (e.g., "Sentiment").
    <p>e. Choose the sentiment analysis algorithm, "VADER."
    <p>f. Click on the "Run" button to perform sentiment analysis on the Excel data and generate the sentiment attribute.
3) ***Interpret and export the results***
    <p>a. Analyze the sentiment analysis results from the generated visualizations.
    <p>b. If desired, drag the "Write Excel" operator onto the canvas to export the sentiment analysis results to a new Excel file.
    <p>c. Connect the output of the visualization operator(s) to the input of the "Write Excel" operator.
    <p>d. Configure the file path and other settings for the Excel export.
    <p>e. Click on the "Run" button to export the sentiment analysis results to a new Excel file.

### Output:

![Screenshot 2024-05-06 110955](https://github.com/R-Udayakumar/WDM_EXP10/assets/118708024/66e0cf2b-0c74-4054-9320-7f07272a72de)

![Screenshot 2024-05-06 105544](https://github.com/R-Udayakumar/WDM_EXP10/assets/118708024/4b8e897e-ba34-4587-b383-b9c96a75f10a)

![Screenshot 2024-05-06 110942](https://github.com/R-Udayakumar/WDM_EXP10/assets/118708024/865fe4f3-be24-4d9a-a0cc-e3110d7609f8)

### Result:
Thus, sentimental analysis for twitter data using Rapidminer has been successfully executed.
