# Predict stock sentiment from Social Media

Using labelled data from StockTwits (tweet-style social media site discussing stocks), trained an LSTM recurrent neural network on the labelled data.

Trained model has a ±70% accuracy.
Example output for the tweet: "Google is working on self driving cars, I'm bullish on $goog"

| Rating       | Probability |
| ------------ | ----------- |
| 0 (negative) | 0%          |
| 1            | 2%          |
| 2            | 1%          |
| **3**        | **71%**     |
| 4 (positive) | 26%         |


