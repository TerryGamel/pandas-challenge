# pandas-challenge
Data Analytics class, Module 4 assignment
The analysis is located in the PyCitySchools folder, titled PyCitySchools_analysis.txt.

There was significant code present in the PyCitySchools_starter.ipynb file, with comments on what was needed.  Since it was
already well-commented, I did not add additional comments in most cases.  However, there were a few places where I had to
do something confusing and I added comments there.

In the line type_list = school_data_complete.groupby(["school_name"])["type"].unique(),
The answer for .unique usage provided by Amanda Pigman in the 02-ask-the-class slack channel
she also pointed me to .str.get(0) from https://stackoverflow.com/questions/38147447/how-to-remove-square-bracket-from-pandas-dataframe
I think perhaps there was supposed to be something there originally, when it said "Use the code provided", but it was empty.