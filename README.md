# Finance: stock market  
It is a collection of Jupyter notebooks that contain Python code on stocks to help investors make better decisions
### Update   
In this file, I created a matrix that contains the current price of a stock and also determines its change
### Stock Distribution and Prediction
In this file, I create and simulate a normally distributed random variable. In the second part, I create a multivariate normal variable and simulate it. Lastly, I perform a bootstrap simulation. At the end of the file, I develop a Dash app that provides the user with the option to select a stock and 'N' days. The app displays a graph of the closing price accompanied by two prediction graphs: one derived using the bootstrap method and the other based on the normal distribution method. Additionally, the app presents a summary table with the mean of the stock, standard deviation (SD), and sequence.
![new_fileupdate](https://github.com/yonatanaizen/Finance/assets/114994667/ff8fed42-5c1f-4117-8e08-137e508d3175)
### Regression 
In this file, I will calculate the coefficient $\beta$ for various stocks. We will define $y$ as the stock and $X$ as the reference index. The coefficient $\beta$ represents the expected percent change in the stock (y) for each unit (percent) change in the reference index (X).
$\hat{\beta}$ is the parameter that minimizes $argmin(y-\hat{y}) = argmin(y-\beta \cdot x) = argmin(||y-XB||^2)$. Therefore, the estimated value of $\beta$ can be calculated as $\hat{\beta} = (X^TX)^{-1}X^TY$.
### Bayes 
In this file, I will compute the probability that the next day will be positive.
To carry out this computation, I am using Bayes formula: $P(A|B)=\frac{P(A\bigcap{B})}{P(B)}$.
$P(A\bigcap{B})$ represents the probability that the next day will be positive,
and B denotes all the possibilities we have in the current state, given our knowledge of the previous sequence.
To gather information about these events, I used historical stock data and calculated the probability for each case.

### Information source 
yahoo finance
### Disclaimer
This is a starter project which may or may not offer advantages. Use it at your own risk. Any usage is the user's responsibility.
