Performance Engineering Lab, UCD
==========================================================

This repository contains a set of synthetic datasets that were generated with COCOA framework and which aim to broaden the scenarios for testing anonymization algorithms. They are used in the research activities of the **Performance Engineering Laboratory** at the [School of Computer Science (University College Dublin)](http://www.csi.ucd.ie).

Related Papers
----------------------
### 1. COCOA: A Synthetic Data Generator for Testing Anonymization Techniques (https://link.springer.com/chapter/10.1007/978-3-319-45381-1_13)
Please cite as: Ayala-Rivera, V., Portillo-Dominguez, A., Murphy, L. & Thorpe, C. "COCOA: A Synthetic Data Generator for Testing Anonymization Techniques." Privacy in Statistical Databases Conference, Dubrovnik, Croatia, September 2016.

### 2. A Systematic Comparison and Evaluation of k-Anonymization Algorithms for Practitioners  (http://www.tdp.cat/issues11/tdp.a169a14.pdf)
Please cite as: Ayala-Rivera, V., McDonagh, P., Cerqueus, T. & Murphy, L. "A Systematic Comparison and Evaluation of k-Anonymization Algorithms for Practitioners." Transactions on Data Privacy Journal, 2014; Volume 7 Issue 3.

### 3. Synthetic Data Generation using Benerator Tool (https://arxiv.org/pdf/1311.3312.pdf)
Please cite as: Ayala-Rivera, V., McDonagh, P., Cerqueus, T. & Murphy, L. "Synthetic Data Generation using Benerator Tool." Technical Report UCD-CSI-2013-03, University College Dublin, November 2013.

Datasets
----------------------

### 1. [Adult Datasets] (https://github.com/ucd-pel/COCOA/tree/master/adultCOCOA) ###

This dataset is based on the Adult census dataset from the UCI Machine Learning Repository (https://archive.ics.uci.edu/ml/datasets/Adult). It is composed of 9 socio-economic demographic attributes (e.g., occupation, education, and salary class).

### 2. [German Credit Datasets] (https://github.com/ucd-pel/COCOA/tree/master/germanCOCOA) ###

This dataset is based on the German Credit dataset from the UCI Machine Learning Repository (http://archive.ics.uci.edu/ml/datasets/Statlog+%28German+Credit+Data%29). It is composed of 20 credit-related attributes (e.g., employment, purpose of credit, credit class). 

### 3. [Insurance Datasets] (https://github.com/ucd-pel/COCOA/tree/master/insuranceCOCOA) ###

These datasets correspond to data containing records with social and demographic information from individuals. This information corresponds to attributes such as their age, occupation, workplace, favorite recreational activity and places where this is practiced. Moreover, this datasets contain two classification attributes (risk of accident and salary class).

### 4. [Irish Census Datasets] (https://github.com/ucd-pel/COCOA/tree/master/irishCensusCOCOA) ###

The generated datasets correspond to microdata containing records with social, economic and demographic data which mimics the distribution of aggregated statistics from the 2011 Irish Census data. More details about the values of each attribute, the methodology followed to generate these datasets, and how the datasets were used in experiments of anonymization can be found at the following papers:

COCOA: A Synthetic Data Generator for Testing Anonymization Techniques (https://link.springer.com/chapter/10.1007/978-3-319-45381-1_13)

Synthetic Data Generation using Benerator Tool (https://csiweb.ucd.ie/files/UCD-CSI-2013-03.pdf)

