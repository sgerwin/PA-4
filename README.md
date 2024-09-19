# PA 4 - Data Wrangling and Data Visualization<br>
__Download__ the _ECE Board Exam 2 dataset_ and write a Python script/code in the Jupyter Notebook to do the given problems.

## :ledger: Index

- [Description/Given Problems](#beginner-descriptiongiven-problems)
- [Getting Started](#green_circle-getting-started)
   - [Dependencies](#electric_plug-dependencies)
   - [Executing Program](#wrench-executing-prorgram)
- [Author](#writing_hand-author)
  - [Acknowledgements](#star2-acknowledgements)
- [Version History](#scroll-version-history)

## :beginner: Description/Given Problems
__ECE BOARD EXAM PROBLEM:__ Using data wrangling and data visualization technique with storytelling, analyze the data and present different (i) data frames; and (ii) visuals using the dataset given.

1. Create the following data frames based on the format provided:
   - Example: Vis = [“Name”, “Gender”, “Track”, “Math<70”]; hometown is constant as __Visayas__
     <br>
     <br>
     Output:
     <br>
     ![Alt text](example.png)
     <br>
     <br>
     - a) Filename: Instru = [“Name”, “GEAS”, “Electronics >70”]; where track is constant as Instrumentation and hometown Luzon
     - b) Filename: Mindy = [ “Name”, “Track”, “Electronics”, “Average >=55”]; where hometown is constant as Mindanao and gender Female
      <br>
2. Create a visualization that shows how the different features contributes to average grade. Does chosen track in college, gender, or hometown contributes to a higher average score?

## :green_circle: Getting Started

### :electric_plug: Dependencies

* Anaconda Navigator
* Jupyter Notebook
* _**[board2.xlsx](board2.xlsx)**_
* _Optional: Microsoft Excel_
* Any updated version of Windows, Mac, or Linux that is capable of running the programs above.

### :wrench: Executing Program

* How to run the program
* Make sure to have downloaded _**[board2.xlsx](board2.xlsx)**_
* In order to run each cell, please remember to press **_Shift + Enter_**
```
import pandas as pd
```
* It is **_crucial_** to include __"import pandas as pd"__ as the entire Python script relies on this specific code.
```
# Read the Excel file "board2.xlsx" and load it into a DataFrame
df=pd.read_excel("board2.xlsx")
```
* The code block above is also important as this loads the .xlsx file. Without it, the entire script won't run.

## :writing_hand: Author
* Sherwin Miguel C. Mapaye

### :star2: Acknowledgements
* [Engr. Ma. Madecheen S. Pangaliman, MSc](https://www.ust.edu.ph/profile/pangaliman-ma-madecheen-s)<br>
* Engr. Nico John Leo S. Lobos

## :scroll: Version History
* 0.1
   * Initial Release

     

