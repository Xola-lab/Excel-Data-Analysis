# Project - Analysing Online Store Data using Excel

### Data Source
The Data in this project was obtained from Kaggle and importing into Excel.

# 1 - Introduction
Ah, welcome, dear reader, to the chronicles of Data Analysis, where deductive prowess meets the realm of numbers and spreadsheets. In this Excel escapade, much like a skilled detective combing through clues, I embarked on a quest to unravel mysteries concealed within the data. Join me, reader, as we venture forth into the realm of data driven deduction, where every cell and formula holds potential for enlightenment. The game is afoot!

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
And now, behold, the culmination of my analytical explots -- a Dashboard, akin to a map in my hands, providing a panoramic view of the data landscape. Throught this Dashboard, we embark on a journey of discovery, navigating the twists and turns of statistical intrigue with the same favour that propels me through the labyrinth of all datasets.

<p align="center">
<img src="DASHBOARD - FINAL.png">
</p>
