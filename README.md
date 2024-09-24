# Project - Analysing Online Store Data using Excel

### Data Source
The Data in this project was obtained from Kaggle and imported into Excel.

### Methods Employed
- Conditional Formatting,
- Pivot Tables/Charts (Visualisation),
- Standardisation, and
- Dashboarding.

# 1 - Introduction
Ah, welcome, dear reader, to the chronicles of Data Analysis, where deductive prowess meets the realm of numbers and spreadsheets. In this Excel escapade, much like a skilled detective combing through clues, I embarked on a quest to unravel mysteries concealed within the data. Join me, reader, as we venture forth into the realm of data driven deduction, where every cell and formula holds potential for enlightenment. Let us begin!

# 2 - Cleaning and Transformation
The data had been obtained as follows:
<p align="center">
<img src="RAW DATA.png">
</p>

Employing my keen eye for detail, I meticulously cleaned and transformed the raw data, casting aside veils of ambiguity to reveal its true essence.

<p align="center">
<img src="CLEAN DATA.png">
</p>

Conditional Formatting was, of course, employed along with some sorting and standardisation. For instance:
```excel
=IF(L2=0, "Digital Wallets", IF(L2=1, "Card", IF(L2=2, "PayPal", "Other")))
```

# 3 - Utilising Pivot Tables
With the precision of a master sleuth, I employed the formidable tools of Pivot Tables and dynamic charts to scrutinise every nook and cranny of the dataset, extracting insights with a keen intellect. Each Pivot Table served as a magnifying glass, uncovering hidden patterns and correlations, while the charts painted a vivid picture of the data's intricate tapestry.

Observe the example below:

<p align="center">
<img src="PAYMENT METHOD.png">
</p>

# 4 - Finally, Dashboarding
And now, behold, the culmination of my analytical exploits -- a Dashboard, akin to a map in my hands, providing a panoramic view of the data landscape. Through this Dashboard, we embark on a journey of discovery, navigating the twists and turns of statistical intrigue with the same flavour that propels me through the labyrinth of all datasets.

<p align="center">
<img src="DASHBOARD - FINAL.png">
</p>

# 5 - Recommendations (Conclusion)
Ah, the case of the Online Store, a veritable conundrum of commerce concealed within the digital ether. Having unraveled the tangled web of data and presented my findings upon the Dashboard canvas, it is now time to deduce our next course of action, much like the concluding chapter of a thrilling tale.

First and foremost, direct your attention to the Time Series Line Chart, a chronicle of revenue fluctuations across months. A keen eye must be cast upon the patterns and anomalies that emerge from this temporal tapestry. Should we observe a consistent upward direction, it may signal a successful strategy worthy of replication. Conversely, any sudden dips or spikes demand scrutiny, for they may conceal the subtle machinations of market forces or internal operations.

Then, scrutinising the distribution of Sex among the clientele. Understanding the demographics of a customer base provides invaluable insights into their preferences and behaviours. Are certain products resonating more strongly with one gender over the other? - It seems to be the so in this case, with Females constituting most of the customer base.

Also, not overlooking the types of payment methods favoured by these discerning customers - we must remember that the Devil is in the details. There are two particular payment methods that seem to be popular among the customers - Card Payments and Digital Wallets. Perhaps the online store should make these methods more accessible? These insights may be a key to optimising the store's payment infrastructure and enhancing customer experience.

Dear reader, this  chapter of our analytical odyssey concludes here. Armed with the insights obtained from our Dashboard, let us embark upon our next adventure in the realm of e-Commerce, ever vigilant for clues and opportunities to refine our strategies and unlock greater success.





