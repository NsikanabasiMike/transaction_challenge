## Table of Contents
- [Installation](#install)
- [Introduction and Problem Statement](#intro)
- [Project Motivation](#motivate)
- [File Descriptions](#describe)
- [Licensing, Authors, and Acknowledgements](#acknowledge)

<a id='install'></a>
### Installation
1. Python 3.6 and latest from [here](https://www.python.org/downloads/)
2. Anaconda distribution of Python from [here](https://www.anaconda.com/blog/anaconda-distribution-2022-10#).<br>

<a id='intro'></a>
### Introduction and Problem Statement
The Tunisian Company of Electricity and Gas (STEG) is a public and a non-administrative company, it is responsible for delivering electricity and gas across Tunisia. The company suffered tremendous losses in the order of 200 million Tunisian Dinars due to fraudulent manipulations of meters by consumers.<br>

Using the client’s billing history, the aim of the challenge is to detect and recognize clients involved in fraudulent activities.
The solution will enhance the company’s revenues and reduce the losses caused by such fraudulent activities.<br>

<a id='motivate'></a>
### Project Motivation
This project is about applying data analytics and Machine Learning(ML) skills to gather, clean, analyze, and build a ML classifier pipeline that classifies transactions whether fraudulent or not.  

<a id='describe'></a>
### File Descriptions
The data used is provided by STEG. It is composed of two files. The first one is comprised of client data and the second one contains billing history from 2005 to 2019. The data can be downloaded [here](https://zindi.africa/competitions/fraud-detection-in-electricity-and-gas-consumption-challenge/data).<br>  

There are 2 .zip files, train.zip, and test.zip and a SampleSubmission.csv. In each .zip file you will find a client and invoice file.

__Variable definitions__

1. Client:

- Client_id: Unique id for client
- District: District where the client is
- Client_catg: Category client belongs to
- Region: Area where the client is
- Creation_date: Date client joined
- Target: fraud:1 , not fraud: 0
- Invoice data

2. Invoice data:

- Client_id: Unique id for the client
- Invoice_date: Date of the invoice
- Tarif_type: Type of tax
- Counter_number:
- Counter_statue: takes up to 5 values such as working fine, not working, on hold statue, ect
- Counter_code:
- Reading_remarque: notes that the STEG agent takes during his visit to the client (e.g: If the counter shows something wrong, the agent gives a bad score)
- Counter_coefficient: An additional coefficient to be added when standard consumption is exceeded
- Consommation_level_1: Consumption_level_1
- Consommation_level_2: Consumption_level_2
- Consommation_level_3: Consumption_level_3
- Consommation_level_4: Consumption_level_4
- Old_index: Old index
- New_index: New index
- Months_number: Month number
- Counter_type: Type of counter.<br>
3. SampleSubmission.csv: This shows the submission format for this competition, with the ‘ID’ column mirroring that of Test.csv and the ‘target’ column containing your predictions. The order of the rows does not matter, but the names of the ID must be correct.<br>

#### Uploaded Files
Two files are uploaded:
1. transaction_challenge.ipynb: This is a notebook containing all the code for analysis, modeling, and results.
2. submission.csv: Thisis a csv file that stores the predictedclasses of transactions for each client.<br>
<a id='acknowledge'></a>
### Licensing, Authors, Acknowledgements
The data used is from Tunisian Company of Electricity and Gas (STEG) and is hosted by [Zindi Africa](https://zindi.africa/) for Machine Learning competition purposes.