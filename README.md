# Transaction. 

##How to convert to CSV to JSON file

import json
import  csv


#read the CSV and add data to dictionary
with open("Transaction.csv", "r") as f:
    reader = csv.reader(f)

    data=[]
    for row in reader:
