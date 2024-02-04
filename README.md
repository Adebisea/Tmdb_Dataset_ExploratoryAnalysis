# Tmdb_Dataset_ExploratoryAnalysis

## Dataset Description
This dataset contains 10866 rows of information on cast, revenue, budget, ratings, popularity, movies and other features. It was collected from The Movie Database (TMDb) on Kaggle.

## Data Exploratory Analysis

I conducted a thorough examination of the dataset, evaluating both its visual presentation and underlying structure programmatically to identify any quality and tidiness issues. 
Among the quality issues observed, I specifically targeted duplicate rows and missing values for cleaning. 
Leveraging functionalities from pandas, NumPy, and matplotlib, I systematically addressed these issues to ensure a cleaner dataset before proceeding with the analysis phase.

## Insights

- I highlighted the first three months with the highest popularity in each year and its interesting to see that movies released in Jan are not really that popular. There was an observable increase in popularity from Feb to July
with May, Jun, and July having the most popularity. Movies released in Nov and Dec are also mostly popular.

#### Movies popularity by month from year 2010 through 2015

<table style="border-collapse: collapse;">
  <tr>
    <td><img src="https://github.com/Adebisea/Tmdb_Dataset_ExploratoryAnalysis/blob/ee4eb4531d8cbdaef193e929bc111a56677a1a47/asset/monthpop2010.png" ></td>
    <td><img src="https://github.com/Adebisea/Tmdb_Dataset_ExploratoryAnalysis/blob/ee4eb4531d8cbdaef193e929bc111a56677a1a47/asset/monthpop2011.png"></td>
    <td><img src="https://github.com/Adebisea/Tmdb_Dataset_ExploratoryAnalysis/blob/ee4eb4531d8cbdaef193e929bc111a56677a1a47/asset/monthpop2012.png"></td>
  </tr>
   <tr>
    <td><img src="https://github.com/Adebisea/Tmdb_Dataset_ExploratoryAnalysis/blob/ee4eb4531d8cbdaef193e929bc111a56677a1a47/asset/monthpop2013.png" ></td>
    <td><img src="https://github.com/Adebisea/Tmdb_Dataset_ExploratoryAnalysis/blob/ee4eb4531d8cbdaef193e929bc111a56677a1a47/asset/monthpop2014.png"></td>
    <td><img src="https://github.com/Adebisea/Tmdb_Dataset_ExploratoryAnalysis/blob/ee4eb4531d8cbdaef193e929bc111a56677a1a47/asset/monthpop2015.png"></td>
  </tr>
 </table>

- The most popular genres are adventure, science fiction, and fantasy. Action and animation genres are also well received but I just want to stick with the first three genres.

  ![Alt text](https://github.com/Adebisea/Tmdb_Dataset_ExploratoryAnalysis/blob/68d9523476ae045269cbfe13fede2ebd4cedbcf8/asset/genrepop.png)
  
- Movies with high popularity are mostly around the first 200 mins, with the peak popularity observed at approximately 120 minutes and beyond.
  <table style="border-collapse: collapse;">
  <tr>
    <td><img src="https://github.com/Adebisea/Tmdb_Dataset_ExploratoryAnalysis/blob/68d9523476ae045269cbfe13fede2ebd4cedbcf8/asset/runtimepop.png" ></td>
    <td><img src="https://github.com/Adebisea/Tmdb_Dataset_ExploratoryAnalysis/blob/ee4eb4531d8cbdaef193e929bc111a56677a1a47/asset/monthpop2011.png"></td>
  </tr>
 </table>



