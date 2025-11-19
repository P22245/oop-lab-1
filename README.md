*** lab overview ***
oop lab 1
commit 1 - The code implemented the functionality to open the file (Cities.csv), process the data, and then generate and print the required question based on the problem that provide.

commit 2 - The code from Commit 1 was refactored into a functional style, using lambda.

oop lab 2
commit 3 - The existing code was refactored into oop style.

oop lab 3
commit 4 - add DB class to handle to use the data from multiple files

*** Project Structure ***
oop_lab_1
- README.md # this file (overview of this lab)
- Cities.csv # contains all of our data
- data_processing.py # the analysis code (in a oop style)
- Counties.csv # dataset containeach counties information such as EU member or other detail

*** Design Overview ***
- class 1 : learning about how to use github and gitbash and did my-first-repo in github
- class 2 : start oop_lab_1, Strating with try to find the answer in google sheet. Then start writing code using for loop to find the output by the task that provide(in doc).That was commit 1. Next turn the code to using function and start learning about lambda. <- that was commit 2
- class 3 - continue do the commit 2 and prepare for commit 3. The commit 3 was try to turn our code to be an oop style. Starting with the code skeleton the provide in oop_lab_2's google doc and add my code in the DataLoader class and Table class

sturcture from each class
- DataLoader Class # reading csv file
valuable
base_path ; path of data file

method
__init__(self) : loader if no path provide
load_csv(self,filename) : csv reader return list of dict

- Table Class # keep and generage code to be a table of data
valuable
name ; table's name
table ; list of dict

method
filter(self, condition) : check condition and then return new table
aggregate(self, aggregation_function, aggregation_key) : to call value of each key
join(self, table2, key) : 2 tables join together and return new table
str(self) : return str

*** How to test and run my code ***
if Cities.csv , Countries.csv and data_processing.py are in the same folder, that means it's ready to run the code