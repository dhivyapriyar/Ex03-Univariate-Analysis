# Ex03-Univariate-Analysis

# Aim
To read the given data and perform the univariate analysis with different types of plots.

# Explanation
Univariate analysis is basically the simplest form to analyze data. Uni means one and this means that the data has only one kind of variable. The major reason for univariate analysis is to use the data to describe. The analysis will take data, summarise it, and then find some pattern in the data.

# Algorithm
# Step1 
Read the given data.

# Step2 
Get the information about the data.

# Step3
Remove the null values from the data.

# Step4
Mention the datatypes from the data.

# Step5
Count the values from the data.

# Step6
Do plots like boxplots,countplot,distribution plot,histogram plot.

# program
Developed by : DHIVYAPRIYA R
Registration Number : 212222230032
```
import pandas as pd import numpy as np import seaborn as sns df=pd.read_csv("SuperStore.csv") df df.head() df.info() df.describe() df.isnull().sum() df.dtypes df['Postal Code'].value_counts() sns.boxplot(x="Postal Code", data=df) sns.countplot(x="Postal Code", data=df) sns.distplot(df["Postal Code"]) sns.histplot(x="Postal Code", data=df)
```

OUTPUT
DATA
![228483553-3cb35e71-5166-47ed-b0c4-0b6b06f21340](https://user-images.githubusercontent.com/119477552/234184534-b0422ea8-d9bf-43af-8c70-8473d48c5f76.png)


DATA HEAD

![228483690-07800721-8a7d-4a01-a832-0948e1745c65](https://user-images.githubusercontent.com/119477552/234184639-e30706c3-729f-4436-b2b4-90cf6c62dced.png)

DATA INFORMATION

![228483815-6f07985a-504e-41e1-8c4b-feaa34d23969](https://user-images.githubusercontent.com/119477552/234184665-b40e9e7c-ce0e-45ad-9ad6-4754cd06d64e.png)


DATA DESCRIBE

![228483914-290012db-bd0b-4b6c-848f-7340b0d9878b](https://user-images.githubusercontent.com/119477552/234184709-d3107c76-4ff0-4bd0-9fbb-f4c4020a0998.png)


DATA NULL VALUES

![228485220-87ff56a8-0097-4175-848c-dd2914c52c3a](https://user-images.githubusercontent.com/119477552/234184726-8ac01edf-6578-4056-88a6-eeb6fd25c87c.png)

DATA DATA TYPES

![228485396-dc3a331d-35ba-46a3-a1cf-db23dd29e96d](https://user-images.githubusercontent.com/119477552/234184739-68003f38-dd46-4fe9-a867-f5287df73549.png)


DATA VALUE COUNT

![228485442-2de67d08-a686-4dd2-bd34-7bea7510d61b](https://user-images.githubusercontent.com/119477552/234184773-ebeb3305-a2e1-4baa-a39e-efe852bb278e.png)

BOXPLOT

![228485477-7df8f95a-0e2b-4c89-a96b-2109745a4774](https://user-images.githubusercontent.com/119477552/234184784-6003aef3-03d0-4aef-bfbe-ca1370fc4eed.png)

COUNTPLOT

![228485516-a9a765db-8841-45af-bff6-aff0e6e005f3](https://user-images.githubusercontent.com/119477552/234184799-39ea7899-c2a7-4544-8a92-7aab9e0c5341.png)


DISTRIBUTION PLOT

![228485589-57b17f29-2115-4c1a-bd89-3977f2485114](https://user-images.githubusercontent.com/119477552/234184835-b755f6ad-c853-4d88-8591-12311a85464c.png)

HISTOGRAM PLOT

![228485637-7872f8e5-4ce3-481c-be62-1e730e012888](https://user-images.githubusercontent.com/119477552/234184843-9c2e48d9-874d-44d2-a7ec-0423034f7249.png)

# RESULT
Thus we have read the given data and performed the univariate analysis with different types of plots.
