In this study, the impact of external and internal textual information polarity and sentiment on the accuracy of financial crisis early warning models was investigated. This study utilizes a web crawler to collect the MD&A text from 10-K reports and the financial news headlines from news website for the listed firms in the US market, using the timeframe from 2014 to 2022, and then employs textual analysis techniques to extract sentiment and polarity of this textual data. Afterwards, this study compares the early warning impact of financial distress by combining the textual data with conventional financial indicators.

The findings indicate that the integration of emotional tone indicators of news headlines text does not significantly increase the ability of the model to detect financial distress early on and has a detrimental effect on some models' ability to forecast future events. However, the polarity of financial news headlines is the feature with the highest importance for forecasting financial distress in the final model after the hyperparameters tuning. The next finding is that the early warning signals of financial distress of listed companies can be improved and made more accurate by adding emotional tone indications of MD&A sections (internal textual data). Nevertheless, the research must be carried out carefully since the MD&A text might become a subject of manipulation on behalf of the company. 

The classification abilities and performance of the boosting models including Light GBM, Cat Boost, XG Boost, and Random Forest remain steady and precise under four different sets of input feature variables. The four models mentioned above can be utilized as somewhat best classifiers across the selected for financial crisis early warning systems. Moreover, the final model trained after tuning or the hyperparameters showed the high accuracy (more than 90%) in the test set and a positive recall. This model might be considered as the object for future research and modeling on different datasets. 
