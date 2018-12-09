# AirBnb Price Modeling

##### Contributers:
- Andrew Zhang

Airbnb, although relatively new, has brought about a huge change in the field of hospitality. Rather than stay in hotels or motels, people now have the option to stay in the comfort of other people’s homes for a much cheaper rate. Airbnb allows it’s hosts to come up with prices for people who decide to stay in their homes, but Airbnb makes recommendations on prices as well. For this particular study, we want to look at a city that has a sizable number of listings. Therefore, we’ve selected Los Angeles, as it is a popular hotspot for tourism and hospitality. The goal of this project is to understand how Airbnb prices listings and whether or not we can create a model that can accurately predict different years of listings. Due to the abundance of data per room rental, we decided to create a model for each of the three room types to understand the characteristics of each rental type. We then applied the “best” models to the 2014 and 2017 AirBnb datasets to see how well the models predicted prices and compared those predictions to the actual prices of the listing. We suspect that the 2017 will be predicted better than 2014 as there is a lower likelihood that Airbnb would have changed their pricing criteria in such a short amount of time. 

## Methods
The dataset was split into 3 separate datasets based on rental types:
- Entire Apartment/Home
- Private Room
- Shared Room

### Predictive Algorithms
- **Linear Regression**
- **Log Linear Regression**
- **Multilevel Hierarchical Modeling**

## Conclusion
We found that pricing was often associated with the number of bedrooms of the listing, the number of accommodations of the listing, and the average rent prices of that particular neighborhood. After selecting our most optimal models, we applied the model to the 2014 and 2017 datasets to compare the predictions against the actual listing price. Although it makes no sense from a business standpoint to predict 2014 prices, we use it as a reference and comparison for the 2017 predictions. We can see that, comparing the two plots, the 2016 model doesn't predict well on 2014 as the predictions are mostly under the actual listing prices. Compared to the 2017 plot, the model does a decent job of predicting, allowing us to conclude that the models we created work well on the 2017 data and not on the 2014 data. Logically, this could be because there was more time between 2014 and 2016, allowing for more possibility of a criteria change when it came to pricing, whereas, since 2017 and 2016 are closer, the pricing criteria should be similar. 
