This project analyses mobile phone data, with the aim of creating a prediction model that can accurately predict which features most likely influence the price of the mobile phones sold.

The dataset obtained from Kaggle contains a number of variables pertaining to different mobile devices including: battery life, bluetooth, wifi, 3g/4g etc.

I began by checking that there are no empty rows in my dataset, then proceed to explore the data by creating informative relationship charts using univariate and bivariate analysis tools. In doing this, I identify the following patterns/relationships for the period that the data covers:

- customers have favored dual sim phones over single-sim phones
- customers have favored phones with wifi capabilities over the ones without
- more customers have purchases phones without bluetooth capability than the ones with bluetooth; and
- customers prefer phones with less battery power than those with more (perhaps because the latter is more expensive)
- also, I observed that dual sim phones, and bluetooth/wife-enabled phones are more expensive than their counterparts

Ultimately, the exploratory analysis revealed that customers were not merely driven by price but by the benefits they can derive from their choice of phones e.g., ability to use more than one sim, and the numerous benefits of wifi-enabled phones such as stronger battery life, faster internet connection and lesser mobile data costs.

Further, I analysed the available features (using feature selection tools) and developed a logistic regression model to determine which features most significantly impact the price sensitivity. In doing so, I discovered that while the weightiest features are RAM, battery power and phone width (with a 96% accuracy level); all features equally contribute to price sensitivity with an accuracy of 97%.

The analaysed features include:
- battery power
- bluetooth functionality
- clock-speed (speed at which microprocessor executes instructions)
- dual sim availability
- front camera megapixels
- 4G availability
- internal memory space (in Gb)
- mobile depth (in cm)
- number of cores of processors
- primary camera megapixels
- pixel resolution height
- pixel resolution width
- RAM (in Mb)
- height of mobile screen (in cm)
- width of mobile screen (in cm)
- talk time - longest talk time each battery charge cycle will last
- 3G availability
- touch screen functionality
- wifi functionality
- price range (target feature) - ranging from 0 to 3 to depict low cost, medium cost, high cost and very high cost.
