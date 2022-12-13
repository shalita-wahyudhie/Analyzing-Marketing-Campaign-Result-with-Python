Analyzing marketing campaign results with Python

Data science has many use in marketing such as, analyzing marketing campaign performance, A/B testing, and answering questions like "how different marketing channels are performing?" or "given current conversion rate and revenue, should we continue investing in this channel?".

In this project, I utilize python to analyze marketing campaign result using 
- pandas
- numpy
- matplotlib
- scipy
- seaborn


Marketing metrics I used in this project uncluding:
1. conversion rate, of all people that got in contact with the campaign, how many of them actually bought the product? (i.e. made a purchase, subscribed)
2. retention rate, how many subscribers stay subscribed after an amount of time?
3. Lift, the relative impact of treatment on control (A/B testing)

Summary :

1. Most ads are in english and there are numbers of ads that are sent out in the wrong languague (not the preferred language)
2. House ads conversion rate dropped likely due to the language of the ads not matching the preferred language of viewer
3. Lost subscribers due the the language bug is estimated to be 32 (1 Month campaign period)
4. Overall lift of treatment over control in A/B testing is 80%
5. Younger viewers (up to 30 yrs) have higher conversion rate with personalized ads compared to control ads.
6. Conversion rate on older viewers who recieved the personalized ads are lower than the ones who recieved the control ads.
7. Personalized ads perform much better in some marketing channels compared to the others (positive lift in Instagram, Facebook, Push, and Email)
8. Personalized ads doesn't give positive change in conversion rate for house ads
9. House ads are marketing channel with most viewers from every age group

Recommendation:

1. Company should pay attention to the languages the ads were send in since it is proven to be a factor in the conversion rate.
2. Personalize ads only for viewers aged up to 30 years and not older.
3. Company don't have to invest more to personalize ads on website (house ads) 
4. Company should continue and improve the personalization of ads in Facebook, Instagram, and Push that is the channels with high lift for the personalized ad.
