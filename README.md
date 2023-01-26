# Read-from-CSV

## AIM:

## ALGORITHM:
Step 1:
Import pandas as pd.

Step 2:
Read the CSV file using read_csv method.

Step 3:
Use head and tail method to get the required contents from the file.

Step 4:
Use len() method to get the number of rows and columns

Step 5:
Print the output



## PROGRAM:
```
Developed by: Gokul J
Register number: 22009062

import pandas as pd
f = pd.read_csv('nba.csv')
print(f.head(10))
print(f.tail())
print("Number of rows:",len(f.axes[0]))
print("Number of columns:",len(f.axes[1]))
## OUTPUT:
![Screenshot from 2023-01-26 17-34-12](https://user-images.githubusercontent.com/121165938/214831515-648fcf71-6644-4e1e-92b4-732d22b1fd11.png)


## RESULT:
