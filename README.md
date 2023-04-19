# March Madness Prediction

## About

This is our mini-project for SC1015 (Intro to DSAI). The dataset is taken from [March Madness Data](https://www.kaggle.com/datasets/nishaanamin/march-madness-data). March Madness is a single-elimination basketball tournament played in the United States among 68 college/university teams. According to the [American Gaming Association (AGA)](https://www.forbes.com/sites/jayginsbach/2023/03/12/2023-ncaa-tournament-betting-68-million-americans-to-wager-on-march-madness/?sh=6ef2aec2eb24), 68 million American adults planned to wager an estimated 15.5 billion on this year's 2023 NCAA Men's Division I Basketball Tournament. March Madness is one of the best traditions in sports. As sports enthusiasts ourselves, let us see if we can make better predictions through the power of data science and artificial intelligience. 

## Contributors

Choo Kean Yee (@keaneallen) - Exploratory Data Analysis, Random Forest 

Aaron Lowe (@swalowe) - Multi-Variate Classification Tree, Video Presentation

Chiam Zheng (@chiamzheng) - Poisson Model, Video Editing

### Problem Statement

What are the key performance metrics in predicting success in March Madness? 

Can we use these metrics to build a predictive model?

### Models Used 

Poisson Model

Multi-Variate Classification Tree

Random Forest Classification

### Conclusions

1) Multi-Variate Classification Tree and Random Forest Model improved accuracy overall compared to randomly choosing which teams would be successful. 
2) Poisson Model did not work well due to non-linearly correlated variables and other limitations. 
3) Using the classification tree model on 2023's pre-tournament data to predict success, there was low accuracy compared to the years we trained the model on (2008-2022). This is likely due to the high amount of variance in a single-elimination game. 

### References 
https://www.kaggle.com/datasets/nishaanamin/march-madness-data
https://www.forbes.com/sites/jayginsbach/2023/03/12/2023-ncaa-tournament-betting-68-million-americans-to-wager-on-march-madness/?sh=641808132eb2
https://www.datacamp.com/tutorial/random-forests-classifier-python
https://stats.oarc.ucla.edu/r/dae/poisson-regression/

