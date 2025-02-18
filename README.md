>[!Note]
>This is an ongoing project. 

# 1. Introduction
This is a project of studying and forecasting the spot exchange rate. This project studies the USD/JPY pair with data from FRED (Federal Reserve Economic Data). 

# 2. Models
## 2.1 The Benchmark -- Random Walk
In Meese & Rogoff (1983)'s paper, three structural models are competing against the random walk model for their abilities to predict future spot exchange rate. 
The first structural model introduced is the 

The authors found out that the predicting power of the three structural model are no better than that of the random walk model. 

Two random walk models will be considered in this project. The first one is the random walk model without drift. Mathematically, we have
```math
S_{t+1} = S_{t}+\varepsilon
```
where $$S_{t+1}$$ is the spot rate at time $$t+1$$ and $$\varepsilon$$ is a white noise with zero mean. The second model that is considered is the random walk model with drift. 
```math
S_{t+1} = \alpha + S_{t} + \varepsilon
```
where $$\alpha$$ is a time independent constant. 
# 3. Data Source




# 4. References
Meese, R. A., & Rogoff, K. (1983). Empirical exchange rate models of the seventies: Do they fit out of sample?. Journal of international economics, 14(1-2), 3-24.

Rogoff, K. (2001). The failure of empirical exchange rate models: no longer new but still true. Economic Policy Web Essay, 1(1), 1-34.
