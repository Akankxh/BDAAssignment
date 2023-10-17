# Frequent ItemSet Mining Using Apriori Algorithm

In this project we have worked on a dataset consisting of 77,185 places in the United States. 
Each line corresponds to the category list of one place, where the list consists of a number of category 
instances (e.g., hotels, restaurants, etc.) that are separated by semicolons.

Now, our motivation is to find out which category instances occur most frequently in places across the US, this is an example of a real-life data mining problem
and we have chosen the Apriori Algorithm because of its effectiveness in discovering frequent itemsets and association rules while working on large datasets.
It is commonly seen in Market Basket Analysis, Web Usage Mining and Recommendation Systems to identify association between products and increasing user
engagement.
## Table Of Contents
* [General Info](#general-info)
* [Technologies](#technologies)
* [Setup](#setup)

## General Info
Now, our motivation is to find out which category instances occur most frequently in places across the US, this is an example of a real-life data mining problem
and we have chosen the Apriori Algorithm because of its effectiveness in discovering frequent itemsets and association rules while working on large datasets.
It is commonly seen in Market Basket Analysis, Web Usage Mining and Recommendation Systems to identify association between products and increasing user
engagement.
## Technologies
Project is created with:
* Python (itertools and combinations library)

## Setup
To first run this project and the source code, we will implementing the following on Visual Studio Code.
[1]: https://code.visualstudio.com/download 

* Create a directory containing the dataset categories.txt.txt
* First, start with producing the patterns_1.txt file, you will have to run the patterns_1.py file to produce all length-1 frequent itemsets, which is present in the directory with the following command on the terminal:
```bash
python patterns_1.py
```
After running the above command on the terminal, the patterns_1.txt will be produced and the required output can be visualised.

* Now, run the patterns_all.py file to return all the frequent itemsets present in the dataset, this will produce the patterns_all.txt file. Make sure patterns_all.py is present in your directory.
```bash
python patterns_all.py
```

* Finally, to produce all the closed frequent itemsets, run the patterns_close.py file which will be present in the directory. This will produce the patterns_close.txt file which will consist of these closed frequent itemsets.
```bash
python patterns_close.py
```

* In each txt file, the itemsets will be displayed in descending order and this due to the implementation of a merge sort function present in the respective codes which sorts them in descendig order

## THANK YOU


