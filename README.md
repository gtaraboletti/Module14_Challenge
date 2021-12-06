# Module14_Challenge
Module 14 UNCC FinTech Boot Camp Challenge Homework

## Libraries and Dependencies ##

import pandas as pd
import numpy as np
from pathlib import Path
import hvplot.pandas
import matplotlib.pyplot as plt
from sklearn import svm
from sklearn.preprocessing import StandardScaler
from pandas.tseries.offsets import DateOffset
from sklearn.metrics import classification_report

## Contributors ##

Giselle Taraboletti
UNCC FinTech Boot Camp

## Baseline SVM Model ## 

  ![baseline](https://user-images.githubusercontent.com/89159824/144774830-e180a89b-9a7a-4afa-9cd1-96e1b6221707.png)


## SVM DateOffset 4 months ##

  

## SVM DateOffset 6 months ## 
  

## Linear Regression Model ## 

  

## Conclusions ##

Looking at the baseline SVM models, the version with the DateOffset parameter set to 6 months had the same accuracy as the 4 month offset, but the 6 month was more precise. The 4 month SVM was more accurate but less precise than the baseline. The 6 month was both more accurate and more precise than the baseline. Overall, the version of the SVM with the DateOffset set to 6 months is the best version to use of those tested. Comparing the 6 month SVM to the Linear Regression model, the 6 month SVM is more accurate. However, the two models were equally precise. If I were to recommend a model to use, I would suggest the 6 month offset SVM. 

## License ## 

MIT License

Copyright (c) [year] [fullname]

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.







