# 📘 Assignment 2: Mastering Big Data Handling

<table border="solid" align="center">
  <tr>
    <th>Name</th>
    <th>Matric Number</th>
  </tr>
  <tr>
    <td width=80%>TIEW CHUAN RONG</td>
    <td>A22EC0112</td>
  </tr>
  <tr>
    <td width=80%>DANIAL HARRIZ BIN MOHD ASINEH @MOHD ASNEH</td>
    <td>A22EC0152</td>
  </tr>
</table>
<br>

## Files Path
| File Name                     | Description                                | Link |
|------------------------------|--------------------------------------------|------|
| **big_data.md**              |            | [![Open](https://img.shields.io/badge/View-Code-green?logo=jupyter)](big_data.md)|
|**big_data.ipynb**||[![Open](https://img.shields.io/badge/View-Code-green?logo=jupyter)](big_data.ipynb)|

## Introduction
   In today’s digital world, companies collect a huge amount of data every day. So, it is important to select a efficient technique to handle this huge data. It is because with a correct tool we can load and process data faster and efficiently. This project is about learning how to deal with big data using real tools used by data engineer.
  
   For our project, we chose a large Transaction dataset that’s about 2.93MB in size. This dataset is selecting from kaggle with name [**'ismetsemedov/transactions'**](https://www.kaggle.com/datasets/ismetsemedov/transactions). Handling such a big dataset can be tricky because it can slow down the computer or even crash the program. So, we used several techniques to make it easier and faster to load, process, and analyze the data. These include breaking the data into chunks, loading only what we need, using lighter data types, sampling small parts, and using parallel processing tools like Dask and Polars. Other than that we also try using different library like Pandas, Polars and Dask to handle this huge amount of data. Then we made a comperative analysis on the processing time and memory usage for each technique used.

   Through this project, we gained hands-on experience in working with big data and learned how professional data engineers manage huge datasets efficiently.
  
## Library used
- Pandas
- Polars
- Dask

## Data Details
**Data source:** [Kaggle - Transaction Data](https://www.kaggle.com/datasets/ismetsemedov/transactions) <br>
**File size:** 2.93GB <br>
**Data Shape:** (7483766, 24)<br>
