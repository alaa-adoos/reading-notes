# pandas
### we import as follows:
```
import numpy as np

import pandas as pd
```
## Object creation
- Creating a Series by passing a list of values, letting pandas create a default integer index
- Creating a DataFrame by passing a NumPy array, with a datetime index using date_range() and labeled column
- Creating a DataFrame by passing a dictionary of objects that can be converted into a series-like structure

## Viewing data
- Use DataFrame.head() and DataFrame.tail() to view the top and bottom rows of the frame respectively
- Display the DataFrame.index or DataFrame.columns

## **NumPy arrays have one dtype for the entire array, while pandas DataFrames have one dtype per column.**
