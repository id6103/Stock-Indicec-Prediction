# 30-Dow-Jones-Price-Prediction
This is coursework for INF 385T Introduction to Machine Learning
[Paper](https://jiachaof.github.io/paper/stock.pdf)
[Video](https://www.dropbox.com/s/y07sdlqba7ax0vn/ML.mp4?dl=0)

The research of stock index prediction has been conducted for years. However, the scope of the research is large because of the uncertainty and volatility of market. Compared with other data, the stock indices are relatively easy to obtain, which allows us to reduce the burden of finding ground-truth data. In this study, we build a stock index prediction model with better performance and give investors a direction when they make investment decisions.

The prediction accuracy of stock index of existing researches are lower than 70 percentage \cite{lai2014performance}, which is relatively low comparing to other machine learning tasks (e.g. image recognition). We assumed there are two main reasons behind this issue: first, there are too many influential factors of stock index, such as politics and economics; second, it lacks of applicable machine learning models for stock index prediction because of the limits of research on neural networks in the past years.

The focus of this work is finding input features and using recurrent neural network. We look for the data that is most likely to affect E-mini Dow (\$5) Futures; that is, the major events happened on each day and history of futures index. We train a LSTM model by using these related features. By doing so, our model is sensitive to the time and news that happened in the world. From our study, we find that news data happened more close to predicted index time, index history alone and more input data give better performance.




