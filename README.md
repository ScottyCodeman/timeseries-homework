# timeseries-homework
## [Google Colab link](https://drive.google.com/file/d/156uFIkBhIXeCLGP5Gdrnl03RLtreaJn5/view?usp=sharing)
# MercadoLibreLinks Analyst 

# I'm a growth analyst at MercadoLibreLinks to an external site.. With over 200 million users, MercadoLibre is the most popular e-commerce site in Latin America. I've been tasked with analysing the company's financial and user data in clever ways to help the company grow. So, I want to find out if the ability to predict search traffic can translate into the ability to successfully trade the stock.

## First I ploted the data for the Google search trends based on the company and focused on the month of May
![trendsmay](Resources/timeseries_1.jpg)

## Then with that data I checked out the traffic based on the day of the week
![searchtraffic](Resources/timeseries_2.jpg)

## I then dove deeper with a heatmap cisualization of the hour and day of the week for the Search Traffic
![heatmap](Resources/timeseries_3.jpg)

## Then I took a look at the Stock trends and the connection between the Search traffic
![stocktrends](Resources/timeseries_5.jpg)
### I found that as the stock price increases in value, the search traffic becomes increasingly volatile.
![volitile](Resources/timeseries_6.jpg)
## I then used Prophet to predict and forecast possible trends of what the company could be looking at
![forecast](Resources/timeseries_7.jpg)
## I then used the data from Prophet to figure out the yhat(prediction) and the uncertianty of that prediction(yhat_lower, yhat_upper)
![yaht](Resources/timeseries_8.jpg)

## Then I plotted the trends over the year,week, and how it would look on a daily basis 
![trends](Resources/timeseries_9.jpg)
### Useing this data we can find what the peak times are to push for advertising or other marketing areas.

## Then produced a Sales forecast to predict future sales based on the information provided and the analysis done
![futuresales](Resources/timeseries_10.jpg)
### Using that I setup a dataframe and calculated the most likely, best and worst case with the predictions
![Case](Resources/timeseries_11.jpg)




