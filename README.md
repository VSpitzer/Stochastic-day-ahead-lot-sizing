# Stochastic-day-ahead-lot-sizing
Open-access data for reproducibility of the numerical experiments in the article "Day-ahead lot-sizing under uncertainty: An application to green hydrogen production" 

In Data:
  - The "grid_price" file indicates the hourly electricity prices over the year 2016 in France.
  - The "Wind_Power" files represent the historical and simulation data of hourly forecasted and actual wind power.
  - The "quantiles" file represents the minimum guaranteed hourly wind power corresponding to the simulation dataset.
  - The "Scenario_sets" repository represent the sampled scenarios used for the simulation presented in the mentionned article.

In src:
  - A notebook is available to reproduce the scenario generation method of the mentionned article, by training and evaluating the method on the wind power data available in the "Data" repository.
  - "Scenario generation VAE" corresponds to the neural network used to generate the scenarios of the simulation presented in the article.

Licence:
  -  The notebooks, and other documents are released under a CC BY-NC-SA 4.0 license.
  -  The forecasted and actual wind power datas are derived from an original work by C. Lalanne: https://github.com/CA683-Group99/Wind-Energy-Prediction.
    
