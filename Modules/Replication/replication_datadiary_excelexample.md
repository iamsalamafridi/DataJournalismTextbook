# A data diary of global chinese aid project

A data diary of gobal chiinese aid project [beginning of the Excel math review module](../MathReview/mathreview_with_excel.md) is explained below:

### Data source

Original file downloaded as a ZIP folder from the Aid Data website site at https://www.aiddata.org/data/geocoded-chinese-global-official-finance-dataset. The link was http://docs.aiddata.org/ad4/files/GeoCoded_China_Data_Merged_Files.zip. It's undated as far as I can tell.

The key files were in ZIP folder three -- that is listed as below mentioned.
1. AidDataTUFF_Methodology_1.3 (PDF format)
2. GlobalChineseOfficialFinanceDataset_v1.0 (XLSX format)
3. Readme_GlobalChineseOfficialFinanceDataset_v1.0 (PDF format)

Using Acrobat, extracted out those pages into a new file, 
~/Documents/ChinaAidProject/ AidDataTUFF_Methodology_1.3
~/Documents/ChinaAidProject/ Readme_GlobalChineseOfficialFinanceDataset_v1.0

Using Microsoft Excel 2013, extracted out excel sheet into a new file, 
~/Documents/ChinaAidProject/ GlobalChineseOfficialFinanceDataset_v1.0

I tried to extract the data table using Microsoft Excel program. Then I organized and structure the data into the new spread sheet keeping the orginal one in separate sheet.

I decided to use PivotTable for answering to my questions.

### The original spreadsheet
Used the same spreadsheet by keeping the orignal and new spredsheet separatly. 

clean sheet: created new sheet with by just duplicating the orignal sheet with name "Clean" and renaming the old one with "Orignal".

Selected 'even_split_commitments' column and checked against the totals shown at the bottom of the page with column 'project_total_commitments'. They were right!. Then I realized to use the PivotTable to answer my questions.

Did the same thing for the each question sheet, ...............................

Checked against the originals. They matched. Made sure to un-format any numbers so that if I want to export to another program, they'll come in correctly.

This spreadsheet won't be changed unless the data is updated.

### Cleanup

Formatted the numbers as dollars.

Widened the columns

Added a unique identifier to the detail rows in categories in case I need to sort.

Created a row that checks the sums of the detail against the sum provided by the city.

Saved the spreadsheet as phx_budget_summary_sc01.xlsx

### Questions

* What is the money for contingency? How has it been used in the past?
* What does "estimated" mean for 2017 -- don't they know how much was actually spent? When was this created?
* Is there any reason that comparing the estimated 2017 to budgeted 2018 would be misleading?

### Keep going

You can finish the rest yourself, but the key is that everything you've done is logged, and anyone reading this can follow what you did. Including yourself.
