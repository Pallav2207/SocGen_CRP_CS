# Named Entity Recognition for Financial Crimes : Corporate Research Project with Societe Generale

The purpose of this analysis is to perform named entity recognition (NER) on a transaction-level dataset for the financial crimes team in the sanctions and embargo division of Societe Generale. The goal of this analysis is to identify entities related to potential financial crimes, such as sanctioned individuals, countries, or entities involved in money laundering.

## Data

The data for this analysis consists of a transaction-level dataset containing information on transactions processed by Societe Generale. We have created synthetic dataset based on the observed patterns and relevant information for the project as discussed with the Data Science team of Societe Generale. The dataset might contain the following variables:

- `AccountNumber`: Unique identifier for an indiviual's bank account
- `Entity/Recipient`: Name of the recipient or the entity
- `Address`: Location of the recipient
- `Noise`: Noise or randomness present in the data due to various known or unknown factors

## Methods

We will be using the natural language processing libraries and various neual network architectures in Python to perform Named Entity Recognition (NER) in the dataset. We will leverage a pre-trained model as baseline and then train a custom NER model using labeled synthetic data to identify entities related to potential financial crimes.

## Results

After training the NER model on the labeled data, we plan to evaluate the model performance on various metrics like accuracy, F1 score, etc (to be further discussed upon) on the test data. The model should be able to identify entities related to potential financial crimes with good accuracy,  precision and recall.


