# Student-Performance-Excel-Data-
Excel data cleaning and analysis of student performance
This will be a step by step on how I cleaned and analyzed this dataset using excel:
Upon opening this file, I immediately noticed the amount of blank cells within this data. 
Going row by row, I went ahead and filled in the missing cells, starting with column A.
Column A shows Student ID numbers. A good amount of these cells were missing student ID numbers. Since I don't have any other data to retrieve these missing values, I went ahead and filtered the data to only show the blank cells and filled in those blanks by using Ctrl+ G to bring up the go to special pop up and fill in the missing cells with "N/A".
Column B is the name of the students, and using the same Ctrl + G method, I filled in the missing names but instead of using "N/A", I filled in the missing values with "Missing".
Column C is Gender and using the same method as in column A and B I filled in the missing values with "N/A".
Column D is Attendance rate. For this one, to calculate the missing attendance rates, I used the IF function in conjunction with ISBLANK and AVERAGEIF.
Column E is Study hours per week, same method as column D in order to find the missing values.
Column F is Previous Grade, same function combination using IF, ISBLANK, and AVERAGEIF to find the missing cells.
Column G is Extracurricular activities, same function combination as well.
Column H is Parental support, for this one, I filtered the data to only show blanks and used the Ctrl + G method to fill in the blanks with "N/A".
Column I is Final grade, and for this one, I used the IF, ISBLANK, and AVERAGEIF formula combination again to find the missing final grades.
Column G is Study hours, used the same function combination. (IF, ISBLANK, AVERAGEIF).
Column K is Attendance %, same function combination (IF, ISBLANK, AVERAGEIF).
Column L is Online classes taken, used the Ctrl + G to fill in the blanks with "N/A".
Created a dashboard to display four bar graphs showing "Average Attendance Rate", "Average Study Hours Per Week", "Average Study Hours Per Day", and "Average Final Grade", all by gender.
