# Read-from-CSV

## AIM: To write a python program for reading content from a csv file

## ALGORITHM:
### Step 1: 

Import pandas as pd
### Step 2:

Read the CSV file using read_csv method
### Step 3: 

Use head and tail method to get the required contents from the file.
### Step 4:

Use len()method to get the number of rows and columns
### Step 5:

Display the result.
## PROGRAM:
```
# Program to read contents from CSV file
# Developed By: M.Lokesh
# Register Number: 212223230114
import pandas as pd
df=pd.read_csv("nba.csv")
print(df.head(10))
print(df.tail())
print("no of rows",df.axes[0])
print("no of columns",df.axes[1])
print("no of rows",len(df.axes[0]))
print("no of columns",len(df.axes[1]))
```

## OUTPUT:
![Screenshot 2024-01-01 081532](https://github.com/Lokesh23001615/Read-from-CSV/assets/144979337/59186ae9-deb3-4a84-9abb-501e001ff0dd)


## RESULT:

Thus python program for reading content from a CSV file is successful.
