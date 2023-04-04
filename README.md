# Ex03-Univariate-Analysis
# Aim:
To detect the Univariate Analysis by using default functions.

# Algorithm:
1.Import pandas(),numpy()and seaborn() for a required detection.

2.use the head()

3.The information and is null function.

Use the describe function. 5.Figure the boxplot.

6.plot the countrplot,Displot,Histoplot.

7.Print the program.

# Program:
```
import pandas as pd
import numpy as np
import seaborn as sns

data=pd.read_csv('SuperStore.csv')
data

data.head()

data.info()

data.describe()

data.isnull().sum()

data.dtypes

data['Postal Code'].value_counts()

sns.boxplot(x='Postal Code', data=data)

sns.countplot(x='Postal Code',data=data)

sns.distplot(data["Postal Code"])

sns.histplot(x='Postal Code',data=data)
```

# OUTPUT

# READFILE

![dsreadfile1](https://user-images.githubusercontent.com/120623583/229703208-9c82f494-b34f-4e01-9f03-37dc64555a07.png)

# HEAD

![dshead2](https://user-images.githubusercontent.com/120623583/229703315-96615d10-b9c5-4a1a-bdaf-599b8eab1183.png)

# INFO

![dsinfo3](https://user-images.githubusercontent.com/120623583/229703674-ff790ae4-55a0-4e78-b1e1-384f56f75eec.png)

# DESCRIBE

![dsdesciebe4](https://user-images.githubusercontent.com/120623583/229703777-8061f382-d198-4aa7-9b47-11aad3a4cd4e.png)

# NULL

![dsisnull5](https://user-images.githubusercontent.com/120623583/229703895-a9550127-61ea-4535-baaf-f236deee51ed.png)

# DTYPE

![dsdtype6](https://user-images.githubusercontent.com/120623583/229704187-f8c727f8-a82c-416c-8182-65fa21a29dc5.png)


# COUNT

![dscount7](https://user-images.githubusercontent.com/120623583/229704261-b6e55ed0-57ff-4fdb-ae78-7c96fb7cf120.png)

# BOXPLOT

![dsboxplot8](https://user-images.githubusercontent.com/120623583/229704335-e625a66c-cb08-4e1d-a1ee-73cd0d8ec833.png)

# COUNTERPLOT

![dscounterplot9](https://user-images.githubusercontent.com/120623583/229704461-c37e9e9c-1078-4ca9-b391-af7c4c90c53f.png)

# DISPLOT

![dsdisplot10](https://user-images.githubusercontent.com/120623583/229704636-e1ce2728-9021-4440-a7d7-c7ed628f4e8c.png)

# HISTPLOT

![dshistplot11](https://user-images.githubusercontent.com/120623583/229704715-ab0bf676-f4d1-431b-99fb-b5257ff48e14.png)



# RESULT

Thus the univariate analysed by using default functions. 










