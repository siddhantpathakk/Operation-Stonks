# Operation Stonks
This is our first year project under the course CZ1115: Introduction to Data Science and Artificial Intelligence.

### Motivation:
Can we predict the opening, closing prices, as well as the highs and the lows of a stock, given its past data? Can we predict if the next month is a good time to invest in a
particular company or not based on the Random Forest Classification Model? Is it possible to derive a relationship between stock volatility and volume based on past data?

### Problem Definition:
We aim to prepare a useful model to determine whether to invest in a specific company in the next month, given its past data.

### Dataset Source:
The dataset has been obtained from the Alpha Vantage Stock API. It is a dynamic dataset, i e its information is periodically updated on a daily basis It required importing of the Alpha Vantage API as a Python module. 

Source: https://www.alphavantage.co/documentation/ (requires FREE API KEY)

### Procedure:
The jupyter notebook is roughly divided into three segments: 

1.) Time Series Analysis 

2.) Random Forest Classification

3.) Clustering and Anomaly Detection

We first clean the data, introduce essential variables (both numerical and categorical) and then explore it to understand patterns and trends within the data.

Then, we predict the opening, closing as well as the highs and the lows of a stock, given its past data. We trained the Random forest classfier model to decide whether to invest in a particular stock given its volatility, and monthly difference. We further used the clustering model to divide and segregate the data into clusters and looking upon the low contamination rate, we went ahead with anomaly detection.

### Authors and acknowledgment:
This project was created by the members of Team 1, namely, Siddhant Pathak, Dhruv Hariharan, and Anant Gupta, from the lab group FSP8 as our first year project, under the course CZ1115: Introduction to Data Science and Artificial Intelligence.

The members of the team express their gratitude and thanks to Professor Dr Sourav Sen Gupta and lab instructor Hou Jingwen, whose constant support and guidance made this project possible.

License
MIT License

Copyright (c) 2021 Siddhant Pathak

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

