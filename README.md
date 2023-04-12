# Covid-19
<br>
<img align="center" alt="coding" width="400" src="https://wordpress.accuweather.com/wp-content/uploads/2020/03/CoronavirusAnimation2.gif">
<br>
<img align="center" alt="coding" width="400" src="https://media1.tenor.com/images/13388dbc058e8ba9b3935138f4e7a376/tenor.gif?itemid=18090415">
<br>
<img align="center" alt="coding" width="400" src="https://media.giphy.com/media/MCAFTO4btHOaiNRO1k/giphy.gif">

<br>
<h2> Descripection :-</h2>
<br>
In this video, a mini dataset related to the Covid-19 pandemic is taken and analysed in a very Easy To Understand (ETU) language.<br>
Here, you will learn how to work on a real project of Data Analysis with Python. <br>
Questions are given in the project and then solved with the help of Python. <br>

<br>
<h2>DataSet :-</h2><br>
* Download the dataset for custom trainig
<br>

 https://drive.google.com/file/d/1BTG4tZUmiTKwu1E7o_UmqAtMrguNrOoh/view?usp=sharing
 
 <br>
 
 <h2> Installaction :- </h2>
 <h3> Requirments :-</h3>
 * Python 3.9 + <br>
 * Pandas<br>
 * Windows<br>
  <br>
  <h2> Setup :-</h2>
 * install Pandas:-<br>
 * pip install Pandas<br>
  
  
  <h2>The commands that we used in this project :-</h2>

* import pandas as pd -- To import Pandas library<br>
* pd.read_csv - To import the CSV file in Jupyter notebook<br>
* df.count() - It counts the no. of non-null values of each column.<br>
* df.isnull().sum() - It detects the missing values from the dataframe.<br>
* import seaborn as sns - To import the Seaborn library.<br>
* import matplotlib.pyplot as plt - To import the Matplotlib library.<br>
* sns.heatmap(df.isnull()) - It will show the all columns & missing values in them in heat map form.<br>
* plt.show() - To show the plot.<br>
* df.groupby(‘Col_name’) - To form groups of all unique values of the column.<br>
* df.sort_values(by= ['Col_name'] ) - Sort the entire dataframe by the values of the given column.<br>     
* df[df.Col_1 = = ‘Element1’] - Filtering – We are accessing all records with Element1 only of Col_1.<br>
<br>
Q. 1) Show the number of Confirmed, Deaths and Recovered cases in each Region.<br>
Q. 2) Remove all the records where the Confirmed Cases is Less Than 10.<br>
Q. 3) In which Region, maximum number of Confirmed cases were recorded ?<br>
Q. 4) In which Region, minimum number of Deaths cases were recorded ?<br>
Q. 5) How many Confirmed, Deaths & Recovered cases were reported from India till 29 April 2020 ?<br>
Q. 6-A ) Sort the entire data wrt No. of Confirmed cases in ascending order.<br>
Q. 6-B ) Sort the entire data wrt No. of Recovered cases in descending order.<br>
