# PlayStore Data Analysis EDA

    
Google Play is an online store where people go to find their favourite apps, games, movies, TV shows, books, and more. It provides 2 million apps & games to billions of people around the world, generating over $120 billion in earnings for developers to date. Helping developers scale their businesses globally it connect developers to billions of people around the world while investing in the platform, tools, services, and marketing opportunities that support apps and games businesses worldwide.
![](playstore_logo.webp)

# Data provided by :
Almabeter

The PlayStore-Analysis by using python libraries.
##


##  Project Files Description
This Project includes 1 colab notebook, 1 technical documentation as well as 1 presentation:
## Output: file
Google Colab - All the outputs are visible in the provided colab notebook.

## Input Files:
Play Store Data.csv - It contains the basic details of the playstore app like number of user reviews, ratings, installs, categories etc.

User Reviews.csv - It contains the user reviews and its sentiment score for the respective app.

## The contents of Play Store Data are :

* App: It contains the name of the app with a short description (optional).

* Category: This section gives the category to which an app belongs. In this dataset, the apps are divided among 33 categories.

* Size: The disk space required to install the respective app.
* Rating: The average rating given by the users for the respective app. It can be in between 1 and 5.
* Reviews: The number of users that have dropped a review for the respective app.
* Installs: The approximate number of times the respective app was installed.
* Type: It states whether an app is free to use or paid.
* Price: It gives the price payable to install the app. For free type apps, the price is zero.
* Content rating: It states which age group is suitable to consume the content of the respective app.
* Genres: It gives the genre(s) to which the respective app belongs.
* Last updated: It gives the day in which the latest update for the respective app was released.
* Current Ver: It gives the current version of the respective app.
* Android Ver: It gives the android version of the respective app.

## The contents of User Reviews are:

* Translated_Review: It contains the English translation of the review dropped by the user of the app.
* Sentiment: It gives the attitude/emotion of the writer. It can be ‘Positive’, ‘Negative’, or ‘Neutral’.
* Sentiment_Polarity: It gives the polarity of the review. Its range is [-1,1], where 1 means ‘Positive statement’ and -1 means a ‘Negative statement’.
* Sentiment_Subjectivity: This value gives how close a reviewer’s opinion is to the opinion of the general public. Its range is [0,1]. Higher the subjectivity, closer is the reviewer’s opinion to the opinion of the general public, and lower subjectivity indicates the review is more of a factual information.


## Problem Statements

> Which is best suitable android version for the apps
> which is the top category on playstore
> what is the ratting frequency
> Are majority of the apps Paid or Free?
> How Content Rating affect over the App?
> which category have top free Apps?
> Which category has the average no. of installations?
> find the average no of user reviews by the apps size.
> find top 10 apps by genreswice.
> what is the Sentiment Data Across the All Reviews.
> find the top 10 positive reviews apps.
> find the top 10 positive reviews apps.
> How are reviews and ratings co-related?
> Lets us discuss the sentiment subjectivity.
> how vary Content rating over the free and paid apps
> How is sentiment polarity varying for paid and free apps?
> Correlation between the Reviews and Installs
## Conclusion

In order to retain the customer base apps should be updated regularly Developers should develop apps such that their content is available for everyone. Bulky apps should be developed in the category like Game, Family. If developing paid apps then its price should not be high and size should be less than 20mb. Apps belonging to Game and Family Category have high negative reviews therefore they should be developed carefully. Like this there can be a lot of conclusions but we have tried to cover the most important ones. These are some of the aspects that the developer should research before proceeding with the app development. By conducting a simple exploratory data analysis (EDA) on the play store dataset, we not only eliminate avoidable risks of failure, but we may also be able to provide better ideas for building the app.

* Percentage of free apps = ~92%
* Percentage of apps with no age restrictions = ~82%
* Most competitive category: Family
* Category with the highest average app installs: Communication
* Percentage of apps that are top rated = ~80%
* There are 20 free apps that have been installed over a billion times
* Minecraft is the only app in the paid category with over 10M installs. This app has also produced the most revenue only from the installation fee.
* Category in which the paid apps have the highest average installation fee: Finance
* Most popular app in the Play Store based on the number of reviews: Facebook
* The median size of all apps in the play store is 12 MB.
* The apps whose size varies with device has the highest number average app installs.
* The apps whose size is greater than 90 MB has the highest number of average user reviews, i.e., they are more popular than the rest.
* Helix Jump has the highest number of positive reviews and Angry Birds Classic has the highest number of negative reviews.
## Credits
## 🔗 Links
![portfolio](https://img.shields.io/badge/my_portfolio-000?style=for-the-badge&logo=ko-fi&logoColor=white)
![linkedin](https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)
![Google colab]()

## References

* GeeksforGeeks
* Analytics Vidhya
* Stack overflow
* Towards data science
* Python libraries documentation
* Data camp


