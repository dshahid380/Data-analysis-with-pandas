![pandas for data analysis](pandas1.png)
                                            <br>**Fig. 1** 

   Welcome to the tutorial Data analysis with pandas. In this tutorial i have covered all the topics of pandas and tried to explain each and every concepts with lesser words in jupyter notebook so that you can observe the function of every methods in pandas from the ground level.<br>
   <br>
   <br>First of all let's understand "what is data analysis and why should we use pandas for analysis ?".
   
### What is data analysis ?
   Suppose you are working in a company which daily generates a lot of data of customers and you are assigned a task to extract some useful information out of it with certain deadline. What will you do if you have very limited time you can not exract information just by looking into the dataset because size of the data is huge. So you asked for help from your collegue he said just read about pandas for data analysis. You study about pandas and you found that pandas makes your life easier than just looking at dataset and finding useful informations.
### What does pandas actually do ?
   This official documentation says- <br>
   pandas is a Python package providing fast, flexible, and expressive data structures designed to make working with “relational” or “labeled” data both easy and intuitive. It aims to be the fundamental high-level building block for doing practical, real world data analysis in Python. Additionally, it has the broader goal of becoming the most powerful and flexible open source data analysis / manipulation tool available in any language. It is already well on its way toward this goal.
   <br>
   <br>
   pandas is well suited for many different kinds of data:
   * Tabular data with heterogeneously-typed columns, as in an SQL table or Excel spreadsheet.
   * Ordered and unordered (not necessarily fixed-frequency) time series data.
   * Arbitrary matrix data (homogeneously typed or heterogeneous) with row and column labels.
   * Any other form of observational / statistical data sets. The data actually need not be labeled at all to be placed into a pandas data structure.

### Dependencies-
   ```
   pip install pandas 
   pip install numpy
   ```

### Table of contents -
  * [Introduction to pandas](https://github.com/dshahid380/Data-analysis-with-pandas/blob/master/pandas_part1.ipynb)
  * [Dataframe Object](https://github.com/dshahid380/Data-analysis-with-pandas/blob/master/pandas_part2.ipynb)
  * [Reading, Writing CSV and EXCEL file](https://github.com/dshahid380/Data-analysis-with-pandas/blob/master/pandas_part3.ipynb)
  * [Handling Missing Data part-1](https://github.com/dshahid380/Data-analysis-with-pandas/blob/master/pandas_part4.ipynb)
  * [Handling Missing Data part-2](https://github.com/dshahid380/Data-analysis-with-pandas/blob/master/pandas_part5.ipynb)
  * [Groupby : Split, Combine and Apply](https://github.com/dshahid380/Data-analysis-with-pandas/blob/master/pandas_part6.ipynb)
  * [Concat Dataframes](https://github.com/dshahid380/Data-analysis-with-pandas/blob/master/pandas_part7.ipynb)
  * [Merging Dataframes](https://github.com/dshahid380/Data-analysis-with-pandas/blob/master/pandas_part8.ipynb)
  * [Pivot and Pivot table](https://github.com/dshahid380/Data-analysis-with-pandas/blob/master/pandas_part9.ipynb)
  * [Reshaping Dataframes](https://github.com/dshahid380/Data-analysis-with-pandas/blob/master/pandas_part10.ipynb)
 <br>
  
### Introduction to pandas :
   ![](https://i1.wp.com/www.ugandaletsgotravel.com/holidays/wp-content/uploads/2018/04/holidays-panda-breeding-china-600x400.jpg)
   <br> **Fig.2** <br><br>
   Pandas is used as data cleaning tool in the field of data science.You can do whatever operation you want in the dataset with this tool.Now question arises, can we clean or change the value in the dataset manually ? Answer is yes we can if size of the dataset is small.What if we have a large dataset then we can not do it manually it will take a lot of time.Pandas makes data science very easy and effective.
   <br>
   To use pandas you need to first import the pandas module in your program
   ```
     import pandas as pd 
   ```
  <br>  
  
  
####  Reading CSV and Excel sheets:
**d=pd.read_csv("path"):**
   * pd.read_csv() is the function to read the CSV(Comma separated values) file from your computer.
   * In the function you have to pass "path" of the CSV file under quote.
   * Store the dataframe in any variable,here i stored it in variable "d".
   * read_csv() function makes the CSV file into dataframe so that you can access it just like a disctionary. <br>
 
 **d=pd.read_excel("path") :**
   * It is same as the read_csv() but it reads excel sheet or file. Here i am using the weather dataset which has all the data of weather. In my case,weather.csv file is in my current directory that is why the path of the file is file name itself.
   ```
   d=pd.read_csv('datasets/weather.csv')
   print(d)
   ```
 <br>
 
  **For futher tutorial go to the above link given in the Table of contents or click this [link](https://github.com/dshahid380/Data-analysis-with-pandas)**
 
 

 
### References :
 * [Pandas Official documentation](https://pandas.pydata.org/pandas-docs/stable/tutorials.html)
 * [Tutorials points](https://www.tutorialspoint.com/python_pandas)
 * [Datacamp](https://www.datacamp.com/courses/pandas-foundations) 
 
 <br>

<script defer src="https://use.fontawesome.com/releases/v5.6.3/js/all.js" integrity="sha384-EIHISlAOj4zgYieurP0SdoiBYfGJKkgWedPHH4jCzpCXLmzVsw1ouK59MuUtP4a1" crossorigin="anonymous"></script>   
<i class="fab fa-github"></i> [dshahid380](https://github.com/dshahid380)
<i class="fab fa-linkedin"></i>[ Md Shahid](https://www.linkedin.com/in/dshahid380/)
