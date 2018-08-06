# US_Opiate_Presciptions

This [Kaggle dataset](https://www.kaggle.com/apryor6/us-opiate-prescriptions/home) contains information on prescription opiate overdoses by prescriber. From the Kaggle description:

> This dataset contains summaries of prescription records for 250 common opioid and non-opioid drugs written by 25,000 unique licensed medical professionals in 2014 in the United States for citizens covered under Class D Medicare as well as some metadata about the doctors themselves.

Due to the large and often binarized nature of this dataset, I decided to explore it with some supervised and unsupervised modeling techniques. I first looked at this dataset using a Random Forest Classifier to predict the boolean value for whether or not the prescriber prescribed opiate drugs more than 10 times in the year.
