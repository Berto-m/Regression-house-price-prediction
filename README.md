# House Prediction using linear regression. 
### Dataset
I used House Sales in King County, USA dataset from [kaggle](https://www.kaggle.com/harlfoxem/housesalesprediction)

I think when to it comes to predicting anything using ML, I like to think that all data is the same and let the model give me its best prediction. However, I also like to draw clonclusions. In this case, I did some imperical analysis.

Here we can conclude that houses that are closer to the water tend to be more expensive, this information that can be valuable to a real state agency coming in to market. Feel free to dive into the notebook, if you want find out what other factor has influence on the price.
![photo_2021-11-04 16 01 31](https://user-images.githubusercontent.com/79936222/140375024-1f532ece-8c06-4aca-bc43-2ca38eef0060.jpeg)

### Overview - Prediction model
After having trained the data, the explain_variance_score tells us we are off by 20%. And we are being punished by the more expensive houses. Since the model seemed to perform quite well from 0 to 200k. Therefore, we could look into dropping those outliers and see if it yields better results.

![photo_2021-11-04 16 13 44](https://user-images.githubusercontent.com/79936222/140377037-b29d31d9-95f6-4b4b-b899-4385e7b47ff9.jpeg)
