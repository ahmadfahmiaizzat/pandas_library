Explanation:
calculate_grade(): Same as before, this function assigns grades based on the marks.
pandas DataFrame: A DataFrame is created from a dictionary that contains the students' names and marks.
Statistics Calculations:
Average and Standard Deviation are calculated using pandas' .mean() and .std() functions.
Maximum, Minimum, and Range are calculated using .max(), .min(), and simple subtraction.
Summary Data: A separate DataFrame is created for the calculated statistics and is appended to the main DataFrame.
Excel File: The resulting DataFrame is saved as an Excel file called students_marks_and_grades.xlsx.

       Name                 Marks          Grade
0     Alice                   85              A
1       Bob                   78              B
2   Charlie                   92              A
3     David                   67              C
4       Eva                   55              D
5     Frank                   45              F
6     Grace                   73              B
7    Hannah                   88              A
8       Ivy                   61              C
9      Jack                   52              D
10  Average                69.60              
11  Standard Deviation      15.63              
12  Maximum                92.00              
13  Minimum                45.00              
14  Range                  47.00              
