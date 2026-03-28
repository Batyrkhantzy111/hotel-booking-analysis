# Hotel Booking Price Analysis

Analysis of hotel booking data to understand what drives room prices.

**Dataset:** [Hotel Booking Demand](https://www.kaggle.com/datasets/jessemostipak/hotel-booking-demand) - 119,390 bookings from two hotels in Portugal (2015–2017)

## What I did

- Explored the dataset: distributions, missing values, outliers
- Built a simple linear regression using only lead time → R² = 0.0005 (terrible, but expected)
- Built a multiple regression with 6 features → R² = 0.1655
- Compared models and interpreted each coefficient

## Key findings

- Number of guests is the strongest price predictor (+€25 per guest)
- Repeat guests pay €28 less - probably loyalty discounts
- Lead time has almost no effect on price, which surprised me
- 6 features only explain 16.5% of price variation - room type and seasonality would likely matter much more

## Stack

Python · pandas · NumPy · scikit-learn · seaborn · matplotlib · scipy
