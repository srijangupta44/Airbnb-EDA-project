<h1 align="center"> Airbnb-EDA-Analysis-project</h1>

<p align="center"> 
<img src="GIF/google play.gif" alt="Animated gif" height="282px">
</p>

![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)
## Table Of Contents

- [Project Description](project-description)
- [Project Files Description](project-files-description)
- [Dataset Contents](dataset-contents)
- [Variables Details Of Dataset](variables-details-of-dataset)
- [Problem Statements](problem-statements)
- [Technologies Used](technologies-used)
- [Steps Involved](#steps-involved)
- [Key Insights](key-insights)
- [Conclusion](conclusion)

## 📋 Project Description
This project focuses on conducting an in-depth analysis of Airbnb booking analysis to extract valuable insights. It envolves data cleaning, visualization, and statistical analysis to uncover trends, bugs. there have 49000 data available in a row and total 16 columns such as price, availibility, price, host_name, and location so on and so on. The objective of this experiment is to deliver insights to understand customer demands with prefered intrests. We have tried to discover the relationships among various attributes.
![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

##  💾 Project Files Description

<p>This Project includes 1 google colab notebook and 1 data set in the fromat of csv file:</p>

### Executable Files:
- [Airbnb booking Analysis](https://github.com/srijangupta44/Airbnb-EDA-project/blob/main/Airbnb_booking_analysis_capston_project.ipynb) - Includes all functions required for clustering operations.

### Output:
- [Google Colab](https://github.com/srijangupta44/Airbnb-EDA-project/blob/main/Airbnb_booking_analysis_capston_project.ipynb)) - All the outputs are visible in the provided colab notebook.



![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

### Input Files:
  <li><b>Airbnb booking dataset.csv</b> - It contains the basic details of the app like number of user reviews, ratings, etc.</li>


![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

## Dataset Contents

- This **[data set](https://drive.google.com/drive/folders/17MctuvTM04WPfYgXWZsWeCVQffGovQmF)** contains onr csv  files of data scraped from Airbnb booking app for the period of 2010 - 2018.

- Key variables in the dataset includes :

**Apps Dataset:**

| variables | Details |
| --------------------- | ---------------------- |
| Id | unique number provided for host |
| Name | This section gives the name of hotel.|
| host_Id | the unique number provide for host |
| host_name | the name of host |
| neighbourhood_group | the name of regions |
| neighbourhood | the name of city |
| latitude | postion of the place|
| longitude | postion of the place |
| room_type | varsatality of room  |
| price | Amount charged for the app in doller($) |
| minimum_nights | number of nights user stay |
| number_of_reviews	 | The number of visiters |
| last_review | The date when users visit their properties |
| reviews_per_month | number of visitors per months |
| availability_365 | hotel who open at 365 days |

![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)


## 📔 **What are the technolgies used?**
1. Python
2. Numpy library
3. Pandas library
4. Matplotlib
5. Seaborn
   
![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)


## 📖	Steps Involved

### Data Cleaning
Our data set contains a large number of null values in the  last_reviewreviews_per_month column, so we drop them. Some of the columns have a smaller number of null values, so we replace the null values in these columns with the mode value of that particular column. Our data set also contain the duplicate rows for a single application. We also drop the duplicate rows because the rows contain the identical data.

### Data Transforming 
From the information of data frame, we can see that all the columns except latitude and longitude have the object data type but some of the columns like, reviews, reviews per month, availibility 365, price have the numerical value. So, we have to transform them in proper data type and also remove the unwanted values from the numerical columns. 

### Exploratory Data Analysis
After establishing a good sense of each feature, we proceeded with plotting a pairwise plot between all the quantitative variables to look for any evident patterns or relationships between the features. 

### Single Variate Analysis
After that we analysis all the columns one by one to examine whether the particular column contain some useful information or not:

### Category
We breakdown the airbnb data by category and observe that Entire home/apt at Manhattan place have higher booking and vising of visitors. 

### Data wrangling
Apart from this, one new columns were added to the main data frame, "year". This is done to improve simplify the analysis and come up with different meaningful visualizations
By doing these operations on the original dataset, we are ready with the data pipeline, and data visualizations can be done on it.

![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

### Conclusion
