# Credit_Risk_Analysis

## Overview
### The purpose of this analysis is to determine which of the following 6 models is the best at determining credit card risk.

## Summary
### RandomOverSampler
<img width="803" alt="Screen Shot 2021-12-21 at 3 23 12 PM" src="https://user-images.githubusercontent.com/88937178/146992906-c70fea99-5459-4be0-a131-4a4e5a045677.png">
-The balanced accuracy score is 65%. 
-The high_risk precision is about 1% only with 61% sensitivity which makes a F1 of 2%. 
-Due to the high number of the low_risk population, its precision is almost 100% with a sensitivity of 68%.

### SMOTE
<img width="812" alt="Screen Shot 2021-12-21 at 3 36 26 PM" src="https://user-images.githubusercontent.com/88937178/146994570-af39b966-bb6b-4904-b911-20711db4f903.png">
-The balanced accuracy score is 65%. -The high_risk precision is about 1% only with 61% sensitivity which makes a F1 of 2%. -Due to the high number of the low_risk population, its precision is almost 100% with a sensitivity of 64%.

### ClusterCentroids
<img width="805" alt="Screen Shot 2021-12-22 at 12 00 27 AM" src="https://user-images.githubusercontent.com/88937178/147038320-e9ff06bb-fe4d-4be7-a707-5a67f541d45e.png">
-The balanced accuracy score is 62%. -The high_risk precision is about 1% only with 67% sensitivity which makes a F1 of 1%. -The low_risk precision is 100% with a sensitivity of 42%.

### SMOTEENN
<img width="821" alt="Screen Shot 2021-12-22 at 12 03 02 AM" src="https://user-images.githubusercontent.com/88937178/147038511-fe838e8a-230e-4f0b-9c0c-11b4b0fb9cf3.png">
-The balanced accuracy score is 52%. -The high_risk precision is about 1% only with 70% sensitivity which makes a F1 of 2%. -The low_risk precision is 100% with a sensitivity of  58%.

### BalancedRandomForestClassifier
<img width="728" alt="Screen Shot 2021-12-22 at 12 15 52 AM" src="https://user-images.githubusercontent.com/88937178/147039501-13b30300-191d-4bd7-b198-3f1760091a98.png">
-The balanced accuracy score is 79%. -The high_risk precision is about 4% only with 67% sensitivity which makes a F1 of 7%. -The low_risk precision is 100% with a sensitivity of 91%.

### EasyEnsembleClassifier
<img width="731" alt="Screen Shot 2021-12-22 at 12 18 23 AM" src="https://user-images.githubusercontent.com/88937178/147039679-70f61504-0d15-4133-84d3-a7883dad8def.png">
-The balanced accuracy score is 93%. -The high_risk precision is about 7% only with 91% sensitivity which makes a F1 of 14%. -The low_risk precision is 100% with a sensitivity of  91%.
