# Copy-File
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Load the CSV into a DataFrame.

### Step 2: 
 Print the number of contents to be displayed using df.head().


### Step 3: 
The number of rows returned is defined in Pandas option settings.

### Step 4:  
Check your system's maximum column with the pd.options.display.max_column statement.

### Step 5: 
Increase the maximum number of rows to display the entire DataFrame.

## PROGRAM:
`````
#To write a python program for reading content from a CSV file.
#Developed by KRISHNA KUMAR
#Reg no:212223230107

with open("text.txt",'r') as fp:
    msg1=fp.read()
with open("copy.txt",'w') as fp1:
    fp1.write(msg1)
```````

### OUTPUT:
![WhatsApp Image 2024-05-13 at 21 17 10_e1805d64](https://github.com/Krishna23013541/Copy-File/assets/149557764/0dec3692-0b8c-465c-b923-f6f009e5f8b2)
![WhatsApp Image 2024-05-13 at 21 17 10_fca2bb91](https://github.com/Krishna23013541/Copy-File/assets/149557764/01adc4e9-874c-44b7-9259-19bfab32417f)

## RESULT:
Thus the program is written to copy the contents from one file to another file.
