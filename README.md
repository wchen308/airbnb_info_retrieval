# Boston AirBnB Market Information Retrieval

## Motivation
Boston is one of the major cities in the United States. According to the Massachusetts Office of Travel and Tourism, Massachusetts hosted 24.2 million domestic visitors and 2.3 million international visitors in 2017. Before we travel, we would like to do some research about a city. For example, which area should we stay? What problems we may need to prepare in advance, Do we need to rent a car? 

With Boston AirBnB data, we may be able to retrieve some information. The data from Kaggle: https://www.kaggle.com/airbnb/boston includes calendar, listings and review of Boston AirBnB. In this project, I would like to provide insights for the following 3 questions:
	1. What are busy time to visit Boston?
	2. What do visitors like and dislike about their AirBnB journey in Boston?
	3. What are general vibes for different neighborhoods in Boston?
  
Also, some technical skills and problems will be discussed.

## What are busy time to visit Boston?
This calendar data includes price and availability info for 3585 listings. A listing is unavailable for 2 potential reasons:
	1. This listing is rented
	2. The owner of this listing does not make it available.

Hence, we can estimate the volume of visitors by both price and availability. When price rises up and availability drops down, there is a busy time to visit Boston.

![datasize.png](image/datasize.png)

This figure shows the average price and overall availability of 3585 AirBnB listings in Boston by each month. From January to August, price increases and availability decreases. In April, price sharply increases and availability drops to the lowest among these 8 months, which implies that April is a busy month for Boston to host visitors.

In September, price hugely increases and availability hugely drops. Starting from September, price decreases and availability increases. This calendar data has daily price and availability of 3585 listings only from Sep 06, 2016 to Sep 05, 2017. Here are 2 potential reasons for the huge change in September in this figure:
	1. More people do AirBnB business in 2017 than in 2016. Hence, customers have more new options and fewer people may choose the original listings in 2017.
	2. Not all of these 3585 listings have started to do AirBnB business since Sep 2016.

In general, with 2016-17 Boston AirBnB calendar data, April seems to be a busy month. More calendar years of data are recommended to further justify the overall trend and seasonally. 

## What do visitors like and dislike about their AirBnB journey in Boston?

## What are vibes for different neighborhoods in Boston?
