# Seattle_Airbnb_Open_Data_NLP_Guest_Comment_Analysis


# 1) Here I am going to observe room prices regarding to date
# 2) Effects of client reviews on price.
# 3) Finally we are going to investigate  guest comments and prices and try to predict price of accommodation regarding to the guest comments.
# We have 3 dataset, 
#  Lets take a look what are they

# this dataframe shows  prices-dates-listing_id and availability
# so that we can may be extract some information of the seasonality of the prices 
/kaggle/input/seattle/calendar.csv


# Ok lets go to the next dataframe listings.csv here we will check correlation of price with some unexpected accommodation features.
/kaggle/input/seattle/listings.csv


# And finnally I am going to my a sentiment analysis with this that you can check the codes and comments are detaily explains the steps.
/kaggle/input/seattle/reviews.csv



# Prediction results can be discussed from different dimensions and model can be improved by combining review scores.
# Here I want to share my ideas about model predictions; price scales and guest comments can have an alignment however comments are regarding to the people's income levels and expectation 
# so that to deduce this can lead us to make mistake. From the otherside this can be used as a price adjustment tool for hosts. If the guests comments point you out as a high-luxirious 
# price scale accommodation why  would you set your price as a moderate price scale accommodation. Actually here in this case Cheap price scale accommodation comment accuracy is the lowest category
# this can show us some of these class accommodations are really cheaper than expected.
