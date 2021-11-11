# Stock-Predictor
>A stock price predictro using Regression and LSTM

---

## Table of Contents

- [Description](#description)
- [Usage](#usage)
- [Project Development and Working](#project-development-and-working)
- [License](#license)
- [Author Info](#author-info)

---

## Description

This was developed as my undergrad project. Stock price movement analysis is one main study area in algorithm trading. Although nobody in this world can predict the next-moment stock prices with an absolute 100% accuracy, the stock price change pattern is still one of the main interests of many investors. This project was made keeping in mind the small, novice investors who can benifit from a non-biased application based recomendation on purchasing, selling or holding stocks.

#### Technologies

- Python
- Machine Learning
- Linear Regrassion
- LSTM

[Back To The Top](#Stock-Predictor)

---

## Usage

Downnload the 3 .ipyb files and open them in Jupyter notebook and run one cell at a time.

[Back To The Top](#chatbot-game-v2)

---

## Project Development and Working

#### Data Pre-processing

  First we had to clean the data and add various new parameters. Wherever there were null or invalid values we reaplaced this with the mean, this can be seen in the [Reg-Clean&Prep-Process.ipynb](/Reg-Clean&Prep-Process.ipynb) file. We also clasify the day to day changes in few catogories namely Slight or No Change, Slight Positive, Slight Negative, Positive, Negative, Among Top gainers, Among Top Losers, Breakout Bull, and Breakout Bear. Below we can see the number of times the stock was in these catogories. 
  
  ![Image](Preprocessing.img)
 

#### Fitting 

There are two files for the fitting and clasification for LSTM pls see [this](/LSTM-Stock.ipynb) and for Regression pls look [here](Reg-Prediction.ipynb).

[Back To The Top](#Stock-Predictor)


---

## License

[Here](LICENSE)

[Back To The Top](#Stock-Predictor)

---

## Author Info

 - [Linkdin](https://www.linkedin.com/in/taher-mulla) 

 - [GitHub](https://github.com/taher-mulla)

 - Email - taher.mulla@gmail.com

[Back To The Top](#Stock-Predictor)

