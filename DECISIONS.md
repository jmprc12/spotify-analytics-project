# Decision Log
## Assignment 2: Dataset (2026-07-19)
- Dataset: Most Streamed Spotify Songs 2024 from Kaggle
- Main variable of interest: TikTok views because we wanted to see the emergence of the application as a tool to promote artists/music
- Key decision: We decided to choose Spotify Data because we were all interested in music, and we also knew that most people in this world are interested in music, so it had a real world use of the music industry.
## Assignment 3: Descriptive Stats (2026-07-26)
- Cleaning done: We filtered out each column of data by removing blank rows. This removed all blank cells from our data. 
- Most surprising pattern: The most surprising pattern was that songs from 2010-2020 was pretty even with songs from After 2020. This is surprising because this data set is from songs from 2024, so one would think that there would be a higher frequency of songs in the After 2020 category. 
## Assignment 4: Probability (2026-07-26)
- Normal vs. empirical, and why: We used the empirical method for our probability scenarios because all our variables that we used for these problems were skewed, so the empirical method was the best method to use.
## Assignment 5: Inference (2026-08-06)
- What we tested, alpha, conclusion: We tested the confidence interval for the mean of TikTok views, one-sample z-test for the mean of Spotify Streams with the claim being "The average number of Spotify Streams per song exceeds 500,000,000.", and a one-sample z-test for the mean of Spotify Popularity with the claim being "The average Spotify Popularity score differs from 65.", all with an alpha of 0.05. We concluded that we can be 95% confident that the mean TikTok Views are in between 1,054,062,359.49 and 1,509,722,548.33. We also concluded that at the 5% significance level, there is sufficient statistical evidence to conclude that the average number of Spotify Streams per song is greater than 500,000,000 (z = 13.27, p = 0.0000). The sample mean of 665,162,294 streams supports rejecting the null hypothesis. Lastly, we concluded that 
at the 5% significance level, there is sufficient statistical evidence to conclude that the average Spotify Popularity score differs from 65 (z = 10.53, p = 0.0000). The sample mean of 67.60 supports rejecting the null hypothesis.



## Assignment 6: Regression (2026-08-12)
- First predictor removed and why: Apple Music Playlist Count is the first predictor to be removed because it had the highest p-value of all of the predictors at 0.369. 
- Multicollinearity handling: Identified a strong correlation, 0.86, between Spotify Streams and Spotify Playlist Count using a correlation matrix. Tested removing each variable individually, making a new regression model and compared Adjusted R² for both options. Because the Adjusted R² for the regression model with Spotify Streams removed was slightly higher, we decided to go with that model. After doing another correlation model without Spotify Streams, there were no more variables with a high correlation.  
