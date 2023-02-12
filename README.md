# Twitter-Feed-Analysis-Using-Twitter-V2-API-and-MongoDB
Collecting Twitter Feeds Data from Twitter Using Twitter V2 API and Storing it in MongoDB Atlas. Preprocessing the Data and Added many new feature Columns such as Coordinates of Tweet Location, Category Of the Tweet and Sentimental analysis of the tweet. We used Location information from the tweet and by using Geocode python module, we then converted it into the Coordinates which helps in plotting tweets counts in Geological Maps,  We had Implemented Sentimental Analysis Using the TextBlob Package

After processing and setting Data

>Doing Analysis in MongoDB Chart:
>>Movie Popularity Analysis
![image](https://user-images.githubusercontent.com/120790343/218306897-d19406df-a7e5-4591-9d4f-ca412c13a92f.png)
![image](https://user-images.githubusercontent.com/120790343/218306914-a7673fa3-2552-459c-afb0-14687d2fe1be.png)
Link for MongoDB Chart: [CLICK HERE](https://charts.mongodb.com/charts-project-0-bzacq/public/dashboards/a5e98a4b-2363-4e02-abe5-21694ddf0665)

### How to Run the Code:
- In Config.ini file Add your Keys and tokens of Twitter API
- Add Your MongoDB Atlas URI in the IPYNB file  
![image](https://user-images.githubusercontent.com/120790343/218308232-bc0ef02f-1b2f-498c-8a63-69e520d9f884.png)
- Upload the **movie_T_V** (JSON DATA File) in Your MongoDB Atlas DataBase, **_Link to get movie_TV:_** [Click](https://drive.google.com/file/d/1D6ksPbcjBBsZcFVpGxi79R1S1y_fF-zb/view?usp=sharing)
- Run the IPYNB File 
- Don't Run the **Function To Add the Movie Name, Tweet_Type and Coordinates of location of Tweet**
- Only run If you Added New data into the DataBase (Because it creates the Features for Whole Documents in the Database Once again if already excist too)

**Extra MongoDB Chart For Covid Analysis With the same Code:**
> ![image](https://user-images.githubusercontent.com/120790343/218308255-651ae3fe-c81e-4a3a-9b3f-1bbe9393d2a2.png)
Link for MongoDB Chart: [CLICK HERE](https://charts.mongodb.com/charts-project-0-bzacq/public/dashboards/88c769d6-23f9-4e9c-8e22-2d631e25c873)

Simple SQL Querries are there in the end of IPYNB File!
