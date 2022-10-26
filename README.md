
# Stock management and customer billing application using Python

In this project, a simple stock management and billing application is 
implemented.  

Python 3.9 is used for implementation.




## Installation

The following packages are necessary for the application

```bash
import pandas as pd 
import numpy as np  
from IPython.display import display 
```
    
## Data 

A sample dictionary is created and converted into a dataframe to test 
the code. 

The dataframe has the following attributes:

* Name: name of the item in the stock
* Category: The type of item e.g (Vegetable, Dairy, Meat,Beverage)
* Perishable: Yes or No
* Stock: Total number of items in the Stock
* Sell price: cost of item



## Assumptions

The following assumptions are made while implementing the code:

* The DataFrame used has item name as index to ease the data extraction
* In most of the cases, before taking input from the user, a list of options are displayed
* 
## Documentation

The application is built using the following Functions:

#### Important Functions

* stock_management_system():
All the functionalities are clubbed into this one function

* add_item():

