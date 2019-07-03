# Problem Statement

A bank from Europe has been collecting some data from its own customers about their financial habbits. The data was not only restricted to the financials of a customer only. This include other attributes like Age, Location, Gender, Number of products that the customer is using, etc.

For some time now, the bank started observing that the customers have been leaving the bank after staying only 6 months.

We have to figure out what is happening to these custsomers and why are the leaving. Also, we have to figure out if a customer will leave (highest probability of leaving) the bank in the next 6 months, based on the behaviour of the other customers with similar financial features and habbits.

## Assumptions

I made some assumptions before starting this project. I performed some feature engineering to reduce not very useful features from the dataset which would have created noise in our analysis. This feature engineering reduced the dimensionality of the data and made the model run quicker.

## Model Extensions

This same model can be extended to other possible cases, e.g. 1) Will the customer be approved for a loan, 2) Will the customer deposit X amount of money in the next X months, 3) Will the customer pay the bills on time. i.e. MOST of the problems with a binary outcome can use this basic deep learning model.
