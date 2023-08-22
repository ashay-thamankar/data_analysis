# playstore_app_analysis
Comprehensive playstore apps analysis

We will compare thousands of apps in the Google Play Store so that we can gain insight into:

How competitive different app categories (e.g., Games, Lifestyle, Weather) are

Which app category offers compelling opportunities based on its popularity

How many downloads you would give up by making your app paid vs. free

How much you can reasonably charge for a paid app

Which paid apps have had the highest revenue

How many paid apps will recoup their development costs based on their sales revenue

To be noted:

Obviously, the data is just a sample out of all the Android apps. It doesn't include all Android apps of which there are millions.

We will assume that the sample is representative of the App Store as a whole. This is not necessarily the case as, during the web scraping process, this sample was served up based on geographical location and user behaviour of the person who scraped it - in our case Lavanya Gupta.

The data was compiled around 2017/2018. The pricing data reflect the price in USD Dollars at the time of scraping. (developers can offer promotions and change their app’s pricing).

We converted the app’s size to a floating-point number in MBs. If data was missing, it has been replaced by the average size for that category.

The installs are not the exact number of installs. If an app has 245,239 installs then Google will simply report an order of magnitude like 100,000+. Here we removed the '+' and we’ll assume the exact number of installs in that column for simplicity.
