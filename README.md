# Project Name
> Automatic Ticket Classification Case Study


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
We need to build a model that is able to classify customer complaints based on the products/services. By doing so, we can segregate these tickets into their relevant categories and, therefore, help in the quick resolution of the issue.

We will be doing topic modelling on the .json data provided by the company. Since this data is not labelled, we need to apply NMF to analyse patterns and classify tickets into the following five clusters based on their products/services:

1. Credit card / Prepaid card
2. Bank account services
3. Theft/Dispute reporting
4. Mortgages/loans
Others

With the help of topic modelling, we will be able to map each ticket onto its respective department/category. we can then use this data to train any supervised model such as logistic regression, decision tree or random forest. Using this trained model, we can classify any new customer complaint support ticket into its relevant department.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Results
Logistic Regression has highest accuracy of 0.95. It is good fit for this case study.


<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- python - version 3.9.7

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
- This project was done as part of Machine Learning module in ML and AI program conducted by IIITB and upgrad. I thank all the mentors, coworked and faculty at UpGrad and IIIT Banglore for their continuous guidance throughtout this course.

## Contact
Created by [@SaiSatwikK] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
